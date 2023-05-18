```mermaid
classDiagram
  class `<CoFH ASM>`["CoFH ASM"] {
    id: <CoFH ASM>
    version: 000
    authors: 
  }

  class `AWWayofTime`["Blood Magic: Alchemical Wizardry"] {
    id: AWWayofTime
    version: 1.7.10-1.3.3-17
    authors: WayofTime
  }

  class `ActuallyAdditions`["Actually Additions"] {
    id: ActuallyAdditions
    version: 1.7.10-r21
    authors: Ellpeck
  }
  `ActuallyAdditions` <-- `BuildCraft|Energy`

  class `AgriCraft`["AgriCraft"] {
    id: AgriCraft
    version: 1.5.0
    authors: InfinityRaider
  }

  class `Avaritia`["Avaritia"] {
    id: Avaritia
    version: 1.41
    authors: SpitefulFox, TTFTCUTS
  }
  `Avaritia` <-- `Thaumcraft`
  `Avaritia` <-- `AWWayofTime`
  `Avaritia` <-- `Botania`

  class `Baubles`["Baubles"] {
    id: Baubles
    version: 1.0.1.16
    authors: Azanor
  }

  class `Botania`["Botania"] {
    id: Botania
    version: 1.9.23-GTNH
    authors: Vazkii
  }
  `Botania` <-- `Baubles`
  `Botania` <-- `Thaumcraft`

  class `BrandonsCore`["Brandon's Core"] {
    id: BrandonsCore
    version: 1.0.0.13-GTNH
    authors: brandon3055
  }

  class `BuildCraft|Builders`["BC Builders"] {
    id: BuildCraft|Builders
    version: 7.1.33
    authors: SpaceToad, BuildCraft Team
  }
  `BuildCraft|Builders` <-- `BuildCraft|Core`

  class `BuildCraft|Compat`["BuildCraft Compat"] {
    id: BuildCraft|Compat
    version: 7.1.14
    authors: asie, BuildCraft Team
  }
  `BuildCraft|Compat` <-- `BuildCraft|Core`
  `BuildCraft|Compat` <-- `BuildCraft|Transport`
  `BuildCraft|Compat` <-- `BuildCraft|Builders`

  class `BuildCraft|Core`["BuildCraft"] {
    id: BuildCraft|Core
    version: 7.1.33
    authors: SpaceToad, BuildCraft Team
  }

  class `BuildCraft|Energy`["BC Energy"] {
    id: BuildCraft|Energy
    version: 7.1.33
    authors: SpaceToad, BuildCraft Team
  }
  `BuildCraft|Energy` <-- `BuildCraft|Core`

  class `BuildCraft|Factory`["BC Factory"] {
    id: BuildCraft|Factory
    version: 7.1.33
    authors: SpaceToad, BuildCraft Team
  }
  `BuildCraft|Factory` <-- `BuildCraft|Core`

  class `BuildCraft|Robotics`["BC Robotics"] {
    id: BuildCraft|Robotics
    version: 7.1.33
    authors: SpaceToad, BuildCraft Team
  }
  `BuildCraft|Robotics` <-- `BuildCraft|Core`

  class `BuildCraft|Silicon`["BC Silicon"] {
    id: BuildCraft|Silicon
    version: 7.1.33
    authors: SpaceToad, BuildCraft Team
  }
  `BuildCraft|Silicon` <-- `BuildCraft|Core`

  class `BuildCraft|Transport`["BC Transport"] {
    id: BuildCraft|Transport
    version: 7.1.33
    authors: SpaceToad, BuildCraft Team
  }
  `BuildCraft|Transport` <-- `BuildCraft|Core`

  class `CoFHCore`["CoFH Core"] {
    id: CoFHCore
    version: 3.1.4
    authors: Team CoFH
  }

  class `CodeChickenCore`["CodeChicken Core"] {
    id: CodeChickenCore
    version: 1.1.11
    authors: 
  }

  class `DraconicEvolution`["Draconic Evolution"] {
    id: DraconicEvolution
    version: 1.1.16-GTNH
    authors: brandon3055
  }
  `DraconicEvolution` <-- `NotEnoughItems`
  `DraconicEvolution` <-- `BrandonsCore`

  class `EnderIO`["Ender IO"] {
    id: EnderIO
    version: 2.4.16
    authors: CrazyPants, tterrag
  }
  `EnderIO` <-- `endercore`
  `EnderIO` <-- `MineFactoryReloaded`
  `EnderIO` <-- `Thaumcraft`
  `EnderIO` <-- `appliedenergistics2`
  `EnderIO` <-- `chisel`

  class `EnderStorage`["EnderStorage"] {
    id: EnderStorage
    version: 1.4.12
    authors: ChickenBones
  }
  `EnderStorage` <-- `CodeChickenCore`

  class `ExtraUtilities`["Extra Utilities"] {
    id: ExtraUtilities
    version: 1.2.12
    authors: RWTema
  }
  `ExtraUtilities` <-- `ForgeMultipart`
  `ExtraUtilities` <-- `Baubles`

  class `ForgeMicroblock`["Forge Microblocks"] {
    id: ForgeMicroblock
    version: 1.2.0.345
    authors: 
  }
  `ForgeMicroblock` <-- `ForgeMultipart`

  class `ForgeMultipart`["Forge Multipart"] {
    id: ForgeMultipart
    version: 1.2.0.345
    authors: 
  }

  class `IC2`["IndustrialCraft 2"] {
    id: IC2
    version: 2.2.827-experimental
    authors: Alblaka, Player, RichardG, Thunderdark, GregoriusT, alexthesax, Drashian, Elementalist, Feanturi, Lurch1985, SirusKing, tahu44, Aroma1997
  }

  class `LogisticsPipes`["Logistics Pipes"] {
    id: LogisticsPipes
    version: 1.0.1-GTNH
    authors: RS485, LP Team
  }
  `LogisticsPipes` <-- `BuildCraft|Core`
  `LogisticsPipes` <-- `BuildCraft|Transport`
  `LogisticsPipes` <-- `BuildCraft|Silicon`
  `LogisticsPipes` <-- `IC2`
  `LogisticsPipes` <-- `Thaumcraft`

  class `Mantle`["Mantle"] {
    id: Mantle
    version: 0.3.6
    authors: 
  }

  class `McMultipart`["Minecraft Multipart Plugin"] {
    id: McMultipart
    version: 1.2.0.345
    authors: 
  }

  class `Mekanism`["Mekanism Community Edition"] {
    id: Mekanism
    version: 9.10.28
    authors: 
  }
  `Mekanism` <-- `ForgeMultipart`
  `Mekanism` <-- `IC2`
  `Mekanism` <-- `CoFHCore`

  class `MekanismGenerators`["MekanismGenerators Community Edition"] {
    id: MekanismGenerators
    version: 9.10.28
    authors: aidancbrady
  }
  `MekanismGenerators` <-- `Mekanism`

  class `MekanismTools`["MekanismTools Community Edition"] {
    id: MekanismTools
    version: 9.10.28
    authors: aidancbrady
  }
  `MekanismTools` <-- `Mekanism`

  class `MineFactoryReloaded`["MineFactory Reloaded"] {
    id: MineFactoryReloaded
    version: 2.8.1
    authors: PowerCrystals, TehKrush, AtomicStryker, Feanorith, skyboy026
  }
  `MineFactoryReloaded` <-- `CoFHCore`

  class `MineFactoryReloaded|CompatAppliedEnergistics`["MFR Compat: Applied Energistics"] {
    id: MineFactoryReloaded|CompatAppliedEnergistics
    version: 2.8.1
    authors: PowerCrystals
  }
  `MineFactoryReloaded|CompatAppliedEnergistics` <-- `MineFactoryReloaded`
  `MineFactoryReloaded|CompatAppliedEnergistics` <-- `appliedenergistics2`

  class `MineFactoryReloaded|CompatAtum`["MFR Compat: Atum"] {
    id: MineFactoryReloaded|CompatAtum
    version: 2.8.1
    authors: PowerCrystals
  }
  `MineFactoryReloaded|CompatAtum` <-- `MineFactoryReloaded`

  class `MineFactoryReloaded|CompatBackTools`["MFR Compat: BackTools"] {
    id: MineFactoryReloaded|CompatBackTools
    version: 2.8.1
    authors: PowerCrystals
  }
  `MineFactoryReloaded|CompatBackTools` <-- `MineFactoryReloaded`

  class `MineFactoryReloaded|CompatBuildCraft`["MFR Compat: BuildCraft"] {
    id: MineFactoryReloaded|CompatBuildCraft
    version: 2.8.1
    authors: PowerCrystals
  }
  `MineFactoryReloaded|CompatBuildCraft` <-- `MineFactoryReloaded`
  `MineFactoryReloaded|CompatBuildCraft` <-- `BuildCraft|Core`

  class `MineFactoryReloaded|CompatChococraft`["MFR Compat: Chococraft"] {
    id: MineFactoryReloaded|CompatChococraft
    version: 2.8.1
    authors: PowerCrystals
  }
  `MineFactoryReloaded|CompatChococraft` <-- `MineFactoryReloaded`

  class `MineFactoryReloaded|CompatExtraBiomes`["MFR Compat: ExtraBiomes"] {
    id: MineFactoryReloaded|CompatExtraBiomes
    version: 2.8.1
    authors: PowerCrystals
  }
  `MineFactoryReloaded|CompatExtraBiomes` <-- `MineFactoryReloaded`

  class `MineFactoryReloaded|CompatForestry`["MFR Compat: Forestry"] {
    id: MineFactoryReloaded|CompatForestry
    version: 2.8.1
    authors: PowerCrystals
  }
  `MineFactoryReloaded|CompatForestry` <-- `MineFactoryReloaded`

  class `MineFactoryReloaded|CompatForgeMicroblock`["MFR Compat: ForgeMicroblock"] {
    id: MineFactoryReloaded|CompatForgeMicroblock
    version: 2.8.1
    authors: PowerCrystals
  }
  `MineFactoryReloaded|CompatForgeMicroblock` <-- `MineFactoryReloaded`

  class `MineFactoryReloaded|CompatIC2`["MFR Compat: IC2"] {
    id: MineFactoryReloaded|CompatIC2
    version: 2.8.1
    authors: PowerCrystals
  }
  `MineFactoryReloaded|CompatIC2` <-- `MineFactoryReloaded`
  `MineFactoryReloaded|CompatIC2` <-- `IC2`

  class `MineFactoryReloaded|CompatProjRed`["MFR Compat ProjectRed"] {
    id: MineFactoryReloaded|CompatProjRed
    version: 2.8.1
    authors: PowerCrystals
  }
  `MineFactoryReloaded|CompatProjRed` <-- `MineFactoryReloaded`

  class `MineFactoryReloaded|CompatRailcraft`["MFR Compat: Railcraft"] {
    id: MineFactoryReloaded|CompatRailcraft
    version: 2.8.1
    authors: skyboy
  }
  `MineFactoryReloaded|CompatRailcraft` <-- `MineFactoryReloaded`

  class `MineFactoryReloaded|CompatSufficientBiomes`["MFR Compat: Sufficient Biomes"] {
    id: MineFactoryReloaded|CompatSufficientBiomes
    version: 2.8.1
    authors: PowerCrystals
  }
  `MineFactoryReloaded|CompatSufficientBiomes` <-- `MineFactoryReloaded`

  class `MineFactoryReloaded|CompatTConstruct`["MFR Compat: Tinkers' Construct"] {
    id: MineFactoryReloaded|CompatTConstruct
    version: 2.8.1
    authors: PowerCrystals
  }
  `MineFactoryReloaded|CompatTConstruct` <-- `MineFactoryReloaded`
  `MineFactoryReloaded|CompatTConstruct` <-- `TConstruct`

  class `MineFactoryReloaded|CompatThaumcraft`["MFR Compat: Thaumcraft"] {
    id: MineFactoryReloaded|CompatThaumcraft
    version: 2.8.1
    authors: PowerCrystals
  }
  `MineFactoryReloaded|CompatThaumcraft` <-- `MineFactoryReloaded`
  `MineFactoryReloaded|CompatThaumcraft` <-- `Thaumcraft`

  class `MineFactoryReloaded|CompatThermalExpansion`["MFR Compat: Thermal Expansion"] {
    id: MineFactoryReloaded|CompatThermalExpansion
    version: 2.8.1
    authors: PowerCrystals
  }
  `MineFactoryReloaded|CompatThermalExpansion` <-- `MineFactoryReloaded`

  class `MineFactoryReloaded|CompatTwilightForest`["MFR Compat: TwilightForest"] {
    id: MineFactoryReloaded|CompatTwilightForest
    version: 2.8.1
    authors: PowerCrystals
  }
  `MineFactoryReloaded|CompatTwilightForest` <-- `MineFactoryReloaded`
  `MineFactoryReloaded|CompatTwilightForest` <-- `TwilightForest`

  class `MineFactoryReloaded|CompatVanilla`["MFR Compat: Vanilla"] {
    id: MineFactoryReloaded|CompatVanilla
    version: 2.8.1
    authors: PowerCrystals
  }
  `MineFactoryReloaded|CompatVanilla` <-- `MineFactoryReloaded`

  class `NotEnoughItems`["NotEnoughItems"] {
    id: NotEnoughItems
    version: 2.3.53-GTNH
    authors: ChickenBones, mitchej123
  }
  `NotEnoughItems` <-- `CodeChickenCore`

  class `OpenBlocks`["OpenBlocks"] {
    id: OpenBlocks
    version: 1.7.0-GTNH
    authors: Mikee, NeverCast, boq, Lyqyd
  }
  `OpenBlocks` <-- `OpenMods`

  class `OpenComputers`["OpenComputers"] {
    id: OpenComputers
    version: 1.9.5-GTNH
    authors: Florian 'Sangar' Nuecke, Johannes 'Lord Joda' Lohrer, Everyone who contributed to the mod on Github - thank you!
  }
  `OpenComputers` <-- `BuildCraft|Core`
  `OpenComputers` <-- `EnderStorage`
  `OpenComputers` <-- `ForgeMultipart`
  `OpenComputers` <-- `IC2`
  `OpenComputers` <-- `MineFactoryReloaded`
  `OpenComputers` <-- `Thaumcraft`

  class `OpenComputers|Core`["OpenComputers (Core)"] {
    id: OpenComputers|Core
    version: @VERSION@
    authors: Sangar
  }

  class `OpenMods`["OpenMods"] {
    id: OpenMods
    version: 0.10.6
    authors: 
  }
  `OpenMods` <-- `OpenModsCore`

  class `OpenModsCore`["OpenModsCore"] {
    id: OpenModsCore
    version: 0.10.6
    authors: Mikee, NeverCast, boq
  }

  class `TConstruct`["Tinkers' Construct"] {
    id: TConstruct
    version: 1.9.32-GTNH
    authors: mDiyo, fuj1n, ProgWML6, Sunstrike, Pillbox, boni
  }
  `TConstruct` <-- `Mantle`
  `TConstruct` <-- `MineFactoryReloaded`
  `TConstruct` <-- `CoFHCore`
  `TConstruct` <-- `NotEnoughItems`

  class `ThE-core`["Thaumic Energistics Core"] {
    id: ThE-core
    version: 1.0.0.1
    authors: Nividica
  }

  class `Thaumcraft`["Thaumcraft"] {
    id: Thaumcraft
    version: 4.2.3.5
    authors: 
  }
  `Thaumcraft` <-- `Baubles`

  class `TwilightForest`["The Twilight Forest"] {
    id: TwilightForest
    version: 2.4.3
    authors: 
  }

  class `advgenerators`["Advanced Generators"] {
    id: advgenerators
    version: 0.9.20.123
    authors: bdew
  }
  `advgenerators` <-- `BuildCraft|Silicon`
  `advgenerators` <-- `IC2`
  `advgenerators` <-- `CoFHCore`
  `advgenerators` <-- `bdlib`

  class `ae2fc`["AE2 Fluid Crafting"] {
    id: ae2fc
    version: 1.1.20-gtnh
    authors: GlodBlock
  }
  `ae2fc` <-- `appliedenergistics2`

  class `ae2stuff`["AE2 Stuff"] {
    id: ae2stuff
    version: 0.5.1.16-GTNH
    authors: bdew
  }
  `ae2stuff` <-- `appliedenergistics2`
  `ae2stuff` <-- `bdlib`

  class `ae2wct`["AE2 Wireless Crafting Terminal"] {
    id: ae2wct
    version: 1.9.0
    authors: TheRealp455w0rd
  }
  `ae2wct` <-- `appliedenergistics2`
  `ae2wct` <-- `NotEnoughItems`

  class `appliedenergistics2`["Applied Energistics 2"] {
    id: appliedenergistics2
    version: rv3-beta-212-GTNH-1-ga99d8df.dirty
    authors: AlgorithmX2
  }
  `appliedenergistics2` <-- `appliedenergistics2-core`

  class `appliedenergistics2-core`["Applied Energistics 2 Core"] {
    id: appliedenergistics2-core
    version: rv3-beta-212-GTNH-1-ga99d8df.dirty
    authors: AlgorithmX2
  }

  class `avaritiaddons`["Avaritiaddons"] {
    id: avaritiaddons
    version: 1.5.5-GTNH
    authors: WanionCane
  }
  `avaritiaddons` <-- `Avaritia`
  `avaritiaddons` <-- `wanionlib`

  class `bdlib`["BD lib"] {
    id: bdlib
    version: 1.9.8-GTNH
    authors: bdew
  }

  class `chisel`["Chisel"] {
    id: chisel
    version: 2.11.0-GTNH
    authors: tterrag, Drullkus, minecreatr
  }
  `chisel` <-- `ForgeMultipart`
  `chisel` <-- `Thaumcraft`
  `chisel` <-- `appliedenergistics2`
  `chisel` <-- `AWWayofTime`
  `chisel` <-- `TwilightForest`

  class `endercore`["EnderCore"] {
    id: endercore
    version: 0.2.13
    authors: tterrag, CrazyPants
  }
  `endercore` <-- `gtnhlib`

  class `gasstation`["UniMixins: GasStation"] {
    id: gasstation
    version: 0.5.1+uni.0.1.7.1
    authors: FalsePattern
  }

  class `gtnhlib`["GTNH Lib"] {
    id: gtnhlib
    version: 0.0.13
    authors: mitchej123
  }

  class `gtnhmixins`["UniMixins: GTNHMixins"] {
    id: gtnhmixins
    version: 2.1.9+uni.0.1.7.1
    authors: mitchej123
  }

  class `hodgepodge`["Hodgepodge"] {
    id: hodgepodge
    version: 2.2.13
    authors: mitchej123, GTNewHorizons Team
  }
  `hodgepodge` <-- `gtnhmixins`

  class `magicalcrops`["Magical Crops: Core"] {
    id: magicalcrops
    version: 4.0.0_PUBLIC_BETA_4b
    authors: Mark719
  }
  `magicalcrops` <-- `appliedenergistics2`
  `magicalcrops` <-- `Mekanism`

  class `magicalcropsarmour`["Magical Crops: Armoury"] {
    id: magicalcropsarmour
    version: 4.0.0_PUBLIC_BETA_4
    authors: 
  }
  `magicalcropsarmour` <-- `magicalcrops`

  class `magicalcropsdeco`["Magical Crops: Decorative"] {
    id: magicalcropsdeco
    version: 4.0.0_PUBLIC_BETA_4a
    authors: 
  }
  `magicalcropsdeco` <-- `magicalcrops`

  class `mfrmagiccropscompat`["MinefactoryReloaded & MagicalCrops extra compatibility"] {
    id: mfrmagiccropscompat
    version: 1.2
    authors: Portablejim
  }
  `mfrmagiccropscompat` <-- `magicalcrops`

  class `mixinbooterlegacy`["UniMixins: MixinBooterLegacy"] {
    id: mixinbooterlegacy
    version: 1.2.1+uni.0.1.7.1
    authors: Rongmario, tox1cozZ
  }

  class `mixinextras`["UniMixins: MixinExtras"] {
    id: mixinextras
    version: 0.1.1+uni.0.1.7.1
    authors: LlamaLad7
  }

  class `mixingasm`["UniMixins: Mixingasm"] {
    id: mixingasm
    version: 0.2.2+uni.0.1.7.1
    authors: makamys
  }

  class `mod-diagram`["Mod Diagram"] {
    id: mod-diagram
    version: v1.0
    authors: juanmuscaria
  }

  class `neenergistics`["NotEnoughEnergistics"] {
    id: neenergistics
    version: 1.4.0
    authors: vfyjxf
  }
  `neenergistics` <-- `NotEnoughItems`
  `neenergistics` <-- `appliedenergistics2`
  `neenergistics` <-- `ae2wct`
  `neenergistics` <-- `ae2fc`

  class `spongemixins`["UniMixins: SpongeMixins"] {
    id: spongemixins
    version: 2.0.1+gtnh.uni.0.1.7.1
    authors: Time_Conqueror, mitchej123
  }

  class `thaumicenergistics`["Thaumic Energistics"] {
    id: thaumicenergistics
    version: 1.4.2-GTNH
    authors: Nividica
  }
  `thaumicenergistics` <-- `ThE-core`
  `thaumicenergistics` <-- `appliedenergistics2`
  `thaumicenergistics` <-- `Thaumcraft`

  class `unimixins`["UniMixins"] {
    id: unimixins
    version: 0.1.7.1
    authors: makamys
  }

  class `unimixins-compat`["UniMixins: Compatibility"] {
    id: unimixins-compat
    version: 0.1.7.1
    authors: makamys
  }

  class `unimixins-mixin`["UniMixins: Mixin (UniMix)"] {
    id: unimixins-mixin
    version: 0.1.7.1+unimix.0.12.1-mixin.0.8.5
    authors: makamys
  }

  class `wanionlib`["WanionLib"] {
    id: wanionlib
    version: 1.8.4
    authors: WanionCane
  }

```
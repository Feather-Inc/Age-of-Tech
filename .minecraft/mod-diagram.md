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

  class `AppleCore`["AppleCore"] {
    id: AppleCore
    version: 3.2.10
    authors: squeek
  }

  class `ArchitectureCraft`["ArchitectureCraft"] {
    id: ArchitectureCraft
    version: 1.8.6
    authors: 
  }

  class `Avaritia`["Avaritia"] {
    id: Avaritia
    version: 1.41
    authors: SpitefulFox, TTFTCUTS
  }
  `Avaritia` <-- `Thaumcraft`
  `Avaritia` <-- `AWWayofTime`
  `Avaritia` <-- `Botania`

  class `Backpack`["Backpack Editted for ModdedNetwork"] {
    id: Backpack
    version: 2.2.11-GTNH
    authors: 
  }

  class `Baubles`["Baubles"] {
    id: Baubles
    version: 1.0.1.16
    authors: Azanor
  }

  class `BinnieCore`["Binnie Core"] {
    id: BinnieCore
    version: 2.1.1
    authors: Binnie
  }
  `BinnieCore` <-- `Forestry`
  `BinnieCore` <-- `gtnhlib`

  class `BiomesOPlenty`["Biomes O' Plenty"] {
    id: BiomesOPlenty
    version: 2.1.0
    authors: Adubbz, Amnet, Forstride, ted80
  }

  class `BloodArsenal`["Blood Arsenal"] {
    id: BloodArsenal
    version: 1.2.10
    authors: 
  }
  `BloodArsenal` <-- `AWWayofTime`
  `BloodArsenal` <-- `NotEnoughItems`
  `BloodArsenal` <-- `Baubles`
  `BloodArsenal` <-- `TConstruct`
  `BloodArsenal` <-- `Waila`
  `BloodArsenal` <-- `ForbiddenMagic`

  class `Botania`["Botania"] {
    id: Botania
    version: 1.9.23-GTNH
    authors: Vazkii
  }
  `Botania` <-- `Baubles`
  `Botania` <-- `Thaumcraft`

  class `Botany`["Botany"] {
    id: Botany
    version: 2.1.1
    authors: Binnie
  }
  `Botany` <-- `BinnieCore`

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
  `BuildCraft|Compat` <-- `Forestry`
  `BuildCraft|Compat` <-- `BuildCraft|Transport`
  `BuildCraft|Compat` <-- `BuildCraft|Builders`
  `BuildCraft|Compat` <-- `ThermalExpansion`

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

  class `CarpentersBlocks`["Carpenter's Blocks"] {
    id: CarpentersBlocks
    version: 3.4.0-GTNH
    authors: Mineshopper
  }

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
  `DraconicEvolution` <-- `ThermalExpansion`
  `DraconicEvolution` <-- `ThermalFoundation`
  `DraconicEvolution` <-- `BrandonsCore`

  class `EnderIO`["Ender IO"] {
    id: EnderIO
    version: 2.4.16
    authors: CrazyPants, tterrag
  }
  `EnderIO` <-- `endercore`
  `EnderIO` <-- `MineFactoryReloaded`
  `EnderIO` <-- `Forestry`
  `EnderIO` <-- `Waila`
  `EnderIO` <-- `Thaumcraft`
  `EnderIO` <-- `appliedenergistics2`
  `EnderIO` <-- `chisel`

  class `EnderStorage`["EnderStorage"] {
    id: EnderStorage
    version: 1.4.12
    authors: ChickenBones
  }
  `EnderStorage` <-- `CodeChickenCore`

  class `ExtraBees`["Extra Bees"] {
    id: ExtraBees
    version: 2.1.1
    authors: Binnie
  }
  `ExtraBees` <-- `BinnieCore`

  class `ExtraTrees`["Extra Trees"] {
    id: ExtraTrees
    version: 2.1.1
    authors: Binnie
  }
  `ExtraTrees` <-- `BinnieCore`

  class `ExtraUtilities`["Extra Utilities"] {
    id: ExtraUtilities
    version: 1.2.12
    authors: RWTema
  }
  `ExtraUtilities` <-- `ForgeMultipart`
  `ExtraUtilities` <-- `Baubles`
  `ExtraUtilities` <-- `ThermalFoundation`

  class `ExtrabiomesXL`["ExtrabiomesXL"] {
    id: ExtrabiomesXL
    version: 3.16.4
    authors: MisterFiber, ScottKillen, JLBShecky, allaryin, bspkrs
  }

  class `ForbiddenMagic`["Forbidden Magic"] {
    id: ForbiddenMagic
    version: 0.6.7-GTNH
    authors: SpitefulFox
  }
  `ForbiddenMagic` <-- `Thaumcraft`
  `ForbiddenMagic` <-- `ThaumicTinkerer`
  `ForbiddenMagic` <-- `AWWayofTime`
  `ForbiddenMagic` <-- `Botania`

  class `Forestry`["Forestry"] {
    id: Forestry
    version: 4.6.7
    authors: SirSengir
  }
  `Forestry` <-- `ExtrabiomesXL`
  `Forestry` <-- `BiomesOPlenty`
  `Forestry` <-- `IC2`

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

  class `ForgeRelocation`["ForgeRelocation"] {
    id: ForgeRelocation
    version: 0.0.3
    authors: MrTJP
  }

  class `Genetics`["Genetics"] {
    id: Genetics
    version: 2.1.1
    authors: Binnie
  }
  `Genetics` <-- `BinnieCore`

  class `IC2`["IndustrialCraft 2"] {
    id: IC2
    version: 2.2.827-experimental
    authors: Alblaka, Player, RichardG, Thunderdark, GregoriusT, alexthesax, Drashian, Elementalist, Feanturi, Lurch1985, SirusKing, tahu44, Aroma1997
  }

  class `IguanaTweaksTConstruct`["Iguana Tinker Tweaks"] {
    id: IguanaTweaksTConstruct
    version: 2.3.0
    authors: boni, iguana_man
  }
  `IguanaTweaksTConstruct` <-- `TConstruct`
  `IguanaTweaksTConstruct` <-- `ForgeMultipart`

  class `InGameInfoXML`["InGame Info XML"] {
    id: InGameInfoXML
    version: 2.8.3.96
    authors: Lunatrius
  }
  `InGameInfoXML` <-- `LunatriusCore`

  class `InfernalMobs`["Infernal Mobs"] {
    id: InfernalMobs
    version: 1.7.8-GTNH
    authors: 
  }

  class `IronChest`["Iron Chests"] {
    id: IronChest
    version: 6.0.71
    authors: 
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
  `LogisticsPipes` <-- `Forestry`
  `LogisticsPipes` <-- `Thaumcraft`
  `LogisticsPipes` <-- `ThermalExpansion`

  class `LunatriusCore`["LunatriusCore"] {
    id: LunatriusCore
    version: 1.1.7-GTNH
    authors: Lunatrius
  }

  class `MCFrames`["MCFrames"] {
    id: MCFrames
    version: 0.0.3
    authors: MrTJP
  }

  class `MagicBees`["Magic Bees"] {
    id: MagicBees
    version: 2.6.4-GTNH
    authors: 
  }
  `MagicBees` <-- `Forestry`
  `MagicBees` <-- `Baubles`
  `MagicBees` <-- `Thaumcraft`
  `MagicBees` <-- `ExtraBees`
  `MagicBees` <-- `TConstruct`
  `MagicBees` <-- `ThermalFoundation`
  `MagicBees` <-- `ThermalExpansion`
  `MagicBees` <-- `AWWayofTime`
  `MagicBees` <-- `Botania`
  `MagicBees` <-- `appliedenergistics2`

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
  `Mekanism` <-- `MineTweaker3`

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
  `MineFactoryReloaded|CompatExtraBiomes` <-- `ExtrabiomesXL`

  class `MineFactoryReloaded|CompatForestry`["MFR Compat: Forestry"] {
    id: MineFactoryReloaded|CompatForestry
    version: 2.8.1
    authors: PowerCrystals
  }
  `MineFactoryReloaded|CompatForestry` <-- `MineFactoryReloaded`
  `MineFactoryReloaded|CompatForestry` <-- `Forestry`

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
  `MineFactoryReloaded|CompatProjRed` <-- `ProjRed|Core`
  `MineFactoryReloaded|CompatProjRed` <-- `ProjRed|Exploration`

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
  `MineFactoryReloaded|CompatThermalExpansion` <-- `ThermalExpansion`

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

  class `MineMenu`["MineMenu"] {
    id: MineMenu
    version: 1.7.10-1.2.0.B44
    authors: 
  }

  class `MineTweaker3`["MineTweaker 3"] {
    id: MineTweaker3
    version: 3.2.12
    authors: Stan Hebben
  }

  class `MobiusCore`["MobiusCore"] {
    id: MobiusCore
    version: 1.3.8-mapless
    authors: ProfMobius
  }

  class `MouseTweaks`["Mouse Tweaks"] {
    id: MouseTweaks
    version: 2.4.8-GTNH
    authors: YaLTeR
  }

  class `MrTJPCoreMod`["MrTJPCore"] {
    id: MrTJPCoreMod
    version: 1.1.4
    authors: MrTJP
  }

  class `NEIAddons`["NEI Addons"] {
    id: NEIAddons
    version: 1.12.22
    authors: bdew
  }
  `NEIAddons` <-- `NotEnoughItems`

  class `NEIAddons|AppEng`["NEI Addons: Applied Energistics 2"] {
    id: NEIAddons|AppEng
    version: 1.12.22
    authors: bdew
  }
  `NEIAddons|AppEng` <-- `NEIAddons`
  `NEIAddons|AppEng` <-- `appliedenergistics2`

  class `NEIAddons|Botany`["NEI Addons: Botany"] {
    id: NEIAddons|Botany
    version: 1.12.22
    authors: bdew
  }
  `NEIAddons|Botany` <-- `NEIAddons`
  `NEIAddons|Botany` <-- `Botany`

  class `NEIAddons|CraftingTables`["NEI Addons: Crafting Tables"] {
    id: NEIAddons|CraftingTables
    version: 1.12.22
    authors: bdew
  }
  `NEIAddons|CraftingTables` <-- `NEIAddons`

  class `NEIAddons|Developer`["NEI Addons: Developer Tools"] {
    id: NEIAddons|Developer
    version: 1.12.22
    authors: bdew
  }
  `NEIAddons|Developer` <-- `NEIAddons`

  class `NEIAddons|ExNihilo`["NEI Addons: Ex Nihilo"] {
    id: NEIAddons|ExNihilo
    version: 1.12.22
    authors: bdew
  }

  class `NEIAddons|Forestry`["NEI Addons: Forestry"] {
    id: NEIAddons|Forestry
    version: 1.12.22
    authors: bdew
  }
  `NEIAddons|Forestry` <-- `NEIAddons`
  `NEIAddons|Forestry` <-- `Forestry`

  class `NetherOres`["Nether Ores"] {
    id: NetherOres
    version: 2.3.1
    authors: PowerCrystals, TehKrush, AtomicStryker, skyboy026
  }
  `NetherOres` <-- `CoFHCore`

  class `NotEnoughItems`["NotEnoughItems"] {
    id: NotEnoughItems
    version: 2.3.53-GTNH
    authors: ChickenBones, mitchej123
  }
  `NotEnoughItems` <-- `CodeChickenCore`

  class `NuclearCraft`["NuclearCraft"] {
    id: NuclearCraft
    version: 1.9g
    authors: turbodiesel4598
  }

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
  `OpenComputers` <-- `ProjRed|Transmission`
  `OpenComputers` <-- `Thaumcraft`
  `OpenComputers` <-- `ThermalExpansion`

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

  class `Opis`["Opis"] {
    id: Opis
    version: 1.3.8-mapless
    authors: 
  }

  class `ProjRed|Compatibility`["ProjectRed Compatibility"] {
    id: ProjRed|Compatibility
    version: 4.7.9-GTNH
    authors: 
  }
  `ProjRed|Compatibility` <-- `ProjRed|Core`
  `ProjRed|Compatibility` <-- `ProjRed|Transmission`
  `ProjRed|Compatibility` <-- `ProjRed|Exploration`
  `ProjRed|Compatibility` <-- `ProjRed|Transportation`
  `ProjRed|Compatibility` <-- `TConstruct`

  class `ProjRed|Core`["ProjectRed Core"] {
    id: ProjRed|Core
    version: 4.7.9-GTNH
    authors: 
  }
  `ProjRed|Core` <-- `ForgeMultipart`
  `ProjRed|Core` <-- `MrTJPCoreMod`

  class `ProjRed|Expansion`["ProjectRed Expansion"] {
    id: ProjRed|Expansion
    version: 4.7.9-GTNH
    authors: 
  }
  `ProjRed|Expansion` <-- `ProjRed|Core`
  `ProjRed|Expansion` <-- `ProjRed|Transmission`

  class `ProjRed|Exploration`["ProjectRed Exploration"] {
    id: ProjRed|Exploration
    version: 4.7.9-GTNH
    authors: 
  }
  `ProjRed|Exploration` <-- `ProjRed|Core`

  class `ProjRed|Fabrication`["ProjectRed Fabrication"] {
    id: ProjRed|Fabrication
    version: 4.7.9-GTNH
    authors: 
  }
  `ProjRed|Fabrication` <-- `ProjRed|Core`
  `ProjRed|Fabrication` <-- `ProjRed|Integration`
  `ProjRed|Fabrication` <-- `ProjRed|Transmission`

  class `ProjRed|Illumination`["ProjectRed Illumination"] {
    id: ProjRed|Illumination
    version: 4.7.9-GTNH
    authors: 
  }
  `ProjRed|Illumination` <-- `ProjRed|Core`

  class `ProjRed|Integration`["ProjectRed Integration"] {
    id: ProjRed|Integration
    version: 4.7.9-GTNH
    authors: 
  }
  `ProjRed|Integration` <-- `ProjRed|Core`

  class `ProjRed|Transmission`["ProjectRed Transmission"] {
    id: ProjRed|Transmission
    version: 4.7.9-GTNH
    authors: 
  }
  `ProjRed|Transmission` <-- `ProjRed|Core`

  class `ProjRed|Transportation`["ProjectRed Transportation"] {
    id: ProjRed|Transportation
    version: 4.7.9-GTNH
    authors: 
  }
  `ProjRed|Transportation` <-- `ProjRed|Core`

  class `RandomThings`["RandomThings"] {
    id: RandomThings
    version: 2.4.3
    authors: Lumien
  }

  class `RelocationFMP`["RelocationFMP"] {
    id: RelocationFMP
    version: 0.0.4
    authors: MrTJP
  }
  `RelocationFMP` <-- `ForgeRelocation`
  `RelocationFMP` <-- `ForgeMultipart`

  class `Roguelike`["Roguelike Dungeons"] {
    id: Roguelike
    version: 1.5.3-GTNH
    authors: Greymerk
  }

  class `Schematica`["Schematica"] {
    id: Schematica
    version: 1.9.3-GTNH
    authors: Lunatrius
  }
  `Schematica` <-- `LunatriusCore`

  class `SpiceOfLife`["The Spice of Life - Carrot Edition"] {
    id: SpiceOfLife
    version: 2.1.0-carrot
    authors: squeek, mitchej123
  }
  `SpiceOfLife` <-- `AppleCore`

  class `StorageDrawers`["Storage Drawers"] {
    id: StorageDrawers
    version: 1.2.0-GTNH
    authors: 
  }

  class `TConstruct`["Tinkers' Construct"] {
    id: TConstruct
    version: 1.9.32-GTNH
    authors: mDiyo, fuj1n, ProgWML6, Sunstrike, Pillbox, boni
  }
  `TConstruct` <-- `Mantle`
  `TConstruct` <-- `MineFactoryReloaded`
  `TConstruct` <-- `ThermalExpansion`
  `TConstruct` <-- `ThermalFoundation`
  `TConstruct` <-- `CoFHCore`
  `TConstruct` <-- `NotEnoughItems`
  `TConstruct` <-- `Waila`

  class `TMechworks`["Tinkers Mechworks"] {
    id: TMechworks
    version: 0.2.16.4
    authors: 
  }
  `TMechworks` <-- `TConstruct`
  `TMechworks` <-- `Mantle`

  class `TaintedMagic`["Tainted Magic"] {
    id: TaintedMagic
    version: 7.6.2-GTNH
    authors: John Yorke (yorkeMC)
  }
  `TaintedMagic` <-- `Thaumcraft`
  `TaintedMagic` <-- `ThaumicTinkerer`

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

  class `ThaumcraftMobAspects`["Thaumcraft Mob Aspects"] {
    id: ThaumcraftMobAspects
    version: 1.0.0-GTNH
    authors: iguana_man, lycaon, XanderGryphon
  }
  `ThaumcraftMobAspects` <-- `Thaumcraft`

  class `ThaumicHorizons`["ThaumicHorizons"] {
    id: ThaumicHorizons
    version: 1.2.1.12
    authors: 
  }
  `ThaumicHorizons` <-- `Thaumcraft`

  class `ThaumicTinkerer`["Thaumic Tinkerer"] {
    id: ThaumicTinkerer
    version: 2.7.0
    authors: 
  }
  `ThaumicTinkerer` <-- `Thaumcraft`
  `ThaumicTinkerer` <-- `IC2`
  `ThaumicTinkerer` <-- `Waila`
  `ThaumicTinkerer` <-- `ForgeMultipart`

  class `ThaumicTinkerer-preloader`["Thaumic Tinkerer Core"] {
    id: ThaumicTinkerer-preloader
    version: 0.1
    authors: nekosune, Pixlepix, Vazkii
  }

  class `ThermalExpansion`["Thermal Expansion"] {
    id: ThermalExpansion
    version: 4.1.5
    authors: Team CoFH
  }
  `ThermalExpansion` <-- `CoFHCore`
  `ThermalExpansion` <-- `ThermalFoundation`

  class `ThermalFoundation`["Thermal Foundation"] {
    id: ThermalFoundation
    version: 1.2.6
    authors: Team CoFH
  }
  `ThermalFoundation` <-- `CoFHCore`

  class `TiCTooltips`["TiC Tooltips"] {
    id: TiCTooltips
    version: 1.2.10
    authors: squeek
  }
  `TiCTooltips` <-- `TConstruct`

  class `Translocator`["Translocator"] {
    id: Translocator
    version: 1.1.2.21
    authors: ChickenBones
  }
  `Translocator` <-- `CodeChickenCore`
  `Translocator` <-- `NotEnoughItems`

  class `TwilightForest`["The Twilight Forest"] {
    id: TwilightForest
    version: 2.4.3
    authors: 
  }

  class `UniDict`["UniDict"] {
    id: UniDict
    version: 2.9.2
    authors: WanionCane
  }

  class `Waila`["Waila"] {
    id: Waila
    version: 1.6.0
    authors: 
  }
  `Waila` <-- `NotEnoughItems`

  class `WailaHarvestability`["Waila Harvestability"] {
    id: WailaHarvestability
    version: 1.1.10-GTNH
    authors: squeek
  }
  `WailaHarvestability` <-- `TConstruct`

  class `WarpTheory`["WarpTheory"] {
    id: WarpTheory
    version: 1.2.16-GTNH
    authors: 
  }
  `WarpTheory` <-- `Baubles`
  `WarpTheory` <-- `Thaumcraft`

  class `advgenerators`["Advanced Generators"] {
    id: advgenerators
    version: 0.9.20.123
    authors: bdew
  }
  `advgenerators` <-- `BuildCraft|Silicon`
  `advgenerators` <-- `IC2`
  `advgenerators` <-- `CoFHCore`
  `advgenerators` <-- `ThermalExpansion`
  `advgenerators` <-- `bdlib`

  class `ae2fc`["AE2 Fluid Crafting"] {
    id: ae2fc
    version: 1.1.21-gtnh
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

  class `aether_legacy`["The Aether"] {
    id: aether_legacy
    version: 1.1.2.2
    authors: bconlon, Oscar Payn, Hugo Payn, JellySquid
  }

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

  class `atum`["Atum"] {
    id: atum
    version: 0.6.77
    authors: Shadowclaimer, lclc98, RebelKeithy
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

  class `bettercrashes`["BetterCrashes"] {
    id: bettercrashes
    version: 1.2.0-GTNH
    authors: vfyjxf
  }

  class `betterloadingscreen`["Better Loading Screen GTNH"] {
    id: betterloadingscreen
    version: 1.4.1-GTNH
    authors: AlexIIL, jackowski626
  }

  class `biggerpacketsplz`["Bigger Packets, please !"] {
    id: biggerpacketsplz
    version: 1.2
    authors: ElNounch
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

  class `controlling`["Controlling"] {
    id: controlling
    version: 1.0.0.5
    authors: Jaredlll08
  }

  class `cookingforblockheads`["Cooking For Blockheads"] {
    id: cookingforblockheads
    version: 1.2.14-GTNH
    authors: BlayTheNinth, ZeroTheShinigami, GTNH Team
  }

  class `cosmeticarmorreworked`["CosmeticArmorReworked"] {
    id: cosmeticarmorreworked
    version: 1.7.10-v7
    authors: zlainsama
  }

  class `craftpresence`["CraftPresence"] {
    id: craftpresence
    version: 1.8.10
    authors: CDA_Gaming
  }

  class `creativecore`["CreativeCore"] {
    id: creativecore
    version: 1.3.27-GTNH
    authors: 
  }

  class `custommainmenu`["Custom Main Menu"] {
    id: custommainmenu
    version: 1.9.4
    authors: 
  }

  class `debug`["debug"] {
    id: debug
    version: 1.0
    authors: 
  }

  class `defaultserverlist`["DefaultServerList"] {
    id: defaultserverlist
    version: 1.4.0
    authors: glowredman
  }
  `defaultserverlist` <-- `spongemixins`

  class `denseores`["Dense Ores"] {
    id: denseores
    version: 1.6.2
    authors: 
  }

  class `dsurround`["Dynamic Surroundings"] {
    id: dsurround
    version: 1.0.6.4
    authors: OreCruncher
  }

  class `endercore`["EnderCore"] {
    id: endercore
    version: 0.2.13
    authors: tterrag, CrazyPants
  }
  `endercore` <-- `gtnhlib`

  class `eplus`["Enchanting Plus"] {
    id: eplus
    version: 1.7.10-3.0.1
    authors: 
  }

  class `gadomancy`["Gadomancy"] {
    id: gadomancy
    version: 1.1.0
    authors: makeo, HellFirePvP
  }
  `gadomancy` <-- `Thaumcraft`
  `gadomancy` <-- `Waila`

  class `gasstation`["UniMixins: GasStation"] {
    id: gasstation
    version: 0.5.1+uni.0.1.7.1
    authors: FalsePattern
  }

  class `gendustry`["Gendustry"] {
    id: gendustry
    version: 1.6.5.5-GTNH
    authors: bdew
  }
  `gendustry` <-- `Forestry`
  `gendustry` <-- `BuildCraft|Silicon`
  `gendustry` <-- `IC2`
  `gendustry` <-- `CoFHCore`
  `gendustry` <-- `BinnieCore`
  `gendustry` <-- `ExtraBees`
  `gendustry` <-- `ExtraTrees`
  `gendustry` <-- `MineFactoryReloaded`
  `gendustry` <-- `MagicBees`
  `gendustry` <-- `bdlib`

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

  class `harvestcraft`["Pam's HarvestCraft"] {
    id: harvestcraft
    version: 1.7.10i
    authors: Pamela Collins
  }

  class `hodgepodge`["Hodgepodge"] {
    id: hodgepodge
    version: 2.2.13
    authors: mitchej123, GTNewHorizons Team
  }
  `hodgepodge` <-- `gtnhmixins`

  class `inventorytweaks`["Inventory Tweaks"] {
    id: inventorytweaks
    version: 1.5.16
    authors: 
  }

  class `ironfurnaces`["Iron Furnaces"] {
    id: ironfurnaces
    version: 1.2.4
    authors: XenoMustache
  }

  class `irontank`["Iron Tanks"] {
    id: irontank
    version: 1.2.6
    authors: Indemnity83
  }
  `irontank` <-- `BuildCraft|Factory`

  class `ivtoolkit`["IvToolkit"] {
    id: ivtoolkit
    version: 1.2.1
    authors: Ivorius
  }

  class `jecalculation`["Just Enough Calculation"] {
    id: jecalculation
    version: 3.8.5
    authors: Towdium, Discreater
  }
  `jecalculation` <-- `NotEnoughItems`

  class `journeymap`["JourneyMap"] {
    id: journeymap
    version: 1.7.10-5.1.4p6
    authors: techbrew, mysticdrew
  }

  class `letsencryptcraft`["Let's Encrypt Craft"] {
    id: letsencryptcraft
    version: @VERSION@
    authors: 
  }

  class `littletiles`["LittleTiles"] {
    id: littletiles
    version: 1.2.7-GTNH
    authors: 
  }

  class `login_shield`["Login Shield"] {
    id: login_shield
    version: 1.7.10-2-gf6e21a7
    authors: Glasspelican
  }

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
    version: v2.0
    authors: juanmuscaria
  }

  class `modtweaker2`["Mod Tweaker 2"] {
    id: modtweaker2
    version: 0.9.10
    authors: Jaredlll08
  }
  `modtweaker2` <-- `MineTweaker3`
  `modtweaker2` <-- `Forestry`

  class `neenergistics`["NotEnoughEnergistics"] {
    id: neenergistics
    version: 1.4.0
    authors: vfyjxf
  }
  `neenergistics` <-- `NotEnoughItems`
  `neenergistics` <-- `appliedenergistics2`
  `neenergistics` <-- `ae2wct`
  `neenergistics` <-- `ae2fc`

  class `neiintegration`["NEIIntegration"] {
    id: neiintegration
    version: 1.3.1
    authors: tonius11
  }
  `neiintegration` <-- `NotEnoughItems`

  class `netherportalfix`["Nether Portal Fix"] {
    id: netherportalfix
    version: 1.1.2
    authors: BlayTheNinth
  }

  class `oretweaker`["Ore Tweaker"] {
    id: oretweaker
    version: 1.0.2-1.7.10
    authors: EwyBoy
  }

  class `overloadedarmorbar`["Overloaded Armor Bar"] {
    id: overloadedarmorbar
    version: 1.0.1
    authors: Tfarcenim
  }

  class `reccomplex`["Recurrent Complex"] {
    id: reccomplex
    version: 0.9.7.1.1
    authors: Ivorius
  }
  `reccomplex` <-- `ivtoolkit`

  class `rfdrills`["RFDrills"] {
    id: rfdrills
    version: 1.7.3
    authors: goldenapple
  }
  `rfdrills` <-- `CoFHCore`
  `rfdrills` <-- `ThermalExpansion`
  `rfdrills` <-- `EnderIO`

  class `smoothfont`["Smooth Font"] {
    id: smoothfont
    version: 1.7.10-1.15.3
    authors: bre2el
  }

  class `smoothfontcore`["Smooth Font Core"] {
    id: smoothfontcore
    version: 1.7.10-1.15.1
    authors: bre2el
  }

  class `soundfilters`["Sound Filters"] {
    id: soundfilters
    version: 0.7_for_1.7.X
    authors: Tmtravlr
  }

  class `spongemixins`["UniMixins: SpongeMixins"] {
    id: spongemixins
    version: 2.0.1+gtnh.uni.0.1.7.1
    authors: Time_Conqueror, mitchej123
  }

  class `tc4tweak`["TC4 Tweak"] {
    id: tc4tweak
    version: 1.5.7
    authors: glee8e
  }
  `tc4tweak` <-- `Thaumcraft`

  class `tcinventoryscan`["TC Inventory Scanning"] {
    id: tcinventoryscan
    version: 1.0.12-GTNH
    authors: BlayTheNinth
  }
  `tcinventoryscan` <-- `Thaumcraft`

  class `tcneiadditions`["Thaumcraft NEI Additions"] {
    id: tcneiadditions
    version: 1.2.2
    authors: Time_Conqueror
  }
  `tcneiadditions` <-- `Thaumcraft`
  `tcneiadditions` <-- `thaumcraftneiplugin`
  `tcneiadditions` <-- `spongemixins`

  class `tcnodetracker`["TC Node Tracker"] {
    id: tcnodetracker
    version: 1.1.7
    authors: Dyonovan
  }
  `tcnodetracker` <-- `Thaumcraft`

  class `thaumcraftneiplugin`["Thaumcraft NEI Plugin"] {
    id: thaumcraftneiplugin
    version: 1.7.10-1.7a
    authors: DjGiannuzz
  }
  `thaumcraftneiplugin` <-- `Thaumcraft`

  class `thaumicenergistics`["Thaumic Energistics"] {
    id: thaumicenergistics
    version: 1.4.4-GTNH
    authors: Nividica
  }
  `thaumicenergistics` <-- `ThE-core`
  `thaumicenergistics` <-- `appliedenergistics2`
  `thaumicenergistics` <-- `Thaumcraft`
  `thaumicenergistics` <-- `Waila`

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

  class `universalsingularities`["UniversalSingularities"] {
    id: universalsingularities
    version: 8.6.7
    authors: Wealthyturtle, WanionCane
  }
  `universalsingularities` <-- `Avaritia`

  class `wailaplugins`["WAILA Plugins"] {
    id: wailaplugins
    version: 0.2.8
    authors: tterrag
  }
  `wailaplugins` <-- `endercore`
  `wailaplugins` <-- `Waila`

  class `wanionlib`["WanionLib"] {
    id: wanionlib
    version: 1.8.4
    authors: WanionCane
  }

  class `wawla`["What Are We Looking At"] {
    id: wawla
    version: 1.1.3-GTNH
    authors: 
  }
  `wawla` <-- `Waila`

```
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

  class `Baubles`["Baubles"] {
    id: Baubles
    version: 1.0.1.16
    authors: Azanor
  }

  class `BrandonsCore`["Brandon's Core"] {
    id: BrandonsCore
    version: 1.0.0.13-GTNH
    authors: brandon3055
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
  `DraconicEvolution` <-- `BrandonsCore`

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

  class `NotEnoughItems`["NotEnoughItems"] {
    id: NotEnoughItems
    version: 2.3.53-GTNH
    authors: ChickenBones, mitchej123
  }
  `NotEnoughItems` <-- `CodeChickenCore`

  class `Thaumcraft`["Thaumcraft"] {
    id: Thaumcraft
    version: 4.2.3.5
    authors: 
  }
  `Thaumcraft` <-- `Baubles`

  class `ae2fc`["AE2 Fluid Crafting"] {
    id: ae2fc
    version: 1.1.20-gtnh
    authors: GlodBlock
  }
  `ae2fc` <-- `appliedenergistics2`

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

  class `wanionlib`["WanionLib"] {
    id: wanionlib
    version: 1.8.4
    authors: WanionCane
  }

```
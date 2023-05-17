```mermaid
classDiagram
  class `<CoFH ASM>`["CoFH ASM"] {
    id: <CoFH ASM>
    version: 000
    authors: 
  }

  class `Avaritia`["Avaritia"] {
    id: Avaritia
    version: 1.41
    authors: SpitefulFox, TTFTCUTS
  }

  class `Baubles`["Baubles"] {
    id: Baubles
    version: 1.0.1.16
    authors: Azanor
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

  class `NotEnoughItems`["NotEnoughItems"] {
    id: NotEnoughItems
    version: 2.3.53-GTNH
    authors: ChickenBones, mitchej123
  }
  `NotEnoughItems` <-- `CodeChickenCore`

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
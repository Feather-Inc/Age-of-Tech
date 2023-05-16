# Age-of-Tech
Arquivos de configuração do Age of Tech

# Mods
```mermaid
classDiagram
    class CodeChickenCore["CodeChicken Core"] {
        version: 1.1.11
        [LIB/COREMOD]
    }

    class wanionlib["WanionLib"] {
        version: 1.8.4
        [LIB/COREMOD]
    }


    class appliedenergistics2["Applied Energistics 2"] {
        version: rv3-beta-212-GTNH-1-ga99d8df.dirty
    }

    class Avaritia {
        version: 1.41
    }

    class avaritiaddons["Avaritiaddons"] {
        version: 1.5.5-GTNH
    }
    avaritiaddons <-- Avaritia
    avaritiaddons <-- wanionlib

    class NotEnoughItems["NotEnoughItems"] {
        version: 2.3.53-GTNH
    }
    NotEnoughItems <-- CodeChickenCore

    class neenergistics["NotEnoughEnergistics"] {
        version: 1.4.0
    }
    neenergistics <-- NotEnoughItems
    neenergistics <-- appliedenergistics2
```

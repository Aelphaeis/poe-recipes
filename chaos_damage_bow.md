```mermaid
flowchart TD
    A([ilvl 82 Bow]) --> B[Perfect Fossil]
    B --> C{Good base quality?}
    C --> |Yes| D[Metallic + Corroded Fossil]
    C --> |No| B
    D --> E{+2 to Level of Socketed Bow Gems<br/> +1 to Level of Socketed Gems}
    E --> |No| D
    E --> |Yes| F{Has Open Prefix?}
    F --> |No| D
    F --> |Yes| G{Has Two suffix?}
    G --> |No| H{Has Three Suffix?}
    H --> I[Orb of Annulment]
    I --> E
    G --> |Yes| J[Craft Cannot Roll Attack Modifiers]
    J --> K[Hunter's Exalted Orb]
    K --> L[Craft Prefixes Cannot be modified]
    L --> M[Veiled Exalted Orb]
    M --> N{+#% to Chaos Damage over Time Multiplier?}
    N --> |No| O[Craft Prefixes Cannot be modified]
    O --> P[Orb of Annulment]
    P --> Q{+#% to Chaos Damage over Time Multiplier?}
    Q --> |Yes| O
    Q --> |No| M
    N --> |Yes| R[Add aspect of the Spider]
    R --> T["Craft <br/> 10% chance to Trigger Level 1 Blood Rage when you Kill an Enemy<br/> 10% increased Attack Speed (crafted)"]
    T --> U(["+2 to Level of Socketed Bow Gems <br/> +1 to Level of Socketed Gems <br/> #% increased Chaos Damage over Time <br/> +#% to Chaos Damage over Time Multiplier <br/> Grants Level 20 Aspect of the Spider Skill <br/> 10% chance to Trigger Level 1 Blood Rage when you Kill an Enemy (crafted) <br/> #% increased Attack Speed (crafted)"]) 
```

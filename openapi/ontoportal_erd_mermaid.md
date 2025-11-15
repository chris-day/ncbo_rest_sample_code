
```mermaid
flowchart TD

    O[Ontology] -->|1..N| C[Class]
    C -->|0..N| Cat[Category]

    O:::box
    C:::box
    Cat:::box

    classDef box fill:#f7f7f7,stroke:#333,stroke-width:1px;
```

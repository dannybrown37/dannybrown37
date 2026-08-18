# Danny Brown

Software engineer. Billions of messages from thousands of vehicles, across two companies since 2021.

**[dannybrown.dev](https://dannybrown.dev)** — writing, projects, and the digital garden.

```mermaid
flowchart LR
    you([you, right now]) --> profile[["github.com/dannybrown37"]]

    profile --> site(("dannybrown.dev"))

    site --> writing[/"writing"/]
    site --> garden[("digital garden")]
    site --> projects{{"projects"}}

    writing --> post1["agent skills turn notes into ethos"]
    garden --> ccgarden["ccgarden"]
    projects --> ccgarden

    ccgarden -.->|"notes on Claude Code"| you

    classDef default fill:#1a1a1a,stroke:#888,color:#eee;
    classDef site fill:#2b6cb0,stroke:#63b3ed,color:#fff,font-weight:bold;
    class site site
```

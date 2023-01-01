## Flowchart

<br>

```mermaid
flowchart
    subgraph My App
    Home(((home)))-->Review(review)
    style Home fill:navy
    Home --> Edit(edit)
    Home -->Help
    style Edit fill: darkgreen
    style Help fill: red
    style Review fill: purple
    Edit --> Submit[(Database)]
    style Submit fill:darkred
    Submit --> Review
    end
```

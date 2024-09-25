```mermaid
flowchart TD
id1[(Water Storage)] 
id2[(Water Storage)] --> id1[(Water Storage)]
id2[(Water Storage)]
id2[(Water Storage)] --> A[Water Plant]
A[Water Plant] --> B[Water Mains] --> C[Water Meters] --> D[Customers] -->F{Wastewater Pipes}
B[Water Mains] --> G{Blow Off Valves}
B[Water Mains] --> E{Fire Hydrants}
F{Wastewater Pipes} --> H{Waste Water Treatment Plant}
G{Blow Off Valves} --> I(Environment)
E{Fire Hydrants} --> I(Environment)
H{Waste Water Treatment Plant} --> I(Environment)

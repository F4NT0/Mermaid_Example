# Como construir Flowcharts

#### Orientação dos dados

* Podemos colocar das seguintes formas:

* TB - top to bottom
* TD - top-down/ same as top to bottom
* BT - bottom to top
* RL - right to left
* LR - left to right

**TOP TO BOTTOM**

```md
flowchart TB
    Start --> Stop
```

```mermaid
flowchart TB
    Start --> Stop
```

**TOP DOWN**

```md
flowchart TD
    Stop --> Start
```

```mermaid
flowchart TD
    Start --> Stop
```

**BOTTOM TOP**

```md
flowchart BT
    Start --> Stop
```

```mermaid
flowchart BT
    Start --> Stop
```

**RIGHT TO LEFT**

```md
flowchart RL
    Start --> Stop
```

```mermaid
flowchart RL
    Start --> Stop
```

**Left to Right**

```md
flowchart LR
    Start --> Stop
```

```mermaid
flowchart LR
    Start --> Stop
```

```mermaid
gantt
dateFormat  YYYY-MM-DD
title Adding GANTT diagram to mermaid
excludes weekdays 2014-01-10

section A section
Completed task            :done,    des1, 2014-01-06,2014-01-08
Active task               :active,  des2, 2014-01-09, 3d
Future task               :         des3, after des2, 5d
Future task2               :         des4, after des3, 5d

```

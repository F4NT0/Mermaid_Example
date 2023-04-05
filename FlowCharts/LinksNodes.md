# Links entre Nodos

* Nodos são blocos de informações que podem ser conectados

### **Como fazer Nodos**

```md
---
title: Nodo
---
flowchart
    id
```

```mermaid
---
title: Nodo
---
flowchart
    id
```

### **Conexão de Flecha**

```md
flowchart LR
    A-->B
```

```mermaid
flowchart LR
    A-->B
```

### **Conexão Aberta**

```md
flowchart LR
    A --- B
```

```mermaid
flowchart LR
    A --- B
```

### **Conexão entre pontos**

```md
flowchart LR
   A-.->B;
```

```mermaid
flowchart LR
   A-.->B;
```

### **Conexão Forte**

```md
flowchart LR
   A ==> B
```

```mermaid
flowchart LR
   A ==> B
```

### **Conexão Invisivel**

* Serve somente para poder organizar os nodos

```md
flowchart LR
    A ~~~ B
```

```mermaid
flowchart LR
    A ~~~ B
```

### **Novos tipos de Flechas**

```md
---
Conexão de Ponto
---
flowchart LR
    A --o B
```

```mermaid
---
Conexão de Ponto
---
flowchart LR
    A --o B
```

---

```md
---
Conexão de Xis
---
flowchart LR
    A --x B
```

```mermaid
---
Conexão de Xis
---
flowchart LR
    A --x B
```

---

```md
---
Conexão de Flechas Duplas
---
flowchart LR
    A <--> B
```

```mermaid
---
Conexão de Flechas Duplas
---
flowchart LR
    A <--> B
```

### **Texto dentro da conexão**

```md
---
Conexão Aberta
---

flowchart LR
    A---|text|B
```

```mermaid
---
Conexão Aberta
---

flowchart LR
    A---|text|B
```

```md
---
Conexão Flecha
---

flowchart LR
    A-->|text|B
```

```mermaid
---
Conexão Flecha
---

flowchart LR
    A-->|text|B
```

```md
---
Conexão Pontos
---

flowchart LR
   A-. text .-> B
```

```mermaid
---
Conexão Pontos
---

flowchart LR
   A-. text .-> B
```

```md
---
Conexão Forte
---

flowchart LR
   A == text ==> B
```

```mermaid
---
Conexão Forte
---

flowchart LR
   A == text ==> B
```

### **Conexão de Links**

* Agora podemos conectar como quisermos

##### **Nodo para Nodo constante**

```md
---
A vai para B e B vai para C
---
flowchart LR
   A -- text --> B -- text2 --> C
```

```mermaid
---
A vai para B e B vai para C
---
flowchart LR
   A -- text --> B -- text2 --> C
```

```md
---
A vai para B e B vai para C
---
flowchart LR
   A ---|text|B ---|text2|C
```

```mermaid
---
A vai para B e B vai para C
---
flowchart LR
   A ---|text|B ---|text2|C
```

```md
---
A vai para B e B vai para C
---
flowchart LR
   A -. text .-> B -. text2 .-> C
```

```mermaid
---
A vai para B e B vai para C
---
flowchart LR
   A -. text .-> B -. text2 .-> C
```

```md
---
A vai para B e B vai para C
---
flowchart LR
   A == text ==> B == text2 ==> C
```

```mermaid
---
A vai para B e B vai para C
---
flowchart LR
   A == text ==> B == text2 ==> C
```

#### **Multiplos Nodos na mesma linha**

* Podemos colocar conexões tudo na mesma linha de multiplos nodos

```md
---
A vai para B e B vai para D
B vai para C e C vai para D
---
flowchart LR
   a --> b & c --> d
```

```mermaid
---
A vai para B e B vai para D
B vai para C e C vai para D
---
flowchart LR
   a --> b & c --> d
```

---

```md
---
Podemos colocar dois nodos juntos se conectando com outros dois nodos
---
flowchart TB
    A & B --> C & D
```

```mermaid
---
Podemos colocar dois nodos juntos se conectando com outros dois nodos
---
flowchart TB
    A & B --> C & D
```

#### **Multiplos Nodos em Linhas Diferentes**

* O padrão é ser em diferentes linhas, como abaixo

```md
---
Nodos conectados
---
flowchart TB
    A --> C
    A --> D
    B --> C
    B --> D
```

```mermaid
---
Nodos conectados
---
flowchart TB
    A --> C
    A --> D
    B --> C
    B --> D
```

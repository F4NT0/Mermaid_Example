# Constuindo Exemplos de Flowcharts em Mermaid

### Exemplo Simples de Decisão

```md
flowchart TD
    A[Definir nome] --> B{Nome bem definido?}
    B -->|Sim| C([Fim])
    B -->|Não| D[Repensar Nome]
    D --> B
```

```mermaid
flowchart TD
    A[Definir nome] --> B{Nome bem definido?}
    B -->|Sim| C([Fim])
    B -->|Não| D[Repensar Nome]
    D --> B
```

### Adicionando Characteres especiais

```md
flowchart
    A["#128219; Perigo"] --> B["#9989; Tudo OK"]
```

```mermaid
flowchart
    A["#128219; Perigo"] --> B["#9989; Tudo OK"]
```

### 

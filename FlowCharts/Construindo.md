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

* Podemos utilizar characteres em HTML como na lista abaixo

Nome|Código|Exemplo
|---|---|---|
Rosto Feliz|`#128512;`|<p>&#128512;</p>
Estrela|`#11088;`|<p>&#11088;</p>
Rosto Raivoso|`#128544;`|<p>&#128544;</p>
Coração|`#10084;`|<p>&#10084;</p>
Tempo|`#9203;`|<p>&#9203;</p>
Urgente|`#9940;`|<p>&#9940;</p>
OK|`#9989;`|<p>&#9989;</p>
Falta Documentar|`#9997;`|<p>&#9997;</p>
Falha|`#10060;`|<p>&#10060;</p>
Pedido de Socorro|`#127384;`|<p>&#127384;</p>
Enviado para Prod|`#127385;`|<p>&#127385;</p>
Achamos um Bug|`#128030;`|<p>&#128030;</p>
Coração Brilhante|`#128150;`|<p>&#128150;</p>
Pasta|`#128193;`|<p>&#128193;</p>
Arquivo|`#128196;`|<p>&#128196;</p>
PERIGO IMINENTE|`#128219;`|<p>&#128219;</p>
Reenvio|`#128259;`|<p>&#128259;</p>
Bandeira Vermelha|`#128681;`|<p>&#128681;</p>


```mermaid
flowchart
    A["#128512;"]
    B["#11088;"]
```

## Projeto Sorting Station

Professor da disciplina:
* João Martins                - Professor Adjunto              - joao@ic.ufal.br

Participantes:
* João Muniz Neto             - Engenharia de Computação       - jsmn@ic.ufal.br
* Wilamis Aviz                - Engenharia de Computação       - wmaa@ic.ufal.br

### Descrição

Neste trabalho é implementada uma aplicação em Ladder, simulada no TIA Portal V15 da Siemens para uma estação de triagem modelada pela Factory IO, a fim de separar materiais de diferentes formatos para suas respectivas rampas.

A imagem abaixo é do cenário utilizado no Factory IO. <br><br>
![image](https://user-images.githubusercontent.com/58791888/206717184-bfe457b6-a11c-4bee-8889-46f41af60952.png)
<br>

Materiais utilizados:<br><br>
![image](https://user-images.githubusercontent.com/58791888/206719944-158cb821-80d5-492a-9683-21ebc70ed26d.png)
<br>

São considerados três tipos de materiais: Blue Raw Material, Blue product Lid e Blue product Base. Esses materiais são identificados por um sensor de visão. Em seguida conduzidos pelas esteiras até a sua respectiva rampa. <br><br>
![image](https://user-images.githubusercontent.com/58791888/206718776-1708260c-17b7-4bac-a817-3420650cbe2c.png)


## Tabela de endereçamento
| Artefato              | Tipo           |      Endereço         |
|-----------------------|----------------|-----------------------|
|   At exit             | Bool           | %I0.0                 | 
|   Start               | Bool           | %I0.1                 | 
|   Reset               | Bool           | %I0.2                 | 
|   Stop                | Bool           | %I0.3                 | 
|   Emergency stop      | Bool           | %I0.4                 | 
|   Auto                | Bool           | %I0.5                 | 
|   CTORY I/O           | Bool           | %I0.6                 |
|   Vision sensor       | Dint           | %ID30                 |
|   Entry conveyor      | Bool           | %Q0.0                 |
|   Stop blade          | Bool           | %Q0.1                 |
|   Exit conveyor       | Bool           | %Q0.2                 |
|   Sorter 1 turn       | Bool           | %Q0.3                 |
|   Sorter 1 belt       | Bool           | %Q0.4                 |
|   Sorter 2 turn       | Bool           | %Q0.5                 |
|   Sorter 2 belt       | Bool           | %Q0.6                 |
|   Sorter 3 turn       | Bool           | %Q0.7                 |
|   Sorter 3 belt       | Bool           | %Q1.0                 |
|   Start light         | Bool           | %Q1.1                 |
|   Reset light         | Bool           | %Q1.2                 |
|   Stop light          | Bool           | %Q1.3                 |
|   Counter 1           | Dint           | %QD30                 |
|   Counter 2           | Dint           | %QD34                 |
|   Counter 3           | Dint           | %QD38                 |

## Resultado
![image](https://user-images.githubusercontent.com/58791888/206719126-904bb000-cb04-440c-ac7d-b7c1c558c348.png)
![image](https://user-images.githubusercontent.com/58791888/206719098-79634a0f-385a-4f38-aace-de00977e6026.png)
![image](https://user-images.githubusercontent.com/58791888/206719139-cfb6ccf7-47ed-41a4-9ba5-37cdb7c4612a.png)

# Rede Neural Mega-Sena

#### Acurácia: ~75%

#### Arquitetura:

<img width="900" height="626" alt="image" src="https://github.com/user-attachments/assets/1c7cedab-26d5-4860-9414-f88b72dc165c" />

| Camada | Tipo  | Neurônios | Ativação | Entrada | Saída | Parâmetros     |
| ------ | ----- | --------- | -------- | ------- | ----- | -------------- |
| 1      | Dense | 10        | ReLU     | (6,)    | (10,) | 70             |
| 2      | Dense | 12        | ReLU     | (10,)   | (12,) | 132            |
| 3      | Dense | 1         | Sigmoid  | (12,)   | (1,)  | 13             |
|        |       |           |          |         |       | **Total:** 215 |

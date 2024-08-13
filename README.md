# Sem17- aula03

## **Roteiro de Atividade Prática**

Atividade 1: Sistema de agendamento de reuniões

🎯 **Objetivo:** Criar um programa que, dado o número de participantes e o tipo de reunião (normal ou executiva), recomende o tamanho de sala mais adequado.

🛠️ **Detalhes do Exercício:**

Na empresa que você trabalha, identificou que uma das principais dificuldades das pessoas é agendar a sala certa para a realização das reuniões de acordo com o número de pessoas presentes. Dessa forma, você está desenvolvendo um sistema de agendamento de reuniões para uma empresa. O sistema deve ajudar a definir a sala de reunião adequada com base no número de participantes e no tipo de reunião. A empresa tem três tipos de salas:

1.	Sala Pequena: ideal para reuniões com até 5 pessoas.
2.	Sala Média: adequada para reuniões de 6 a 15 pessoas.
3.	Sala Grande: para reuniões com mais de 15 pessoas ou reuniões executivas.

Entrada:
* Número de participantes (inteiro);
* Tipo de reunião (string): "normal" ou "executiva".
Saída:
* Recomendação da sala (string): "Sala Pequena", "Sala Média" ou "Sala Grande".


✔️ **Estrutura da Atividade**
- [ ]	Definir uma função:
Desenvolva uma função chamada recomendar_sala que aceite o número de participantes e o tipo de reunião como parâmetros e retorne a sala recomendada.
- [ ]	Lógica de decisão:
Utilize estruturas de decisão compostas dentro da função para determinar a sala adequada.
- [ ]	Validação de entradas:
O sistema deve garantir que as entradas sejam válidas (ex.: número de participantes não pode ser negativo).
- [ ]	Interface do usuário:
Peça ao usuário para inserir o número de participantes e o tipo de reunião, e exiba a recomendação da sala.

:mouse::mouse::mouse:

> [!TIP]
> Exemplo-base para resolução:
```
if tipo_reuniao == "executiva":
    # Decida qual sala é apropriada para reuniões executivas
elif participantes <= 5:
    # Decida a sala para pequenas reuniões normais
elif participantes <= 15:
    # Decida a sala para reuniões normais de tamanho médio
else:
    # Decida a sala para grandes reuniões normais
```
Tempo estimado: 30 minutos.

🚀


Aplicação simples para compleção de desafio proposto no Bootcamp Santander/DIO 2024 - Backend com Java

**Propósito:** 

Pôr em prática a criação e tratamento de exceções customizadas.

**Fluxo:**
1. Receber dois parâmetros de número inteiro do usuário
2. **Verificar se:** parametroUm é maior que parametroDois

    **Se sim:** Lançar a exceção customizada "ParametrosInvalidosException" e tratar com try/catch para imprimir uma mensagem de aviso ao usuário

    **Se não:** Definir nova variável chamada **contagem** com o valor de parametroDois subtraído pelo valor de parametroUm
3. Definir um for loop para imprimir uma mensagem enquanto a variável **contagem** for maior que zero
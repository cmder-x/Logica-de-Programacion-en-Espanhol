# Aula 5 - O que são algorítimos e como montar algorítimos do zero

1. O que são algorítimos?
"Um algoritmo é simplesmente uma série de instruções a serem seguidas, para resolver um problema."

1. Quando os algorítimos devem ser criados?
Sempre que queremos montar uma sequência de passos necessários para solucionar um problema.

1. Quál é a estratégia para montar um algorítmo?
  Independente se:
    1. Quando alguém te apresenta um problema a ser resolvido.
    1. Quando você encontra um problema a ser resolvido.
___

## Método 5Q's para montar um algorítimo:
Analise criticamente o problema e descubra:
(Tente explicar este problema para você mesmo em voz alta e peça mais informações/investigue mais até você compreender completamente o problema.)

1. **Quais são os dados de entrada necessários?**
1. **O que devo fazer com estes dados?**
1. **Quais são as restrições deste problema?**
1. **Qual é o resultado esperado?**
1. **Qual é a sequência de passos a ser feitas para chegar ao resultado esperado?**

___

## Vamos aplicar esse método!
Vamos resolver três problemas para poder praticar o nosso método:
  1. [Ligar para alguém](#problema-1---ligar-para-alguém)
  1. [Valor por hora](#problema-2---valor-por-hora)
  1. [Chute o número](#problema-3---chute-o-número)

### Problema 1 - Ligar para alguém
Monte um **algorítimo** necessário para ligar para um amigo.
1. Quais são os dados de entrada necessários?
    * Um telefone.
    * Um número de celular.
1. O que devo fazer com estes dados?
    * Devo usar o celular para discar o número do meu amigo.
1. Quais são as restrições deste problema?
    * Caso meu amigo não atenda, devo deixar uma mensagem dizendo: "me ligue de volta".
1. Qual é o resultado esperado?
    * Conseguir falar com meu amigo.
1. Qual é a sequência de passos a ser feitas para chegar ao resultado esperado?
    1. Pegar o telefone.
    1. Se estiver travado por senha, destrave o celular.
    1. Verifique se há sinal do operadora.
    1. Navegue até o discador do celular.
    1. Digite o número do seu amigo.
    1. Aperte o botão de "ligar".
    1. Aguarde a ligação completar.
    1. Se a ligação completar, conversar com ele.
    1. Se a ligação não completar, deixar uma mensagem dizendo "me ligue de volta".

### Problema 2 - Valor por hora
Escreva um programa que retorna o valor hora de um funcionário com base no seu salário mensal e horas trabalhadas por mes.
1. Quais são os dados de entrada necessários?
    * O salario mensal.
    * As horas trabalhadas por mes.
1. O qué devo fazer com estes dados?
    * Devo usar eles para calcular o valor hora que um funcionário recebe usando o cálculo **salario mensal / horas trabalhadas**.
1. Quais são as restrições deste problema?
    * Os valores devem ser entregues somente em formato de salário por hora.
1. Qual é o resultado esperado?
    * O valor hora que um funcionário recebe.
1. Qual é a sequência de passos a ser feitas para chegar ao resultado esperado?
    1. Pedir os dados necessários:
        * Perguntar quanto a pessoa ganha por mes.
        * Guardar essa informação.
        * Perguntar quantas horas ela trabalha por mes.
        * Guardar essa informação.
    1. Calcuar o valor hora da pessoa (salário mensal / horas trabalhadas).
    1. Exibir o valor hora daquela pessoa.

### Problema 3 - Chute o número
Escreva um programa que, ao iniciar gera um valor aleatório de 1 a 10 e permite que o usuário chute um número até que o valor aleatório gerado no início do programa seja chutado corretamente.

O programa deve informar se o chute foi acima, abaixo ou igual ao valor aleatório gerado no início do programa.
1. Quais são os dados de entrada necessários?
    * O valor aleatório de 1 a 10.
    * Um chute do usuário.
1. O que devo fazer com estes dados?
    1. Devo pegar o valor aleátorio de 1 a 10 que foi gerado e comparar com o valor que foi chutado pelo usuário.
    1. Se o chute foi maior ou menor que valor gerado, alertar o usuário sobre isso e o deixar jogar novamente até que acerte o número que foi gerado.
1. Quais são as restrições deste problema?
    * O programa não deve ser finalizado até que um valor seja chutado corretamente.
    * O usuário deve ser capaz de jogar quantas vezes quiser.
1. Qual é o resultado esperado?
    * O programa identificar que o valor chutado pelo usuário é igual ao valor gerado no início do programa.
1. Qual é a sequência de passos a ser feitas para chegar ao resultado esprado?
    1. Gerar um valor aleatório de 1 a 10.
    1. Armazenar este valor.
    1. Receber o chute do usuário.
    1. Comparar o chute do usuário com o valor aleatório gerado.
    1. Se o chute for maior que o valor gerado, exibir "chutou alto" e voltar ao passo 3.
    1. Se o chute for menor que o valor gerado, exibir "chutou baixo" e voltar ao passo 3.
    1. Se o chute for igual que o valor gerado, exibir "acertou!" e perguntar ao usuário se queser jogar de volta.
    1. Se o jugador aceita voltar jogar, voltar ao passo 1.

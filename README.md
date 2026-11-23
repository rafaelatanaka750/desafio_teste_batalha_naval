**Rafaela Tanaka Cardoso 24062611-2**

**Vitor Hugo da Costa 23234248-2**

# Batalha Naval - Casos de Teste

## Concepção do Desafio

O desafio consiste na criação de casos de teste para o jogo Batalha Naval, utilizando JavaScript e o framework Jest.

A ideia é testar as principais regras do jogo, considerando um tabuleiro de 10x10 e quatro tipos de navios:

- Porta-aviões: ocupa 5 casas.
- Encouraçado: ocupa 4 casas.
- Submarino: ocupa 3 casas.
- Destroier: ocupa 2 casas.

Os testes foram pensados para verificar se os navios podem ser posicionados corretamente, se os ataques funcionam como esperado e se as regras do jogo são respeitadas. Também foram considerados alguns erros que podem acontecer durante uma partida, como posicionar navios fora do tabuleiro ou tentar atacar uma posição que já foi atacada.

## Funcionamento dos Casos de Teste

Os casos de teste foram separados por funcionalidades para facilitar a organização e a identificação do que está sendo verificado.

Primeiro, são testados o tamanho do tabuleiro e o posicionamento dos navios, verificando se cada um ocupa a quantidade correta de casas e se não ultrapassa os limites ou fica sobreposto a outro navio.

Depois, são realizados testes relacionados aos ataques, verificando situações em que o jogador acerta um navio, atinge uma casa vazia ou tenta atacar uma posição inválida ou já utilizada.

Também são testadas as regras do jogo, como a identificação de navios afundados e a condição para finalizar a partida, que acontece quando todos os navios adversários são afundados.

Por fim, os testes automatizados com Jest servem para verificar cada uma dessas situações, comparando o resultado esperado com o resultado apresentado pelo sistema. Assim, é possível identificar se alguma regra não está funcionando corretamente.

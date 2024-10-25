

## Membros do Projeto
- Victor Monte (@victormonte)
- Vinicius L. Pazos (@Viniciusgithu)


## Disciplina
Programação Imperativa e Funcional - 2024.2

## Instituição de Ensino
Centro de Estudos e Sistemas Avançados do Recife - CESAR School

## Nome do Jogo
**Battle of the Waters**

## Instruções para Compilar e Executar o Jogo

1. **Pré-requisitos:**
   - Certifique-se de ter o [GCC](https://gcc.gnu.org/) instalado no seu sistema.
   - Para sistemas Windows, você pode usar o [MinGW](http://www.mingw.org/).

2. **Clone o Repositório:**
   ```bash
   git clone https://github.com/Viniciusgithu/battle_of_the_waters
   cd Battle of the Waters

## Descrição do Jogo

**Battle of The Waters** é um emocionante jogo de estratégia onde dois jogadores competem para afundar o navio inimigo. O jogo combina lógica e tática para proporcionar uma experiência desafiadora e divertida.

### Regras do Jogo

1. **Configuração Inicial:**
   - Cada jogador possui um tabuleiro de 10x10.


2. **Turnos:**
   - Os jogadores se alternam em turnos, começando pelo jogador que foi escolhido aleatoriamente.
   - Durante o seu turno, um jogador deve escolher uma coordenada LinhaxColuna (ex: 00 01 02) para atacar.

3. **Resultados dos Ataques:**
   - Se a coordenada escolhida atingir um navio do oponente, será considerado um "acerto" e o jogador deve soma ponto.
   - Se não houver navio na coordenada, será um "erro"
   - O tabuleiro do oponente deve ser atualizado para refletir os acertos e erros.

4. **Final do Jogo:**
   - O jogo termina quando um dos jogadores afunda todos os navios do adversário.
   - O jogador que afundar todos os navios do oponente primeiro é declarado o vencedor.

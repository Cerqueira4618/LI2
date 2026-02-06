# Projeto LI2 - Jogo de Tabuleiro

Projeto em C para a disciplina de Laboratórios de Informática II (LI2). O jogo consiste em manipular o estado de um tabuleiro através de comandos, seguindo regras definidas no enunciado.

## Conteúdos

- [Requisitos](#requisitos)
- [Compilar](#compilar)
- [Executar](#executar)
- [Testes](#testes)
- [Estrutura do projeto](#estrutura-do-projeto)

## Requisitos

- GCC
- Make

## Compilar

```bash
make
```

Gera o executável `jogo`.

## Executar

```bash
./jogo
```

Se existir um ficheiro de entrada, pode executar com:

```bash
./jogo < jogo.txt
```

## Exemplo de execucao

```text
Jogo carregado com sucesso.

Jogo salvo com sucesso no arquivo 'res.txt'.

e c a d c
d c d e c
b d d c e
c d e e b
a c c b b

Digite um comando:
- s para sair
- g para guardar o jogo
- l para carregar o jogo
- r <coordenada> para riscar uma posicao
- b <coordenada> para colocar em maiusculas uma posicao
- d para desfazer o ultimo comando
- a para ajudar mudando o estado de todas as casas que se conseguem inferir atraves do estado atual do tabuleiro
- A invocar o comando a enquanto o jogo sofrer alteracoes
- v para verificar as restricoes
- R para resolver o jogo automaticamente

Jogo carregado com sucesso do arquivo 'res.txt'.

Matriz resolvida carregada do ficheiro 'res.txt':
E # A D C
D C # E #
B # D C E
C D E # B
A # C B #

Digite um comando:
- s para sair
- g para guardar o jogo
- l para carregar o jogo
- r <coordenada> para riscar uma posicao
- b <coordenada> para colocar em maiusculas uma posicao
- d para desfazer o ultimo comando
- a para ajudar mudando o estado de todas as casas que se conseguem inferir atraves do estado atual do tabuleiro
- A invocar o comando a enquanto o jogo sofrer alteracoes
- v para verificar as restricoes
- R para resolver o jogo automaticamente
```

## Testes

```bash
make testes
./testes
```

## Estrutura do projeto

- `main.c` - ponto de entrada do programa.
- `funcoes.c` - logica principal do jogo.
- `testes.c` - testes automatizados.
- `jogo.txt` - exemplo de input.
- `res.txt` - exemplo de output.
- `Makefile` - comandos de compilacao.

## Licenca

Sem licença especificada.

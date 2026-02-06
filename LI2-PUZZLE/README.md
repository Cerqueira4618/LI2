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

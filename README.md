# 🎮 Terminal Adventure

Jogo de aventura em texto feito em Python, jogado direto no terminal.

Você é um aventureiro perdido nas **Terras de Podridão**. Derrote monstros, evolua seu personagem e conquiste todos os cenários para sair vivo desse lugar amaldiçoado.

## Funcionalidades

- Batalhas por turnos com inimigos únicos
- Ações de combate: atacar, bloquear, curar ou fugir
- Sistema de XP e níveis, com evolução de HP e dano
- Inimigos que ficam mais fortes conforme você avança
- Quatro cenários (floresta, ruínas, caverna e torre), com duas salas de batalha cada
- Progresso salvo automaticamente e carregado ao iniciar
- Efeitos sonoros simples no terminal

## Como jogar

Requisito: Python 3.10 ou superior.

```bash
git clone https://github.com/Ocarinna/terminal-adventure-python.git
cd terminal-adventure-python
python "Terminal Adventure.py"
```

### Controles

Durante as batalhas, digite o número da ação:

| Tecla | Ação    |
|-------|---------|
| 1     | Atacar  |
| 2     | Bloquear|
| 3     | Curar   |
| 4     | Fugir   |

O jogo termina com vitória quando todos os inimigos principais forem derrotados.

## Salvamento

O progresso é salvo automaticamente. Ao abrir o jogo, você escolhe se quer continuar de onde parou.

## Próximos passos

- [ ] Separar o código em módulos (`engine`, `player`, `battle`, `areas`, `save`)
- [ ] Criar uma classe `Player` no lugar de variáveis globais
- [ ] Lançar uma versão web do jogo

## Tecnologias

Python 3 (apenas biblioteca padrão)

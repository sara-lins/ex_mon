# ExMon

**Turn-based game where we will have a player against the computer.**

### Game rules:
Turn-based game where we will have a player against the
computer
- Human and computer start with 100 health;
- Each round, each can make one of 3 moves:
  - Moderate attack dealing between (18-25) damage;
  - Ranged attack dealing between (10-35) damage;
  - Healing power, healing between (18-25) hp;
- With each movement, what happened should be displayed on the screen and the
situation of each player;
- If either the player or the computer drops to 0 health, it's game over;
- If someone loses, when displaying the final result, it should not be
displayed that some player had negative life;
- The human player will be able to choose his character's name,
as well as the name of its 3 movements;

![Project image](/assets/exmon.png)

## Installation

```elixir
# Clone este repositório
> git clone git@github.com:sara-lins/ex_mon.git

# Acesse a pasta do projeto no terminal
> cd ex_mon

# Abra o vscode
> code .

# Rode o projeto no terminal
> iex -S mix

# Rodando os testes
> mix test
```

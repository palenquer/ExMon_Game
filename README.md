# ExMon

Um jogo simples baseado em turnos desenvolvido através do curso "Aprenda Elixir criando um jogo e sua primeira API RESTful utilizando Phoenix com autenticação." por Rafael F. Camarda na plataforma Udemy.

## Inicializando o projeto

Para dar início ao projeto, digite ``` iex -S mix ``` no seu terminal e logo em seguida crie um jogador utilizando o seguinte exemplo: 

```player = ExMon.create_player("Paulo", :soco, :chute, :cura)```. 

A função create_player recebe 4 parâmetros. O primeiro parâmetro é o nome do jogador, o segundo é o ataque médio, o terceiro é o ataque variável e o quarto e último é o movimento de cura.

Após a criação do jogador, digite:

```ExMon.start_game(player)```

Para dar início ao jogo e começar a batalha. Para dar início a um movimento na batalha digite:
``` ExMon.make_move() ```
Passando o movimento que o jogador quer que seja utilizado. Exemplo:

```ExMon.make_move(:chute)```

Logo após, o computador fará um movimento aleatório e então o jogador poderá jogar novamente. Ao jogador ou o computador chegar a 0 de vida, o jogo termina.




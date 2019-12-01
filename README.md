# Connect 4
Implementation in java of the famous game "connect 4" and some variants


To play it, simply:
- Add external library (`lib/commons-cli-1.2`)
- Run it

## Parameters
- `-g`,`--game <game>` Type of game (c4,co,gr,rv)
- `-h`,`--help` Shows this help
- `u`,`--ui <ui>` Type of interface (console, window). By default, console.
- `-x`,`--tamX <columns>` Number of board columns (only for Gravity). By default, 10.
- `-y`,`--tamY <rows>` Number of rows in the dashboard (only for Gravity). By default, 10.

## Console usage
If you use the console, the commands are:

- `SALIR`: Ends the application.
- `DESHACER`: Undoes the last move made in the game.
- `JUGAR [c4|co|gr|rv] [tamX tamY]`: Changes the game type. 
- `REINICIAR`: Resets the game.
- `PONER`: Use it to put the next piece.
- `JUGADOR [blancas|negras] [humano|aleatorio]`: Changes the type of player ( [white|black] [human|random] ).
- `AYUDA`: Shows the help.

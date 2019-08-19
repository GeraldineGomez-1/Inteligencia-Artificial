# Triqui 

Es un programa que permitee jugar el juego mas comunmente conocido como Triqui, el cual emula para el usuario un contricante 
computarizado que obtiene sus posibles jugadas a través de la técnica Minmax y poda alfa-beta.

## Descripción del juego

El juego se encuentra representado por un tablero con 3 filas y 3 columnas. Los jugadores podran escoger entre dos símbolos para jugar X u O.  

Por turnos cada jugador deberá colocar el símbolo que haya escogido en un espacio del tablero, intentando formar con 3 de estos una linea horizontal o vertical, cuando esto se logre podrá considerarse el ganador de la partida.

Al haberse llenado totalmente el tablero de simbolos sin haber pordido formar la linea ningúno de los dos jugadores, se considerara empate.


## Ejecución
Para poder ejecutar el programa realice los siguientes pasos:
1. Seleccione el archivo zip, de clic derecho dobre este y en el menu emergente oprima descomprimir.
2. En el buscador de su computador ingrese la palabra consola o terminal, cuando obtenga resultados abra la aplicación que dependiendo del sistema operativo se llamara simbolo del sistema (Windows) o terminal (Linux - IOS).
3. Regrese a la carpeta donde se encuentra el archivo del programa, de clic derecho sobre este nuevamente 
4. Seleccione propiedades, podra visualizar un cuadro dialogo que tendra un campo llamado ubicación, sombree con su cursor la información contenida allí, de clic derecho, finalmente oprima copiar y dirijase nuevamente a la consola o terminal, en la cual digitara los siguientes comandos:
    - cd, presione la barra espaciadora, de clic derecho, seleccione copiar, vera como la información de la ubicación del archivo se escribe automáticamente, presione enter y con esto se encontrara en la carpeta deseada.
    - digite java -jar Triqui.jar, y oprima enter.

## Detalles de la aplicación

La aplicación asignara el primer turno de manera aleaotoria, es decir si la computadora o el usuario comenzara la partida respectivamente, en dado que caso que la máquina inicie, se le otorgara el simbolo O, de igual forma si lo hace el usuario. 

Las posiciones del tablero tendrán como representación el formato del número de la casilla, al ser una matriz de 3x3, cada casilla estara enumerada horizontalmente como 0,1,2,3,4,5,6,7,8. 

## Uso

Al ejecutarse la aplicación, mostrara una interfaz con un tablero, donde podra visualizar tanto el tablero como un enunciado con las posiciones disponibles para insertar el símbolo correspondiente y junto a este un numero entre paréntesis ( ), el cúal podrá presionar para poner el símbolo en la casilla deseada.

Al digitarlo el tablero se actualizará de forma automatica, cediendole el turno a la computadora y continuando la partida.








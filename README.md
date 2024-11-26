# Social Simulation
---
## Ejercicio 1: Visualización de puntajes tras varias rondas

### Descripción del Juego
Este ejercicio simula un torneo de *Piedra, Papel o Tijera* entre cuatro jugadores: **Jim**, **Jane**, **Peter** y **Zoe**. Cada jugador compite contra todos los demás en múltiples rondas, y sus estrategias se eligen al azar en cada enfrentamiento. Se utilizan las siguientes reglas para determinar el ganador de cada partida:

### Reglas del Juego
| Jugador 1   | Jugador 2   | Resultado        |
|-------------|-------------|------------------|
| Piedra      | Papel       | Jugador 2 gana   |
| Papel       | Piedra      | Jugador 1 gana   |
| Piedra      | Tijeras     | Jugador 1 gana   |
| Tijeras     | Piedra      | Jugador 2 gana   |
| Papel       | Tijeras     | Jugador 2 gana   |
| Tijeras     | Papel       | Jugador 1 gana   |
| Piedra      | Piedra      | Empate (0 puntos) |
| Papel       | Papel       | Empate (0 puntos) |
| Tijeras     | Tijeras     | Empate (0 puntos) |

### Dinámica del Torneo
1. **Jugadores**: Los jugadores comienzan con un puntaje inicial de 0.
2. **Estrategias**: En cada ronda, cada jugador elige una estrategia de forma aleatoria entre: *Piedra*, *Papel* o *Tijeras*.
3. **Rondas**: El torneo se desarrolla en 100 rondas.
4. **Puntajes**: Después de cada enfrentamiento, se asignan puntos según las reglas descritas.

### Resultados Finales
Tras 100 rondas de competencia, los puntajes finales de los jugadores son los siguientes:

| Nombre   | Puntaje | Estrategia Final |
|----------|---------|------------------|
| Jim      | 90      | Papel            |
| Jane     | 103     | Papel            |
| Peter    | 100     | Tijeras          |
| Zoe      | 95      | Papel            |

### Ganador
La ganadora del torneo es **Jane**, con un puntaje de **103**.

## Ejercicio 2: Aplicación para el juego "Piedra, Papel, Tijera, Lagarto, Spock"

### Descripción del Juego
Este ejercicio simula un torneo entre 10 jugadores que participan en el juego ampliado de *Piedra, Papel, Tijera, Lagarto, Spock*. Cada jugador compite contra todos los demás en múltiples rondas, eligiendo estrategias al azar.

### Qué vence a qué:
| Elemento      | Vence a                  | Razón                  |
|---------------|--------------------------|------------------------|
| **Piedra**    | Tijeras, Lagarto         | Aplasta, aplasta       |
| **Papel**     | Piedra, Spock            | Cubre, refuta          |
| **Tijera**    | Papel, Lagarto           | Corta, decapita        |
| **Lagarto**   | Spock, Papel             | Envenena, come         |
| **Spock**     | Tijeras, Piedra          | Rompe, vaporiza        |

### Estrategias disponibles
- **Rock**
- **Paper**
- **Scissors**
- **Lizard**
- **Spock**

### Resultados del Torneo
Se jugaron **10 rondas**, donde cada jugador eligió su estrategia de manera aleatoria en cada enfrentamiento. A continuación, se muestran los resultados finales.

| Nombre     | Puntaje | Estrategia Final |
|------------|---------|------------------|
| rosite     | 34      | Scissors         |
| aleli      | 29      | Paper            |
| ed         | 30      | Rock             |
| charles    | 29      | Lizard           |
| nico       | 33      | Scissors         |
| elenita    | 25      | Scissors         |
| dani       | 25      | Paper            |
| liz        | 26      | Paper            |
| tomi       | 24      | Lizard           |
| **jose**   | **38**  | Rock             |

### Ganador del Torneo
El ganador del torneo es **jose**, con un puntaje de **38** y una estrategia final de **Rock**.

## Enlace a la tarea
---
https://rosite12.github.io/Social-Simulation/tarea.html

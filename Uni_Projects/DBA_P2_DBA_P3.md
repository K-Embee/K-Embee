# DBA_P2 / DBA_P3

Link/Enlace: 
* Project/Proyecto 1: https://github.com/monicordovilla/DBA_P2
* Project/Proyecto 2: https://github.com/monicordovilla/DBA_P3

## English

### University Project:
* Year: 2019-2020
* Subject: Agent-Based Development
* Language: Java
* Goal: Create an agent that can optimally achieve an objective in a simulated world / Create a group of communicating agents that can optimally achieve an objective in a simulated world. Apply SCRUM development to a real project.
* Collaborators: @monicordovilla, @AnaBosch, @celiabotella, @Alaiin

Two separate projects, the second being a continuation of the first, consisting in creating agents that control virtual drones that must navigate a grid-based 3D world in order to reach a goal. The first project involves managing a single agent, ensuring that it does not run out of fuel, crash into the terrain, and finds its objective relatively quickly via various pathfinding methods without perfect knowledge of its environment.

The second has multiple agents communicating with eachother via ACL message passing in order to locate as many objectives as possible within a certain global fuel limit. The drones are heterogeneous, there are three types of 'search' drones with varying tradeoffs between fuel efficiency and sensor size and a 'rescue' drone that is the only one able to complete objectives.

The server-side code is in the hands of the course's professor and, as far as I know, is not publicly available.

## Español

### Práctica Universitaria:
* Curso: 2019-2020
* Asignatura: Desarrollo Basado en Agentes
* Lenguaje: Java
* Objetivos: Crear un agente que ha de resolver un problema de manera óptima en un mundo simulado / Crear un grupo de agentes que se comunican entre sí para resolver un problema en un mundo simulado. Aplicar SCRUM a un proyecto real.
* Colaboradores: @monicordovilla, @AnaBosch, @celiabotella, @Alaiin

Dos proyectos separados, el segundo siendo una continuación del primero, consistiendo en crear agentes que controlan drones virtuales que han de navegar un mundo discreto 3D para alcanzar una meta. El primer proyecto consistió en manejar un unico agente, asegurandose de que no se queda sin combustible, que no se choque contra el terreno y que encuentre su objetivo rápidamente mediante varios métodos de búsqueda de ruta sin conocimiento perfecto de su entorno.

El segundo consta de varios agentes comunicandose entre sí mediante paso de mensajes ACL para encontrar el máximo número de objetivos posibles dentro de un límitie de consumo de combustible. Los drones son heterogeneos, hay tres tipos de drones de búsqueda con diferentes eficiencias de consumo y tamaño de sensores, y un drón de rescate que es el único capaz de alcanzar los objetivos.

El código del servidor esta en manos del profesor, y según lo que se, no está disponible públicamente.

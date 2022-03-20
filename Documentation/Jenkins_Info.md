## Arquitectura Master / Slave de Jenkins:

![image](https://user-images.githubusercontent.com/17514509/159185719-d688661b-8204-4b2c-a8ba-1424dbe10edd.png)

### Job / Project:
Se refieren a tareas ejecutables que son controladas y monitoreadas por Jenkins.

### Slave / Node:
- Slaves son computadoras establecidas para construir projectos para un master.
- Jenkins ejectua un programa por separado llamado **slave agent** en los Slaves.
- Cuando los Slaves estan registrados a un master, el master empieza a distribuir los trabajos a los slaves.
- Node se utiliza para refererirse a ttodas las maquinas que son parte de una malla Jenkins, slaves y masters.

### Executor:
- Executor es una rama de builds a ser ejectuados en un node en paralelo.
- Un Node puede tener uno o mas executors.

### Build
Resultado de la ejecucion de uno de los projectos.

### Plugin:
Como en cualquier otro sistema, es una pieza de software que agrega funcionalidad al servidor central de Jenkins.

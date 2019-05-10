# BLOCKCHAIN, SUS APLICACIONES Y EL CLOUD

A lo largo de estos años es fácil que hayamos oido hablar la palabra Blockchain, especialmente ligada al Bitcoin y resto de monedas. Pero, ¿qué es realmente el blockchain?

## INTRODUCCIÓN

Esta tecnología tuvo su origen como soporte para las transacciones con bitcoin, fue originalmente utilizada por figuras que se oponían al sistema establecido y que querían conseguir independencia del control central. 

Veamos un ejemplo concreto, en este caso una transacción monetaria y el rol que el bitcoin podr ía tener. Pagamos un dolar por algún bien material. Esta transacción se realizó porque el valor de un dolar está representado por un bil- lete, el cual fue creado por un Gobierno en el que ambas partes confían, que se reconocen y aceptan. Cuando esta compra-venta se concrete, los detalles deben quedar escritos en un libro de cuentas.

En el caso de transacciones electrónicas entran en participación terceras partes fiables como bancos u operadores como Google Wallet o Paypal. Pero se sigue manejando una moneda centralizada como el dolar. Al final, las entidades financieras concilian las operaciones y obtienen sus beneficios correspondientes.

La situación cambia cuando la moneda es virtual y no la emite una entidad financiera o administración. En este caso se garantiza la integridad y fiabilidad basándose en el consenso. Aquí entra en juego el blockchain. El Blockchain (o cadena de bloques) es una base de datos compartida que funciona como un libro para el registro de operaciones de compra-venta o cualquier otra transacción.

Es un conjunto de apuntes que están en una base de datos compartida en la que se registran mediante códigos las transacciones realizadas. Al utilizar claves criptográficas y al estar distribuido por muchos ordenadores presenta ventajas en la seguridad frente a manipulaciones y fraudes. Una modificación en una de las copias seria inútil, ya que se debe realizar el cambio en todas las copias porque la base es abierta y pública [2]. La potencia de blockchains viene por la conjunción de sus tres grandes cualidades: irrefutable, irrevocable y distribuida.

Ahora bien, esta tecnología puede cambiar el mundo porque este modo de operar, en el que toda la información se distribuye con total transparencia por todos los nodos del sistema, puede terminar aplicándose a todo tipo de transac- ciones entre todo tipo de intervinientes, públicos o privados.[3]

    - Clasificación segun el acceso a los datos? 

## COMPONENTES

La tecnología está basada en cuatro fundamentos: el registro compartido de las transacciones (ledger), el consenso para verificar las transacciones, un contrato que determina las reglas de funcionamiento de las transacciones y finalmente la criptografía, que es el fundamento de todo[5]. En esta sección veremos los componentes que hacen esto posible.

### Bloques

Blockchain es un registro de todas las transacciones que se empaquetan en blo- ques que los mineros luego se encargan de verificar. Luego serán agregadas a la cadena una vez terminada su validación y distribuidas a todos los nodos que forman la red. En la actualidad, la cadena de bloques bitcoin ocupa unos 170 gigas aproximadamente)[6].
Un bloque es un conjunto de transacciones confirmadas e información adi- cional que se ha incluido en la cadena de bloques. Cada bloque que forma parte de la cadena (menos el primer bloque que inicia la cadena) está formado por:
1. Un código alfanumérico que enlaza con el bloque anterior
2. El “paquete” de transacciones que incluye
3. Otro código alfanumérico que enlazará con el siguiente bloque.

![Figura2](img/2.png)

El bloque en progreso lo que intenta es averiguar con cálculos el ultimo punto.
Los bloques son generados por los mineros.

### Mineros

Los mineros son ordenadores dedicados que aportan su poder computacional a la red para verificar las transacciones que se llevan a cabo. Son computadoras que se encargan de autorizar la adición de los bloques de transacción. Estos siguen los siguientes pasos[7]:

1. Las nuevas transacciones se transmiten a todos los nodos
2. Cada nodo de la minería recoge nuevas transacciones en un bloque.
3. Cada nodo minero trabaja en la búsqueda de una prueba de trabajo para su
bloque.
4. Cuando un nodo de la minería encuentra una prueba de trabajo, este trans-
mite el bloque a todos los nodos.
5. Los demás nodos acepta el bloque sólo si todas las transacciones son válidas
y no se hayan gastado.
6. Los nodos expresan su aceptación del bloque trabajando en la creación del
próximo bloque en la cadena, utilizando el hash del bloque aceptado como el hash anterior.
Cada vez que alguien completa un bloque recibe una recompensa en forma
de bitcoins y/o por cada transacción que se realiza.

### Nodos

Son computadoras conectadas a la red utilizando un software que almacena y distribuye una copia actualizada en tiempo real del blockchain.
Cada vez que un bloque se valida y se an ̃ade a la cadena, el cambio es comunicado a todos los nodos y este se an ̃ade a la copia que cada uno almacena. Algunos, conocidos como mining pools o grupos de minería, se encargan ade- mas de escuchar nuevas transacciones y agruparlas en bloques para proponerlos como trabajo a los mineros,que luego de ser confirmados son propagados a la
red y an ̃adidos a la cadena.

![Figura3](img/3.png)

## CARACTERÍSTICAS Y FUNCIONAMIENTO

Las propiedades mas importantes para describir como funciona la tecnología blockchain son las siguientes: es de carácter descentralizado, pues esta no requiere un organismo o entidad central de confianza, es una tecnología distribuida y de consenso, porque que parte de unas reglas claras y un consenso sobre la validez de las transacciones y su estado, abierta tal que cualquier usuario puede hacer uso de ella y finalmente segura gracias a la verificación criptográfica. [8]

### Descentralizado

Expertos explican[9], que las redes blockchain son altamente escalables, descen- tralizadas y peer-to-peer. Es asi que, la integridad está basada en un mecanismo de consenso, en vez de una infraestructura basada en la confianza sobre un or- ganismo central, como sería un banco u otra entidad financiera. La red P2P evita que un único participante o grupo controlen el sistema completo. Todos los in- tegrantes de una red se adhieren, a los mismos protocolos, ya sean individuos, organizaciones o actores estatales. Las transacciones son irreversibles, por lo que una vez realizadas no pueden anularse, modificarse o revertirse.
Así, se eliminan los riesgos que vienen con los sistemas centralizados[10]. La red carece de puntos críticos o centrales de vulnerabilidad que podrían ser ex- plotados. Los métodos de seguridad Blockchain incluyen el uso de la criptografía de clave pública: Una clave pública es una dirección en la cadena de bloque. Los tokens, como por ejemplo bitcoins, son enviados a través de la red y se registran como pertenecientes a esa dirección. Una clave privada es como una contrasen ̃a que le da acceso a su propietario a sus activos digitales.
Cada nodo o minero en un sistema descentralizado tiene una copia de la cadena de bloqueo. La calidad de los datos se mantiene mediante la replicación masiva de bases de datos[11]. No existe una copia oficial centralizada y ningún usuario es de más confianza que cualquier otro.

### Sistema abierto

Es abierto porque cualquier persona puede formar parte tan solo con descargándose el programa. Luego ella podrá realizar movimientos y transacciones con monedas virtuales y acceder a los datos registrados en su cadena de bloques.
A veces los bloques se pueden producir concurrentemente, creando un fork temporal. La cadena de bloques tiene un algoritmo especificado para marcar diferentes versiones de la cadena para que una con un valor más alto pueda ser seleccionada sobre otras. Los bloques no seleccionados para su inclusión en la cadena se denominan bloques húerfanos[12], como se observa en la figura 4.

![Figura4](img/4.png)

Los peers de la red pueden tener de vez en cuando versiones diferentes de la base de datos. Estas solo guardan la versión con la puntuación más alta que conocen. Cada vez que un compan ̃ero recibe una versión de puntuación más alta (usualmente la versión antigua mas un solo bloque an ̃adido) extienden o sobrescriben su propia base de datos y retransmiten la mejora a sus pares. Por ejemplo, en una cadena de bloques utilizando el sistema de prueba de trabajo, la cadena con la prueba de trabajo más acumulativa siempre es la considerada válida por la red.

### Seguridad

Los bloques que forman parte del blockchain son ordenados en la cadena por orden cronológico y tienen un código alfanumérico conocido como hash, que cor- responde al bloque que los precede, gracias a ese hash todos están referenciados por el bloque que los creo, por lo que solo los bloques que contienen un código valido son introducidos en la cadena y replicados a todos los nodos. Es gracias a este método lo que hace virtualmente imposible modificar un bloque que ha sido introducido ya hace un cierto tiempo.
Los nodos mineros son los encargados de la creación de nuevos bloques de la cadena, computando y an ̃adiendo luego a cada uno de ellos el hash y todas las nuevas transacciones correspondientes. Por lo tanto el blockchain nos permite llevar a cabo, una contabilidad publica de los movimientos realizados en la red de manera transparente, minimizando la posibilidad de fraude, no permitiendo la perdida de datos y con un sistema totalmente trazable.

![Figura5](img/5.png)


Es necesario que los nodos que integran la red estén sincronizados mante- niendo almacenada la cadena de bloques correcta, es decir la que esta actu- alizada. Como también observamos anteriormente, cada bloque contiene infor- mación sobre las transacciones de un periodo concreto, estas son almacenadas en una estructura denominada Merkle Tree (en honor a su creador: Ralph Merkle), también la información criptográfica del bloque precedente es decir, el código hash (Las funciones de hash, permiten parear strings de un taman ̃o cualquiera a strings de taman ̃o fijo en una cantidad de tiempo razonable, en el caso de la moneda virtual Bitcoin se emplea la función hash criptográfica SHA-256, siendo sus apuntadores hash de un taman ̃o fijo de 256 bit), y un número único llamado nonce, el cual es un valor arbitrario que puede utilizarse una sola vez, es gen- erado por los mineros mediante la prueba de trabajo (Proof of Work o PoW) y sirve como método sencillo para autenticar un bloque en caso de una posible modificación o reutilización de su contenido, sin tener que volver a procesar toda la cadena, ahorrando así mucho trabajo computacional.

Esta estructura de árbol binario, reúne pedazos de información y da como resultado un hash por cada uno de ellos, que vuelven a agruparse en pares y generan un nuevo hash que es agrupado con otro y así sucesivamente hasta alcanzar un único bloque raíz que se conoce como root hash, y es registrado en la dirección del bloque actual con el fin de reducir el espacio ocupado por cada bloque. Se puede observar un ejemplo en el gráfico 6:

![Figura6](img/6.png)

Esta estructura permite recorrer cualquier nodo del árbol para la verificación de que ningún dato ha sido falsificado o adulterado.
Un bloque se verifica cuando el nonce, un número aleatorio que es utilizado una única vez, se encontró que, pasado por una función hash, proporciona un resultado menor que el valor objetivo. Una vez que el esfuerzo computacional satisface la prueba de trabajo, no se puede cambiar sin hacer de nuevo todo el trabajo, y, como los bloques están encadenados juntos, se deben calcular todos los bloques despúes de él también. Las pruebas de trabajo son esencialmente un sistema de una CPU, un voto. La decisión de la mayoría esta representada por la cadena mas larga, que tiene el mayor esfuerzo de pruebas de trabajo invertido. Para modificar un bloque pasado, para intentar robar bitcoins, un atacante debe rehacer todas las pruebas de trabajo y todos los bloques despúes de el y luego alcanzar y sobrepasar el trabajo de los nodos honestos[7].
Las cadenas de bloque también pueden utilizan otros esquemas de consenso, para serializar los cambios. Los métodos de consenso alternativos incluyen Proof of Stake y Proof of Burn.

## APLICACIONES





































## Cuestiones

- ¿Es totalmente seguro blockchain?
- Si por ejemplo bitcoin ocupa 170 GB, ya que el blockchain hace uso de la replicación de datos en cada base de datos.... esto en cloud no estaría generando una replicación innecesaria?
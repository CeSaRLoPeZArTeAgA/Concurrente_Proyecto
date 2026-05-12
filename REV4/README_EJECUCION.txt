ESTRUCTURA
==========

1.- SERVIDOR_MICRO_CHUNK-JAVA/
   - modelo_mnist.bin
   - word2vec_model.bin
   - redesOk/Servidor50.java
   - redesOk/TCPServer50.java
   - redesOk/TCPServerThread50.java
   - redesOk/MLP.java
   - redesOk/MNISTDataset.java
   - redesOk/Word2VecModel.java

2.- CLIENTE_MICRO_CHUNK-JAVA/
   - redesOk/Cliente50.java
   - redesOk/TCPClient50.java
   - redesOk/MainMenuCliente.java
   - redesOk/MainFormularioMNISTCliente.java
   - redesOk/MainFormularioWord2VecCliente.java

EJECUTAR SERVIDOR - JAVA
===========================
Abrir terminal dentro de SERVIDOR_MICRO_CHUNK:

javac -encoding UTF-8 -d out redesOk/*.java
java -cp out redesOk.Servidor50 5000

Si no pasas puerto, usa 4444 por defecto:

java -cp out redesOk.Servidor50

EJECUTAR CLIENTE 1 - JAVA
==============================
Abrir terminal dentro de CLIENTE_MICRO_CHUNK:

javac -encoding UTF-8 -d out redesOk/*.java
java -cp out redesOk.Cliente50

El cliente pedira:
- IP del servidor
- Puerto del servidor
- Nombre del cliente

Si servidor y cliente estan en la misma computadora:
IP: 127.0.0.1
Puerto: 5000

Si el servidor esta en otra computadora:
IP: usar la IP real del servidor, por ejemplo 192.168.1.119
Puerto: el mismo puerto del servidor, por ejemplo 6666


EJECUTAR CLIENTE 2 - PYTHON
==============================



EJECUTAR CLIENTE 3 - C++
==============================




EJECUTAR CLIENTE 2 - KOTLIN
==============================





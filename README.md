# tesina

Repositorio para el proyecto de tesina 
"Realización de un protocolo de autenticación para el 
mejoramiento de la privacidad del usuario". Este repositorio
contiene el fork de [cas-overlay-template](https://github.com/adal347/cas-overlay-template)
y de [cordapp-example](https://github.com/adal347/cordapp-example).

Para *cordapp-example* necesitas el [jdk de java](http://www.oracle.com/technetwork/java/javase/downloads/index.html)
y [IntelliJ v2017.3](https://www.jetbrains.com/idea/download/previous.html).

1. Instalar Corda

```dos
git clone https://github.com/adal347/cordapp-example.git
```

2. sigue los pasos de [Corda](https://docs.corda.net/tutorial-cordapp.html) para realizar el setup del proyecto.

3. Instalar C.A.S.

```dos
git clone https://github.com/adal347/cas-overlay-template.git
```

3. Generar la Web of Trust, con las claves de los involucrados.

4. Correr el proyecto

```dos
build run
```

# Sin Codigos

## Integrantes

- Benicio Pacheco
- Valentino Lenoci

## Descripcion

Sin Codigos es un videojuego de accion 2D con vista cenital, ambientado en un barrio
ficticio dividido en tres zonas controladas por distintas bandas. Esta disenado para dos
jugadores en red local y combina movimiento, misiones, combate e IA de enemigos.

La propuesta completa esta disponible en la
[pagina de la propuesta](https://github.com/benipach/sin-codigos/wiki/Propuesta-del-Proyecto-%E2%80%90-Sin-Codigos).

## Tecnologias

- Java 21
- LibGDX 1.14.2
- Gradle
- LWJGL3 para escritorio
- Git y GitHub

Plataforma objetivo de esta entrega: escritorio.

## Estado actual

Configuracion inicial del proyecto: estructura generada con gdx-liftoff, modulos core
y lwjgl3, proyecto preparado para compilacion y ejecucion en escritorio.

## Compilar y ejecutar

Requisitos:

- JDK 21
- Git

Clonar y entrar al proyecto:

```bash
git clone https://github.com/benipach/sin-codigos.git
cd sin-codigos
```

Compilar el proyecto:

```bash
./gradlew build
```

En Windows:

```bat
gradlew.bat build
```

Ejecutar la version de escritorio:

```bash
./gradlew lwjgl3:run
```

En Windows:

```bat
gradlew.bat lwjgl3:run
```

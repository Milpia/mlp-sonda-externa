# mlp-sonda-externa

Sondeo externo de Milpia. Cada hora comprueba, desde fuera de nuestros servidores, que el acceso responde y que lo que debe estar cerrado a internet lo sigue estando. Si algo falla, avisa a nuestros canales de alertas.

Este repositorio solo contiene ese workflow. Es público porque en un repositorio público GitHub Actions no consume minutos, y está aparte para que el token que lo dispara no alcance nada más.

- El workflow se dispara desde un cron externo, no con `schedule`.
- No se edita aquí: la copia de referencia vive en el repositorio de infraestructura de Milpia y se publica desde allí.
- No aceptamos issues ni pull requests en este repositorio.

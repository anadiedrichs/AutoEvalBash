# AutoEvalBash

# Desafíos de Linux con Docker

Entorno interactivo y reproducible para practicar administración de sistemas Linux con verificación automática de niveles.

## Requisitos previos

- Docker instalado y en ejecución.

## Cómo construir y ejecutar el entorno

1. Clonar el repositorio:

 >  git clone https://github.com/anadiedrichs/AutoEvalBash/

 >  cd AutoEvalBash

3. Construir la imagen Docker:

  > docker build -t desafio-linux .

4. Iniciar el contenedor de forma interactiva:

  > docker run -it --rm desafio-linux

## Cómo jugar y verificar tu progreso

Una vez dentro del contenedor:
- Lee las consignas del nivel actual.
- Ejecuta el comando `jugar` en la terminal para validar tu solución y desbloquear el siguiente nivel.

## Niveles incluidos

- Nivel 1: [Breve descripción del desafío 1 ]
- Nivel 2: [Breve descripción del desafío 2]

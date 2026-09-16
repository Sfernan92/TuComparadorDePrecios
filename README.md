# TuComparadorDePrecios

> ⚠⚠ IMPORTANTE: Para Visualizar el proyecto, ir a la **rama DEV**, ya que la rama main, esta limpia, En dicha rama se explica el proyecto y como desplegarlo. ⚠⚠

# 💰 "Dontacaño.com" - Tu Comparador de Precios.

## 🧠 Idea Principal.

En este proyecto vamos a realizar una página web que compare los precios de productos de distintos supermercados para realizar un análisis de todos los precios que hay actualmente en el mercado. Además podremos realizar búsquedas en la que se nos mostrará los distintos supermercados donde nuestros productos buscados estén más baratos. Así como también podremos realizar la inserción de nuevos supermercados, nuevos productos, sus precios o incluso actualizar los ya existentes para tenerlos actualizados en todo momento con los anteriores. 

Con todo ello intentaremos ayudar a los usuarios que vayan a realizar sus compras diarias para saber en qué supermercados se encuentran sus productos a mejor precio, promoviendo así un ahorro en sus compras. 

Los datos de las tiendas se insertaran en nuestra base de datos mediante un frontal el cual interactuará con un backend que realizaremos en java mediante Springboot. 

## 🎯 Objetivo Principal.

El objetivo principal del proyecto es realizar una página web de comparación de precios de los distintos productos que nos ofrecen los supermercados hoy en día. De esta forma ayudaremos a los consumidores a ahorrar en cada una de sus compras en el día a día, así como poder decidir en qué lugar o supermercado realizar la compra para que dicha compra le salga lo más económicamente posible. Además estaremos ayudando a los usuarios no solo a ahorrar económicamente sino a ahorrar en tiempo, es decir, aprovecharan más su tiempo al saber a qué tienda poder acudir sin necesidad de tener que estar buscando o comparando precios u ofertas de diferentes supermercados. Por lo que podríamos decir que como objetivo general es desarrollar una plataforma digital o web donde ayude a los usuarios a comparar precios de productos en distintos supermercados, ayudándoles en la toma de decisiones, la cual está basada en criterios de stock, coste y calidad.

## 📍 Objetivos Específicos.

1. Diseñar una interfaz que sea fácil e intuitiva de forma que los usuarios puedan comparar y buscar los precios de los productos de forma sencilla.
2. Actualizar datos y recabar precios de los distintos productos en los distintos supermercados.
3. La actualización de precios es de forma manual a través de fuentes de datos fiables.
4. Opciones de personalización y implementación de filtros para que los usuarios puedan filtrar o ajustar según sus necesidades los criterios de búsqueda.
5. Optimización del rendimiento del sistema, de esta forma puede ofrecerse comparaciones rápidas y precisas.

## ✅ Requisitos Funcionales.

- RF1, Búsqueda de productos. Los usuarios podrán buscar por nombre, categoría o marca los productos.
- RF2, Comparación de precios. Nuestro comparador mostrará los distintos precios de un mismo producto en los distintos supermercados.
- RF3, Actualización de precios y supermercados. Habrá un apartado en el que podremos ir actualizando los distintos precios de los productos en base de datos y de supermercados.
- RF4, Filtrado o buscador. Tendremos un filtro o buscador donde los usuarios podrán buscar los productos por nombre, marca, categoría, etc.

## 📑 Requisitos no Funcionales.

1. El rendimiento y la escalabilidad de la plataforma son fundamentales para garantizar una experiencia fluida a los usuarios. Es muy importante que su velocidad de respuesta no se vea afectada. Además, debe contar con una arquitectura escalable que le permita crecer sin que su rendimiento se degrade a medida que aumenta la cantidad de usuarios y productos disponibles.
2. En cuanto a la usabilidad y experiencia de usuario, la plataforma debe ser intuitiva y fácil de navegar, permitiendo que cualquier usuario pueda encontrar y comparar precios sin dificultad. La interfaz debe ser clara, con un diseño optimizado que facilite la búsqueda y visualización de información, es decir, la interfaz debe ser sencilla e intuitiva, nuestra página web debe ser sencilla y fácil de usar para que los usuarios puedan tener una navegación rápida a la hora de buscar productos y comparar precios.
3. La compatibilidad y accesibilidad también juegan un papel importante. La plataforma debe funcionar correctamente en diversos navegadores y sistemas operativos para garantizar que todos los usuarios puedan acceder sin inconvenientes.
4. Por último, el tiempo de respuesta es un aspecto clave en el desempeño del comparador de precios. Las consultas deben ejecutarse en el menor tiempo posible, idealmente en menos de dos segundos, para evitar esperas prolongadas y mejorar la eficiencia en la búsqueda de información. Una respuesta rápida no solo mejora la experiencia del usuario, sino que también fomenta la retención y el uso continuo de la plataforma.

## 🦦 Base de Datos.

Utilizo DBeaver para poder manejar la base de datos, en mi caso con PostgreSQL, desde ahí es donde puedo visualizar las distintas tablas de productos, precios, categorías o supermercados, puedo ejecutar las consultas SQL y importar nuevos datos o exportar datos. PostgreSQL es un sistema de gestión de bases de datos relacional de código abierto, muy potente y ampliamente utilizado tanto en aplicaciones pequeñas como empresariales. Nos permite almacenar, consultar y manipular datos estructurados usando SQL. También soporta características avanzadas que lo hacen muy flexible y extensible.

## 🚀 Despliegue de la aplicación.

Para desplegar DonTacaño.com antes tienes que instalar Docker Compose y Docker Desktop. Y posteriormente hacer los pasos siguientes:

### 🐳 Clonar y Levantar Contenedores en Docker.

### 📦 Clonar el Repositorio.

1. **Clave HTTPS.**

```
git clone git@github.com:CodeArts-Solutions/elephants-B-Fray-Meliton.git](https://github.com/Sfernan92/TuComparadorDePrecios.git)
```

2. **Clave SSH.**

```
git@github.com:Sfernan92/TuComparadorDePrecios.git
```

### 🆙 Levantar los contenedores de Docker.

```
docker compose up
```

### 🔄 Actualizar la rama del proyecto.

1. Una vez tengamos nueustro proyecto levantado el proyecto con docker, nos **vamos a Visual Studio Code**, donde nos aparecerá de entrada la rama main (la cual esta vacia con el proyecto limpio).
2. Abrimos consola y **entramos dentro de la carpeta angular-frontend** y utilizamos el comando `npm install` para instalar todas las dependencias y no tener errores en los módulos.
3. Una vez ahí, a través del comando `git fetch origin` nos **traemos las ramas del proyecto** y realizamos el comando `git checkout DEV`, para cambiarnos a la rama DEV que es donde está todo el proyecto. 

💲 ¡Una vez hecho todo esto **ya tendrás el proyecto** y podrás comenzar a **comparar precios y ahorrar**! 💲

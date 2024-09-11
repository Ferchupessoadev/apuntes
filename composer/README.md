# Apuntes Composer

# Composer - PHP Dependency Manager

## ¿Qué es Composer?

Composer es un gestor de dependencia de PHP inspirado en npm de Node.js y en bundler de Ruby.

Los paquetes y bibliotecas son administradas al nivel del proyecto, y aunque se pueden instalar de manera global, la herramienta no es un administrador de paquetes como APT.

Sitio oficial de Composer: [web oficial](https://getcomposer.org/)

## ¿Para qué sirve?

Composer permite agregar “paquetes” o bibliotecas a un proyecto existente de PHP o crear un proyecto nuevo a través de una plantilla existente o un framework de PHP como laravel.

 

## ¿Qué es Packagist?

Packagist es el repositorio principal de paquetes para Composer. Es una plataforma en línea donde los desarrolladores pueden publicar, compartir y encontrar paquetes de código PHP para usar en sus proyectos. vamos es como [npmjs.com](https://www.npmjs.com/)

web oficial: [packagist](https://packagist.org/)

## ¿Qué es Twig?

Twig es un motor de plantillas para PHP, diseñado para ser rápido, seguro y flexible. Es utilizado principalmente en el framework Symfony, pero también puede ser usado de forma independiente en otros proyectos PHP.

Características principales de Twig:

- Sintaxis limpia y fácil de leer
- Seguridad incorporada con escape automático de variables
- Extensible, permitiendo agregar funciones y filtros personalizados
- Compilación de plantillas para un rendimiento óptimo

Sitio oficial de Twig: [https://twig.symfony.com/](https://twig.symfony.com/)

### Instalación de dependencias de PHP con Composer

Primero, necesitamos crear un carpeta, por ejemplo, en sistemas linux abrimos una terminal y ejecutamos el comando

```bash
mkdir aprendiendo-composer
```

Luego, entramos en esa carpeta con **cd** y ejecutamos el siguiente comando

```bash
composer require twig/twig
```

## ¿Como eliminar una dependencia con Composer?

Eliminar una dependencia con composer es muy sencillo y todo se remonta a un comando

```bash
composer remove twig/twig
```

## ¿Actualizar Composer?

```bash
composer self-update
```

## **Comandos importantes de Composer**

Mostrar la lista de paquetes y dependencias

```bash
composer show
```
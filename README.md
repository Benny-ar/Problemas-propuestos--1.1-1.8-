# Problemas-propuestos--1.1-1.8-
En este repositorio agrupo ejercicios NoSQL hechos usando MongoDB en MongoDB Compass

Ejercicios hechos para la materia Base de Datos - Instituto Tecnologico Beltran 2026

# Objetivos de los Problemas Propuestos

## Problema 1.1
1. Insertar 2 documentos en la colección `clientes` con `_id` no repetidos.  
2. Intentar insertar otro documento con clave repetida.  
3. Mostrar todos los documentos de la colección.

## Problema 1.2
1. Crear una base de datos llamada `blog`.  
2. Agregar una colección llamada `posts` e insertar 1 documento con una estructura a su elección.  
3. Mostrar todas las bases de datos actuales.  
4. Eliminar la colección `posts`.  
5. Eliminar la base de datos `blog` y mostrar las bases de datos existentes.

## Problema 1.3
1. Crear la colección `articulos` en la base de datos `base1` (eliminar la colección previamente) y cargar 6 documentos.  
2. Imprimir todos los documentos de la colección `articulos`.  
3. Imprimir todos los documentos de la colección `articulos` que no son impresoras.  
4. Imprimir todos los artículos que pertenecen al rubro de `mouse`.  
5. Imprimir todos los artículos con un precio mayor o igual a 5000.  
6. Imprimir todas las impresoras que tienen un precio mayor o igual a 3500.  
7. Imprimir todos los artículos cuyo stock se encuentra comprendido entre 0 y 4.

## Problema 1.4
1. Crear la colección `articulos` en la base de datos `base1` (eliminar la colección previamente) y cargar 6 documentos (utilizar la colección del problema 1.3).  
2. Imprimir todos los documentos de la colección `articulos`.  
3. Borrar los documentos de la colección `articulos` cuyo rubro son impresoras, utilizando las dos sintaxis que permite MongoDB.  
4. Borrar todos los artículos que tienen un `_id` mayor o igual a 5.

## Problema 1.5
1. Crear la colección `articulos` en la base de datos `base1` (eliminar la colección previamente) y cargar 6 documentos (utilizar la colección del problema 1.3).  
2. Imprimir todos los documentos de la colección `articulos`.  
3. Modificar el precio del mouse `LOGITECH M90`.  
4. Fijar el stock en 0 del artículo cuyo `_id` es 6.  
5. Agregar el campo `proveedores` con el array `['Martinez','Gutierrez']` para el artículo cuyo `_id` es 6.  
6. Eliminar el campo `proveedores` para el artículo cuyo `_id` es 6.

## Problema 1.6
1. Crear la colección `articulos` en la base de datos `base1` (eliminar la colección previamente) y cargar 6 documentos (utilizar la colección del problema 1.3).  
2. Imprimir todos los documentos de la colección `articulos`.  
3. Fijar el stock en cero para todos los artículos del rubro monitor.  
4. Agregar un campo llamado `pedir` con el valor `true` para todos los artículos que tienen el campo stock en 0.  
5. Eliminar el campo `pedir` de todos los documentos.

## Problema 1.7
1. Crear la colección `medicamentos` en la base de datos `base1` (eliminar la colección previamente) y cargar 6 documentos.  
2. Imprimir todos los documentos de la colección `medicamentos`.  
3. Recuperar los medicamentos cuyo laboratorio sea `Roche` y cuyo precio sea menor a 5.  
4. Recuperar los medicamentos cuyo laboratorio sea `Roche` o cuyo precio sea menor a 5.  
5. Mostrar todos los medicamentos cuyo laboratorio NO sea `Bayer`.  
6. Mostrar todos los medicamentos cuyo laboratorio sea `Bayer` y cuya cantidad NO sea 100.  
7. Eliminar todos los documentos de la colección `medicamentos` cuyo laboratorio sea igual a `Bayer` y su precio sea mayor a 10.  
8. Cambiar la cantidad por 200 a todos los medicamentos de `Roche` cuyo precio sea mayor a 5.  
9. Borrar los medicamentos cuyo laboratorio sea `Bayer` o cuyo precio sea menor a 3.

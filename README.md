# Introducción al lenguaje SQL con el SGBD Firebird

➡️ Curso relacionado: **[Introducción al lenguaje SQL con el SGBD Firebird](https://stahe.github.io/ales-sql-firebird-janv-2006/)**

## Resumen

Este documento es una introducción al lenguaje **SQL (Structured Query Language)** aplicado al **sistema de gestión de bases de datos Firebird**.
Se trata de una adaptación de un documento educativo anterior escrito en **1991 para Oracle**, el cual, a su vez, se inspiró en gran medida en la documentación oficial de Oracle y en el libro:

* *SQL – Iniciación, programación y dominio*
  de **Christian Marée** y **Guy Ledant**, publicado por Eyrolles. 

SQL es un **lenguaje estándar que permite crear, mantener y realizar búsquedas en bases de datos relacionales**.
El lenguaje es en gran medida independiente del sistema de gestión de bases de datos (SGBD) utilizado, aunque algunos SGBD introducen sus propias extensiones. 

## ¿Por qué Firebird?

Los ejemplos de este documento utilizan el **SGBD Firebird**.
Esta elección se debe a una característica que resulta particularmente práctica en un contexto educativo: una base de datos de Firebird puede **almacenarse en un solo archivo**.

Esto permite, por ejemplo:

* copiar fácilmente una base de datos a una **memoria USB**
* usarla en **diferentes computadoras** (en casa, en la universidad, en el laboratorio)
* trabajar sin una infraestructura compleja

## Compatibilidad con SQL

Aunque los ejemplos están escritos para Firebird, la mayoría se pueden reproducir con otros sistemas de gestión de bases de datos relacionales, por ejemplo:

* MySQL
* PostgreSQL
* Firebird
* SQL Server Express
* Microsoft Access
* Oracle

Todos estos sistemas utilizan SQL, a veces con **variantes o extensiones específicas del producto**. 

## Público objetivo

Este documento está dirigido a:

* **principiantes que desean iniciarse en SQL**
* personas que **desean refrescar los conceptos básicos del lenguaje**

Se enfoca en el aprendizaje de **SQL fundamental**.

## Fuera del alcance de este documento

Se han omitido deliberadamente ciertos aspectos:

* procedimientos almacenados
* programación avanzada en SQL
* API de SQL
* administración de un SGBD

El objetivo es ofrecer una **introducción clara y paso a paso al lenguaje SQL**. 

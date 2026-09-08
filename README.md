# Ecosistema de Automatización IA con HITL

**Autora:** Cintia Alejandra Mouzo
**Fecha:** Septiembre de 2026

## Descripción

Proyecto final de automatización para la generación y gestión de contenidos mediante Inteligencia Artificial, con control humano antes de su aprobación y envío.

El ecosistema integra:

* **n8n:** orquestación del flujo.
* **Airtable:** base de datos, memoria y registro de ejecuciones.
* **OpenAI:** generación y procesamiento del contenido con RAG.
* **Gmail:** canal automatizado de salida.
* **HITL:** validación humana previa al envío.
* **Gestión de errores:** registro de fallos y reintentos controlados.

## Archivos del repositorio

* `Entrega_Final_Ecosistema_IA_HITL_Cintia_Mouzo_ACTUALIZADA.pdf`: documentación completa y evidencias.
* `Pipeline_Contenidos_HITL_PUBLICO.json`: workflow público de n8n, preparado sin credenciales privadas.

## Resultados de las pruebas

Se registraron siete ejecuciones:

* 3 ejecuciones exitosas.
* 4 errores controlados.
* Validación del contenido mediante HITL.
* Envío final confirmado por Gmail.
* Registro de estados, consumo de tokens y errores en Airtable.

## Video de demostración

[Ver demostración del ecosistema funcionando](https://youtu.be/FVsBsa83Vz0)

## Seguridad

El workflow publicado fue sanitizado para evitar la exposición de credenciales, claves privadas y datos sensibles.

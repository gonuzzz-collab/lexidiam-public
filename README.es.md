# Lexidiam

**Transcripción y revisión profesional diseñadas alrededor de privacidad, soberanía de datos y control humano.**

[Read in English](README.md)

![Arquitectura pública conceptual de Lexidiam](assets/lexidiam-architecture-es.png)

Lexidiam explora una pregunta:

> **¿Cómo podemos aprovechar la inteligencia artificial para procesar audio profesional sin obligar a las personas u organizaciones a ceder el control de sus grabaciones, transcripciones, metadatos y evidencia?**

Los sistemas modernos de transcripción pueden ser muy capaces, pero frecuentemente dependen de servicios externos y flujos de datos sobre los que el usuario tiene poco control.

Lexidiam adopta un enfoque diferente: priorizar **procesamiento local, custodia, trazabilidad, integridad y revisión humana profesional**.

---

## El problema

Una grabación profesional no es solamente un archivo de audio.

Puede involucrar:

- información sensible;
- identidad de participantes;
- transcripciones;
- segmentos y hablantes;
- metadatos;
- resultados producidos por IA;
- decisiones de revisión;
- exportaciones;
- evidencia asociada.

Cuando ese material se procesa fuera de la infraestructura controlada por el usuario, aparecen preguntas importantes:

- ¿Dónde queda almacenado?
- ¿Quién puede acceder?
- ¿Qué servicios externos lo procesan?
- ¿Cómo se conserva su trazabilidad?
- ¿Cómo distinguimos una salida automática de una revisión humana?
- ¿Quién mantiene el control sobre los datos originales y derivados?

Lexidiam está diseñado alrededor de esas preguntas.

---

## Principios

### Soberanía de datos

El sistema busca mantener audio, texto, metadatos y resultados asociados bajo control de sus usuarios siempre que sea posible.

### Procesamiento local

Las capacidades principales están orientadas a ejecutarse localmente cuando resulte práctico, reduciendo la dependencia de servicios externos.

### Revisión humana

La inteligencia artificial puede asistir intensivamente en la transcripción, diarización y análisis.

Los resultados destinados a contextos profesionales deben poder ser revisados y corregidos por una persona.

### Trazabilidad

Los cambios, revisiones y resultados deben poder relacionarse con el flujo de trabajo que los produjo.

### Integridad

El sistema incorpora mecanismos orientados a detectar cambios y preservar la relación entre los materiales procesados y sus resultados.

### Privacidad por diseño

La privacidad no se trata únicamente como una configuración adicional, sino como una restricción arquitectónica del producto.

---

## Flujo conceptual

```text
Audio autorizado
      ↓
Procesamiento local
      ↓
Transcripción + diarización
      ↓
Revisión profesional humana
      ↓
Trazabilidad + integridad
      ↓
Exportación controlada / custodia
```

La inteligencia artificial participa dentro del flujo, pero no reemplaza automáticamente la responsabilidad humana sobre el resultado final.

---

## Capacidades

Lexidiam integra diferentes etapas de un flujo profesional de trabajo con audio.

Entre ellas:

- ingestión de audio;
- transcripción automática;
- identificación y separación de hablantes;
- edición de segmentos;
- corrección de transcripciones;
- revisión profesional;
- herramientas de privacidad y anonimización;
- reproducción sincronizada de audio y texto;
- gestión de sesiones;
- biblioteca de transcripciones;
- exportaciones en diferentes formatos;
- mecanismos de trazabilidad e integridad;
- evaluación de calidad de transcripción.

El proyecto continúa evolucionando y no todas las capacidades se encuentran en el mismo nivel de madurez.

---

## Human-in-the-loop

Lexidiam no asume que una salida de inteligencia artificial deba convertirse directamente en un resultado profesional.

El modelo busca mantener una separación clara entre:

**resultado automatizado → revisión humana → resultado validado**

Esto es especialmente importante cuando precisión, procedencia y responsabilidad son relevantes.

---

## Soberanía y custodia

El diseño de Lexidiam busca que los datos permanezcan bajo control de la infraestructura que los utiliza.

La filosofía general puede resumirse así:

```text
Datos bajo control del usuario
        ↓
Procesamiento local
        ↓
Resultado revisado por humanos
        ↓
Retención o exportación controlada
```

El funcionamiento local no elimina todos los riesgos. También requiere controles relacionados con acceso, integridad, almacenamiento, recuperación y gestión de información sensible.

---

## Arquitectura

Lexidiam es un sistema en evolución con una arquitectura híbrida.

Diferentes componentes participan actualmente en:

- interfaz de usuario;
- procesamiento de audio;
- inferencia local;
- servicios de aplicación;
- almacenamiento;
- herramientas de revisión;
- capacidades de escritorio y red local en desarrollo.

La documentación pública evita describir mecanismos internos que puedan comprometer la seguridad, custodia, autorización, recuperación o implementación propietaria del sistema.

---

## Evolución asistida por IA

Lexidiam también ha funcionado como un entorno práctico para estudiar un problema más amplio:

> **¿Cómo mantener gobernable un sistema complejo cuando una parte creciente de su evolución es realizada con asistencia intensiva de inteligencia artificial?**

A medida que el proyecto creció, comenzaron a adquirir mayor importancia las decisiones arquitectónicas, documentación, evidencia, trazabilidad, límites de automatización, gobernanza de cambios y conocimiento histórico del sistema.

Parte de esas necesidades contribuyeron posteriormente al desarrollo de **Living Memory**.

---

## Relación con Living Memory

Lexidiam y Living Memory representan dos capas diferentes de un mismo problema.

**Lexidiam** es un producto profesional donde aparecen necesidades reales de privacidad, soberanía, trazabilidad y evolución controlada.

**Living Memory** nació posteriormente como una exploración más general sobre cómo mantener conocimiento técnico verificable y conectado con sistemas que cambian continuamente.

```text
Lexidiam
   ↓
Sistema complejo en evolución
   ↓
Problemas de documentación y gobernanza
   ↓
Necesidad de memoria verificable
   ↓
Living Memory
```

[Conocer Living Memory](https://github.com/gonuzzz-collab/living-memory-public)

---

## Estado actual

**Proyecto:** Lexidiam  
**Estado:** desarrollo activo  
**Tipo:** plataforma profesional de transcripción y revisión  
**Modelo de procesamiento:** principalmente local  
**Modelo de publicación:** descripción pública / implementación propietaria

El código fuente, la documentación operativa sensible y determinados mecanismos internos permanecen privados.

---

## Publicación selectiva

Este repositorio no constituye una publicación open source de Lexidiam.

Funciona como documentación profesional del producto y de sus principios de ingeniería.

Puede incluir progresivamente:

- arquitectura conceptual;
- capturas de interfaz seleccionadas;
- demostraciones;
- documentación de producto;
- evidencia técnica sanitizada;
- decisiones de diseño de alto nivel.

No incluye mecanismos cuya publicación pudiera revelar detalles sensibles sobre seguridad, custodia, autorización, recuperación o infraestructura interna.

---

## Dirección

Lexidiam continúa evolucionando alrededor de cuatro ideas centrales:

**privacidad · soberanía · revisión humana · trazabilidad**

El objetivo no es solamente producir transcripciones mediante IA.

El objetivo es construir un flujo profesional en el que la inteligencia artificial pueda asistir intensivamente sin eliminar la responsabilidad humana ni el control sobre la información.

---

## Autor

**Patricio Castillo**

Arquitectura y gobernanza de sistemas asistidos por IA · Agentes · Soberanía de datos · Documentación viva

Desarrollado bajo **GoNucleo IA**, laboratorio tecnológico independiente.

[Portafolio profesional](https://github.com/gonuzzz-collab/mi-portafolio)

---

*Lexidiam es una exploración continua de transcripción profesional, soberanía de datos, revisión humana y flujos asistidos por IA bajo control.*

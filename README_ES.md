# PRISM - Sistema de Perfilado Psicológico de Amenazas Persistentes Avanzadas (APT)

## Descripción General

PRISM es un sistema integral de perfilado psicológico para grupos de Amenazas Persistentes Avanzadas (APT) que combina marcos de evaluación psicológica con inteligencia de amenazas cibernéticas. El sistema proporciona análisis detallado de comportamiento, recomendaciones de defensa y perfiles operacionales para grupos APT principales basados en rasgos psicológicos y patrones de ataque.

## Estructura del Repositorio

```
PRISM/
├── aptGroups/           # Perfiles de grupos APT y análisis de clusters
│   ├── aptGroupsEN.json     # Perfiles de grupos APT en inglés
│   ├── aptGroupsES.json     # Perfiles de grupos APT en español
│   ├── aptGroupsSources.json # Fuentes y referencias de grupos APT
│   ├── ClusterProfileEN.json # Perfiles de clusters en inglés
│   └── ClusterProfileES.json # Perfiles de clusters en español
└── base/               # Marco psicológico base
    ├── baseAdviceEN.json     # Marco de consejos psicológicos en inglés
    └── baseAdviceES.json     # Marco de consejos psicológicos en español
```

## Componentes Principales

### 1. Perfiles de Grupos APT (`aptGroups/`)

Cada perfil de grupo APT contiene:
- **Información Básica**: ID, nombre, fecha de última actualización, versión
- **Resumen**: Descripción detallada de las actividades y características del grupo
- **Etiquetas de Perfil de Objetivos**: Sectores y organizaciones típicamente atacadas
- **Evaluación Psicológica**:
  - **Rasgos de Personalidad Big Five**: Apertura, Responsabilidad, Extraversión, Amabilidad, Neuroticismo
  - **Rasgos de la Tétrada Oscura**: Maquiavelismo, Narcisismo, Psicopatía, Sadismo
- **Recomendaciones**: Estrategias de defensa y técnicas de mitigación
- **Casos de Referencia**: Incidentes y campañas notables

### 2. Perfiles de Clusters (`ClusterProfileES.json`)

Agrupa organizaciones APT en clusters psicológicos:
- **Innovadores Manipuladores Silenciosos**: Grupos enfocados en sigilo (APT29, APT38)
- **Innovadores Manipuladores Ruidosos/Narcisistas**: Grupos de alta visibilidad (APT28, APT44)
- **Innovadores Manipuladores Equilibrados**: Grupos híbridos (APT41)

Cada cluster incluye:
- Perfil psicológico macro
- Rasgos de personalidad centrales
- Características operacionales
- Estrategias de defensa específicas

### 3. Marco Psicológico (`base/`)

Proporciona el sistema de evaluación psicológica fundamental:
- **Indicadores de Rasgos**: Manifestaciones conductuales de cada rasgo de personalidad
- **Recomendaciones de Defensa**: Estrategias de mitigación específicas para cada nivel de rasgo
- **Sistema de Puntuación**: Escala 1-5 para cada dimensión psicológica

## Marco de Evaluación Psicológica

### Rasgos de Personalidad Big Five

1. **Apertura (1-5)**: Innovación y adaptabilidad en TTPs
2. **Responsabilidad (1-5)**: Planificación y disciplina operacional
3. **Extraversión (1-5)**: Patrones de comunicación y visibilidad
4. **Amabilidad (1-5)**: Selección de objetivos y metodología de ataque
5. **Neuroticismo (1-5)**: Respuesta a la detección y estrés operacional

### Rasgos de la Tétrada Oscura

1. **Maquiavelismo (1-5)**: Capacidades de manipulación y engaño
2. **Narcisismo (1-5)**: Necesidad de reconocimiento y visibilidad
3. **Psicopatía (1-5)**: Tolerancia al riesgo y agresión operacional
4. **Sadismo (1-5)**: Comportamiento destructivo y daño colateral

## Casos de Uso

- **Inteligencia de Amenazas**: Comprender motivaciones y comportamientos de grupos APT
- **Planificación de Defensa**: Adaptar estrategias de seguridad a perfiles de amenazas específicos
- **Respuesta a Incidentes**: Predecir comportamiento del atacante durante incidentes activos
- **Evaluación de Riesgos**: Evaluar riesgo organizacional basado en perfiles de actores de amenazas
- **Entrenamiento de Seguridad**: Educar equipos sobre aspectos psicológicos de amenazas cibernéticas

## Grupos APT Soportados

El sistema actualmente perfila grupos APT principales incluyendo:
- APT29 (Cozy Bear / The Dukes)
- APT28 (Fancy Bear / Sofacy / Pawn Storm)
- APT38 (subgrupo de Lazarus)
- APT41 (Barium / Winnti)
- APT44 (Sandworm Team)

## Idiomas

El repositorio proporciona contenido en versiones en inglés y español para todos los archivos principales, permitiendo uso internacional y colaboración.

## Contribuciones

Este sistema está diseñado para ser extensible. Se pueden agregar nuevos grupos APT siguiendo el esquema JSON establecido, y las evaluaciones psicológicas se pueden actualizar basándose en nueva inteligencia y análisis conductual.

## Licencia

[Agregar información de licencia apropiada]

## Contacto

[Agregar información de contacto para mantenedores]

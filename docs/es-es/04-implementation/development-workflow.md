# 04 - Implementación

## 4.4 Flujo de Desarrollo

Describe cómo avanza el trabajo de principio a fin dentro del equipo, más allá de simples reglas aisladas. Conecta el código, branches, la revisión y la entrega.

Por lo general, incluye elementos como:

4.4.1. Estrategia de Branches

> Cómo se organizan branches en el repositorio:

	main / master → producción
	develop → integración
	feature/* → nuevas funcionalidades
	hotfix/* → correcciones urgentes
	release/* → preparación de lanzamientos

4.4.2. Ciclo de vida de una funcionalidad

> Describe el flujo de trabajo típico:

	Crear branch desde develop o main
	Desarrollar la funcionalidad
	Abrir Pull Request
	Revisión de código
	Aprobación
	Merge
	Deploy (CI/CD)

4.4.3. Proceso de Pull Request

> Reglas para los PR:

	Tamaño ideal del PR (p. ej., pequeño y enfocado)
	Número mínimo de revisores
	Lista de verificación antes de abrir un PR
	Requisito de pruebas automatizadas

4.4.4. Pautas para la revisión de código

> Qué se debe evaluar:

	Legibilidad del código
	Arquitectura
	Rendimiento
	Seguridad
	Estandarización

4.4.5. Estrategia de versionado

> Si el proyecto utiliza versionado:

	Versionado semántico (Semantic Versioning)
	MAJOR.MINOR.PATCH
	1.0.0 → cambios que rompen la compatibilidad
	1.1.0 → nuevas funcionalidades
	1.1.1 → corrección de errores

4.4.6. Flujo de CI/CD

> Cómo llega el código a producción:

	Build automatizado
	Pruebas automatizadas
	Análisis estático (linting)
	Deploy en entorno de pruebas (staging)
	Deploy en producción

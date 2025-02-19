# Plantillas de Workflow para JAG MEDIA

Este directorio contiene plantillas estandarizadas de GitHub Actions workflows para todos los repositorios de la organización.

## Workflows Disponibles

### 1. Standard CI (`standard-ci.yml`)

Configuración estándar de Integración Continua que incluye:

- Linting de código
- Ejecución de pruebas
- Verificación de documentación

### 2. Issue Automation (`issue-automation.yml`)

Automatización de issues y pull requests:

- Triaje automático
- Etiquetado basado en contenido
- Integración con proyectos

## Uso

1. Copia el workflow deseado a tu repositorio en `.github/workflows/`
2. Ajusta las configuraciones según necesites
3. El workflow usará automáticamente el PAT_TOKEN de la organización

## Configuración

Todos los workflows están configurados para usar el `PAT_TOKEN` de la organización, que proporciona:

- Acceso a repositorios
- Permisos de escritura para issues/PRs
- Integración con proyectos

## Mantenimiento

Para modificar estas plantillas:

1. Crea un PR en este repositorio
2. Obtén aprobación del equipo
3. Actualiza la documentación según sea necesario

## Contacto

Para preguntas o problemas:

- Email: <info@jagmedia.com.ve>

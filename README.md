# Zed Config

Configuración personalizada del editor de código Zed con ajustes optimizados para desarrollo y reglas de programación.

## Descripción

Este repositorio contiene la configuración personalizada del editor Zed, incluyendo:

- **`Settting.json`**: Archivo de configuración principal del editor Zed
- **`rules.md`**: Reglas y principios de programación a seguir durante el desarrollo

## Características de la Configuración

### Personalización Visual
- **Fuente**: `.ZedMono` con tamaño de 17px
- **Tema**: `Andromeda Dark` (modo claro y oscuro)
- **Iconos**: `Monospace Icon Theme - Dark`
- **Altura de línea**: 1.5 para mejor legibilidad

### Comportamiento del Editor
- **Autoguardado**: Cada 500ms
- **Auto indentación**: Activada al pegar y escribir
- **Soft wrap**: Ajuste al ancho del editor
- **Hard tabs**: Activados con tamaño de 4 espacios
- **Minimap**: Siempre visible

### Optimizaciones de Rendimiento
- **Telemetría**: Desactivada (diagnósticos y métricas)
- **Inlay hints**: Desactivados
- **Predictions**: Desactivadas
- **Popovers**: Configurados para minimizar interrupciones

### Paneles y UI
- **Panel de proyecto**: Configurado para mostrar siempre, con git status y diagnósticos
- **Barra de estado**: Posición del cursor oculta, lenguaje activo visible
- **Barra de pestañas**: Con git status e iconos de archivo
- **Terminal**: Fuente de 14px, cursor tipo barra

### Integraciones
- **Prettier**: Permitido para formateo
- **Git**: Inline blame desactivado
- **Agente IA**: Configurado con modelo GPT-4.1 de OpenAI

## Reglas de Programación

El archivo `rules.md` contiene 44 reglas que guían el desarrollo de software, enfocadas en:

### Principios Fundamentales
- Principio KISS (Keep It Simple, Stupid)
- Código legible sobre código ingenioso
- Evitar sobreingeniería
- Implementar solo lo necesario

### Calidad del Código
- Nombres de variables descriptivos
- Funciones pequeñas con responsabilidades únicas
- Comentarios solo cuando es necesario
- Consistencia con el código existente

### Manejo de Errores y Seguridad
- Manejo de errores en operaciones críticas
- Validación de entradas
- Prácticas seguras (prevención de inyección SQL, XSS)
- Nunca exponer credenciales

### Desarrollo y Testing
- Código incremental y testeable
- Verificación de casos límite
- Testing con datos reales
- Documentación clara

## Instalación

1. Clona este repositorio
2. Copia el archivo `Settting.json` a tu configuración de Zed
3. Revisa las reglas en `rules.md` y adáptalas a tus necesidades

## Configuración del Agente IA

El agente está configurado para usar:
- **Proveedor**: OpenAI
- **Modelo**: gpt-4.1
- **Perfil**: minimal

## Notas

- La configuración prioriza la productividad y minimiza interrupciones
- Los ajustes están optimizados para desarrollo continuo
- Las reglas promueven código mantenible y seguro

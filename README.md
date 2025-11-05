# MCPWeather

Este proyecto utiliza el protocolo MCP (Model Context Protocol) para gestionar un servidor que procesa peticiones relacionadas con el clima.

## Descripción

El servidor MCP está diseñado para manejar solicitudes y respuestas relacionadas con datos meteorológicos. Está configurado para ejecutarse utilizando `tsx` y puede ser probado fácilmente con el inspector de MCP.

## Uso del Inspector de MCP

Para probar el servidor y visualizar las peticiones y respuestas, puedes utilizar el inspector de MCP. Esto te permitirá depurar y verificar el comportamiento del servidor.

### Comando para levantar el inspector:

```bash
npx -y @modelcontextprotocol/inspector npx -y tsx main.ts
```

### ¿Qué hace este comando?

1. **`@modelcontextprotocol/inspector`**: Inicia el inspector de MCP, que actúa como una herramienta de depuración.
2. **`tsx main.ts`**: Ejecuta el servidor definido en el archivo `main.ts`.

El inspector te permitirá observar las peticiones que llegan al servidor y las respuestas que este genera.

## Requisitos

- **Node.js**: Asegúrate de tener una versión de Node.js compatible (16.14.0 o superior).
- **Dependencias**: Instala las dependencias necesarias ejecutando:
  ```bash
  npm install
  ```

## Ejecución del Servidor

Si solo deseas ejecutar el servidor sin el inspector, utiliza el siguiente comando:

```bash
npx tsx main.ts
```

## Notas

- Asegúrate de que el archivo `mcp.json` esté correctamente configurado para definir los servidores MCP.
- Si encuentras problemas con el inspector o el servidor, verifica que las dependencias estén instaladas y que estés utilizando una versión compatible de Node.js.

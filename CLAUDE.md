# Adri

Proyecto React + TypeScript + Vite generado con Lovable.

## Stack

- **Framework**: React 18 + TypeScript
- **Build**: Vite
- **Estilos**: Tailwind CSS + shadcn/ui (Radix UI)
- **Routing**: React Router DOM v6
- **Tests**: Vitest + Testing Library

## Comandos

```bash
npm install      # Instalar dependencias
npm run dev      # Servidor de desarrollo
npm run build    # Build de producción
npm run lint     # Linter (ESLint)
npm run test     # Tests (Vitest)
```

## Estructura

```
src/
  App.tsx          # Componente raíz
  main.tsx         # Punto de entrada
  index.css        # Estilos globales (Tailwind)
  setupTests.ts    # Setup de Vitest
```

## Alias de paths

Usa `@/` para importar desde `src/`. Ejemplo: `import { Button } from '@/components/ui/button'`

## Integración Lovable + Claude Code

Este repositorio está conectado con Lovable (lovable.dev). Los cambios se sincronizan bidireccionalmente vía GitHub.

- **Lovable**: ideal para cambios de UI rápidos y prototipado
- **Claude Code**: ideal para lógica compleja, refactoring y arquitectura

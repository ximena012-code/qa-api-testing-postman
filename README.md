# QA API Testing — Postman

Colección de **pruebas de API** con Postman (estilo Sofka / QA Automatizador).

## Qué incluye
- Colección JSON importable en Postman
- Casos: GET list, GET by id, POST create, validación de status y schema básico
- Guía de ejecución manual y con Newman

## Importar
1. Abre Postman → Import
2. Selecciona `postman/JSONPlaceholder_API_Tests.postman_collection.json`

## Correr con Newman
```bash
npx newman run postman/JSONPlaceholder_API_Tests.postman_collection.json
```

## Herramientas relacionadas
Postman · Newman · (equivalente conceptual a RestAssured / Karate en CI)

## Autora
[Ximena Sarrazola](https://github.com/ximena012-code)

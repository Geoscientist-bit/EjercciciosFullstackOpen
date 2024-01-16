## Descripción
Se pretende dar solución a cada uno de los ejercicios propuestos

## Flujograma
Se presenta el flujo de la información del archivo ejemplo

```mermaid
sequenceDiagram
    Browser->>+Server: HTTP GET https://fullstack-exampleapp.herokuapp.com
    Server-->>+Browser: HTML, code
    Browser->>+Server: HTTP GET https://fullstack-exampleapp.herokuapp.com/kuva.png
    Server-->>+Browser: image
    Browser->>+Server: HTTP GET https://fullstack-exampleapp.herokuapp.com/favicon.ico
    Server-->>+Browser: favicon
```
## Tecnologías
<ul>
  <li>HTML</li>
  <li>CSS</li>
  <li>JavaScript</li>
  <li>NodeJS</li>
</ul>

# Instituto Tecnológico Horizonte Digital

Sitio web informativo del instituto, desarrollado con HTML5 y versionado con Git.

## Estructura

```
horizonte-digital/
├── index.html            Página principal
├── nosotros.html         Misión, visión y valores
├── README.md
├── pages/
│   ├── oferta.html       Oferta académica (lista anidada y tabla)
│   └── contacto.html     Información de contacto
└── recursos/
    ├── imagenes/
    │   ├── campus-principal.jpg
    │   └── laboratorio.jpg
    └── documentos/
        └── reglamento-academico.pdf
```

## Ramas

| Rama | Propósito |
|---|---|
| main | Rama principal con la estructura inicial |
| feature/programador1 | index.html y nosotros.html |
| feature/programador2 | pages/oferta.html y pages/contacto.html |
| desarrollo | Integración de ambos programadores |
| pruebas | Versión consolidada para verificación |

## Cómo abrirlo

1. Abrir la carpeta `horizonte-digital` en Visual Studio Code.
2. Abrir `index.html` en el navegador (o usar la extensión Live Server: clic derecho > "Open with Live Server").
3. Ver el historial: `git log --oneline --graph --all`.

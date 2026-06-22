# 📊 Seguimiento de Objetivos IIEE

Visualizador web para el seguimiento anual de objetivos estratégicos, líneas de acción, avance general y matriz de riesgo del IIEE.

## 🚀 Publicación

El archivo principal es:

```text
index.html
```

Para publicarlo en GitHub Pages:

1. Subir `index.html` y este `README.md` al repositorio.
2. Ir a **Settings > Pages**.
3. En **Build and deployment**, seleccionar la rama correspondiente.
4. Guardar la configuración.
5. Abrir la URL pública que genere GitHub Pages.

## 👁️ Vista pública

El enlace normal abre una vista simple para todo el personal del IIEE:

```text
[https://usuario.github.io/repositorio/](https://usuario.github.io/repositorio/)
```

Incluye:

- KPI radial de avance promedio total.
- Cantidad de objetivos, tareas y riesgos altos.
- Matriz de riesgo tipo semáforo.
- Objetivos estratégicos y líneas de acción en desplegables.


## 💾 Persistencia de datos

Los cambios se guardan en el navegador mediante `localStorage`.

Esto significa que:

- Los cambios se reflejan entre pestañas del mismo navegador.
- No requiere servidor ni base de datos.
- Si se usa desde distintos dispositivos o navegadores, cada uno tendrá su propia copia local.

## 📁 Estructura mínima

```text
.
├── index.html
└── README.md
```

## 🧭 Uso recomendado

- Compartir el enlace normal para consulta general.
- Usar `?modo=editar` solo para quienes actualicen el seguimiento.
- Exportar informes desde el modo edición cuando sea necesario.


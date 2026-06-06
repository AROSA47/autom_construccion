# 🏗️ 01 · Preparación de la Obra

**Del PDF a la Automatización de Obras con Herramientas Open Source**

La fase de preparación es crítica: recibimos documentación, la entendemos, la ordenamos y la convertimos en información útil para tomar decisiones.  
Este repositorio organiza esta etapa en tres niveles de digitalización:

- [Nivel Básico](ca://s?q=explicar_nivel_basico_preparacion_obra)
- [Nivel Intermedio](ca://s?q=explicar_nivel_intermedio_preparacion_obra)
- [Nivel Avanzado](ca://s?q=explicar_nivel_avanzado_preparacion_obra)

---

## 🎯 Objetivo

Transformar la documentación recibida en **información estructurada**, útil y accesible.

Preguntas clave:

- ¿Qué voy a construir?
- ¿Dónde están los riesgos?
- ¿Qué partidas son críticas?
- ¿Qué proveedores necesitaré?
- ¿Qué plazo tengo?
- ¿Qué condicionantes existen?

Documentación habitual:

- Memoria
- Planos
- Presupuesto
- Mediciones
- Pliego
- Contrato
- Estudio de Seguridad
- Geotécnico
- Licencias

---

# 📂 Estructura del repositorio

01_preparacion_obra/
│
├── basico/
│ ├── extraer_pdf/
│ ├── checklist_documentacion/
│ ├── resumen_obra/
│ └── matriz_riesgos/
│
├── intermedio/
│ ├── pdf_to_csv/
│ ├── indexador_documentos/
│ ├── buscador_documental/
│ └── dashboard_documentacion/
│
└── avanzado/
├── rag_documental/
├── sqlite/
├── llm_local/
└── asistente_jefe_obra/

Cada carpeta incluye:

- `README.md`
- `src/` con código
- Subniveles: **básico**, **intermedio**, **avanzado**

---

# 🟩 Nivel Básico

### Filosofía

**“No programo. Utilizo herramientas gratuitas.”**

### Herramientas open source

- PDF24
- LibreOffice Writer
- LibreOffice Calc
- Trilium Notes
- Xournal++
- Calibre

### Qué se hace

- Leer la memoria en PDF
- Buscar palabras clave (plazo, estructura, riesgos…)
- Crear un resumen en Calc
- Organizar documentación en carpetas
- Crear una matriz de riesgos inicial

### Flujo

1. Abrir memoria con PDF24
2. Buscar palabras clave
3. Copiar información relevante a Calc
4. Crear ficha resumen:

---

# 🟧 Nivel Intermedio

### Filosofía

**“Automatizo tareas repetitivas.”**

### Herramientas

- Python
- LibreOffice Calc
- CSV
- Streamlit

### Qué se hace

- Extraer texto de PDF → CSV
- Crear base documental indexada
- Buscar información sin abrir el PDF
- Relacionar capítulos, partidas y páginas

### Ejemplos

#### PDF → CSV

Columnas:

- Documento
- Página
- Capítulo
- Texto
- Importancia
- Categoría

#### Base documental en Calc

#### Streamlit

Buscar:

- “hormigón”
- “plazos”
- “accesos”
- “saneamiento”

---

# 🟥 Nivel Avanzado

### Filosofía

**“Convierto la documentación en una base de conocimiento.”**

### Herramientas

- Python
- SQLite
- LLM local (Ollama)
- Streamlit
- Blender + GIS
- QGIS

### Qué se hace

- Crear base SQLite del proyecto
- Generar embeddings
- Consultar documentación con IA
- Relacionar memoria, planos y presupuesto
- Automatizar escenas en Blender
- Crear dashboards avanzados

### Flujo completo

Ejemplos de preguntas:

- ¿Qué partidas tienen más riesgo?
- ¿Cuál es el plazo contractual?
- ¿Dónde se menciona el HA-30?
- ¿Qué suministros debo contratar?

---

# 🧠 Filosofía general

La progresión no es tecnológica:  
es una progresión de **madurez digital**.

| Nivel | Cómo trabaja |
| --- | --- |
| **Básico** | Lee documentos |
| **Intermedio** | Indexa documentos |
| **Avanzado** | Consulta conocimiento |

Esto permite repetir la misma estructura en todas las fases:

01_preparacion_obra/
02_arranque/
03_compras/
04_control_economico/
05_produccion/

Cada una con:

- basico/
- intermedio/
- avanzado/

---

#

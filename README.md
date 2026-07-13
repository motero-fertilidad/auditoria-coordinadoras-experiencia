# Auditoría · Coordinadoras de Experiencia · Fertilidad Integral

Dashboard semanal de auditoría para coordinadoras de experiencia. Mide conversión, add-ons y experiencia del paciente.

---

## Cómo configurar (una sola vez)

### 1. Crear el repositorio en GitHub
1. Ve a [github.com](https://github.com) → **New repository**
2. Nombre: `auditoria-coordinadoras` · Visibilidad: **Public**
3. Marca "Add a README file" → Create repository

### 2. Activar GitHub Pages
1. Settings → Pages → Branch: **main** / folder: **/ (root)** → Save
2. Tu URL quedará: `https://TU-USUARIO.github.io/auditoria-coordinadoras/`

### 3. Subir los archivos
1. Add file → Upload files
2. Sube `index.html` y este `README.md`
3. Commit changes

### 4. Compartir el Google Sheet de IT
El dashboard lee automáticamente el Google Sheet de IT.
Verifica que esté compartido como **"Cualquiera con el enlace puede ver"**:
- Sheet → Compartir → Cambiar a → Cualquiera con el enlace → Lector → Listo

---

## Rutina semanal (cada lunes — 10 minutos)

### Exportar de Vrepro:

**Archivo 1: Citas**
- Vrepro → Agenda → Exportar
- Filtro: semana completa (lunes a domingo)
- Guardar como: `citas.xlsx`

**Archivo 2: Cargos**
- Vrepro → Facturación → Cargos → Exportar
- Filtro: misma semana
- Guardar como: `cargos.xlsx`

### Usar el dashboard:
1. Abre tu URL de GitHub Pages
2. Haz clic en **"📂 Cargar Citas"** → selecciona `citas.xlsx`
3. Haz clic en **"📂 Cargar Cargos"** → selecciona `cargos.xlsx`
4. El dashboard se actualiza automáticamente

> Los archivos solo se cargan en tu navegador. Nadie más los ve a menos que los subas a GitHub.

---

## KPIs que mide el dashboard

| KPI | Fuente | Descripción |
|---|---|---|
| **Conversión** | Citas | Primera vez → Captura ovular |
| **Add-ons** | Cargos | HAM/PAP en Gine, Óvulos FI, Vitrificación desde Gine, Suplementos |
| **Experiencia · Expediente** | Google Sheet IT | Demog + Contacto + CP + Clasificación completos |
| **Experiencia · Plática** | Citas | Primera vez con estudio → Plática registrada en Vrepro |

## Coordinadoras auditadas
Viviana · Reyna · Jimena · Lucy · Sharon · Andrea

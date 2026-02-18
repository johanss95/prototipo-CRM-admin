# Design System Synaptek - Configuración para Prototipos

## ✅ VERIFICADO

Este archivo `tailwind.config.js` contiene **EXACTAMENTE** los mismos valores de tu Design System en Figma:

- ✅ **23 paletas de colores** (con tus valores específicos)
- ✅ **35 valores de spacing**
- ✅ **10 valores de border radius**
- ✅ **14 tamaños de fuente**
- ✅ **5 breakpoints**
- ✅ **Blur, skew, opacity, width, border-width**

**Colores verificados:**
- Red 500: `#fb2c36` (no el estándar de Tailwind)
- Blue 500: `#2b7fff` (no el estándar de Tailwind)
- Green 500: `#00c951` (no el estándar de Tailwind)
- Purple 500: `#ad46ff` (no el estándar de Tailwind)

---

## 🎯 Cómo usar este archivo

### OPCIÓN A: v0.dev (Vercel)

1. Ve a [v0.dev](https://v0.dev)
2. Cuando generes un componente, **SIEMPRE pega esto en tu primer prompt:**

```
Usa esta configuración de Tailwind (Design System de Synaptek):

[pega aquí el contenido completo de tailwind.config.js]

Genera el componente con estos colores y espaciados exactos.
```

3. v0.dev respetará tus valores

**⚠️ Importante:** Debes pegar el config en **cada nueva sesión** porque v0.dev no tiene memoria.

---

### OPCIÓN B: Replit (Recomendado para proyectos completos)

1. Crea un nuevo proyecto en [Replit](https://replit.com)
2. Selecciona template: **Next.js**
3. Reemplaza el archivo `tailwind.config.js` con este
4. Ahora **TODOS** los componentes que generes usarán tu DS automáticamente

**Ventaja:** No tienes que pegar el config cada vez.

---

### OPCIÓN C: Cursor/Windsurf

1. Crea proyecto local Next.js/React
2. Reemplaza `tailwind.config.js` con este archivo
3. Usa Claude/IA para generar componentes
4. Deploy a Vercel/Netlify para compartir

---

## 📝 Flujo de trabajo recomendado

```
1. Diseñas pantalla en Figma (estático)
2. Capturas screenshot
3. Vas a v0.dev o Replit
4. Pegas el tailwind.config.js (si es v0.dev)
5. Prompt: "Genera este diseño usando el DS de Synaptek"
6. Copias el código generado
7. Pruebas interacciones
8. Compartes link con el equipo
```

**Tiempo estimado:** 2-4 horas (vs 3 días en Figma)

---

## 🔧 Si necesitas actualizar el DS

1. Exporta nuevamente desde Figma con "Variables to Code"
2. Genera nuevo `tailwind.config.js`
3. Reemplaza en tus proyectos

---

## 📦 Archivos incluidos

- `tailwind.config.js` - Configuración completa de Tailwind
- `DS_export.json` - Tokens originales exportados de Figma (respaldo)

---

**Nota:** Estos valores son específicos de Synaptek y NO son los valores estándar de Tailwind CSS.
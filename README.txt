**Restauración técnica:** Clara Harguindey  
**Recuperación de archivos:** Daniel Pecharromán y Clara Harguindey (Desmusea)
**Proyecto original:** Marisa González

### **HTML**
- Convertido de HTML4 a **HTML5** válido
- DOCTYPE moderno `<!DOCTYPE html>`
- Atributo `lang="es"` añadido
- Meta viewport para móviles
- Encoding **UTF-8** (antes ISO-8859-1)
- Atributos `alt` en todas las imágenes
- Eliminados atributos obsoletos: `bgcolor`, `topmargin`, `leftmargin`, `marginwidth`, `marginheight`

### **CSS**
- Etiquetas `<font>` obsoletas → **clases CSS**
- Estilos inline → **hojas de estilo internas**
- **Colores originales respetados** exactamente
- **Fuentes originales preservadas** (Arial, Verdana)
- **Tamaños exactos** mantenidos (size 2/3/4 → 10pt/12pt/13.5pt)
- CSS3 animations para animaciones (reemplazan JavaScript)
- Sin responsive (diseño fijo a petición)

### **JavaScript**
- Eliminado código **Macromedia Timeline** (200+ líneas obsoletas)
- Eliminado `eval()` inseguro
- `var` → **let/const** (ES6)
- `window.status` → **barra de scroll visible**
- Funciones modernizadas pero funcionalidad preservada
- Event listeners modernos

### **Animaciones**
- JavaScript Timeline → **CSS @keyframes**
- GPU-accelerated (mejor rendimiento)
- 60fps en lugar de 12fps
- Timing y secuencia originales preservados
- Solo en 1 archivo (el resto sin animación como original)

### **Compatibilidad**
- Chrome, Firefox, Safari, Edge (últimas versiones)
- ❌ NO Internet Explorer
- GitHub Pages compatible
- Servidores estáticos estándar

### **Codificación**
- UTF-8 universal
- Acentos españoles corregidos (á, é, í, ó, ú, ñ)
- Caracteres especiales corregidos

### **Estructura**
- Semántica mejorada (manteniendo layout original)
- Comentarios HTML para evitar espacios entre imágenes
- Rutas relativas limpias (sin `./` innecesario)
- Enlaces internos preservados

### **Accesibilidad básica**
- Atributos `alt` descriptivos
- Estructura HTML semántica
- ⚠️  Contraste de colores original mantenido (no optimizado)

### **Optimización**
- Código limpio y legible
- Sin JavaScript innecesario
- CSS eficiente
- Sin dependencias externas

### **Preservado del original**
- Layout con tablas (estilo años 90)
- Paleta de colores exacta
- Tipografía idéntica
- Diseño visual 100% fiel
- Funcionalidad equivalente o mejorada
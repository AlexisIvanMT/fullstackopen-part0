# Parte 0: Diagramas de flujo de red

Este directorio contiene los ejercicios **0.4, 0.5 y 0.6** de la **Parte 0** del curso [Full Stack Open](https://fullstackopen.com/es/) de la Universidad de Helsinki.

Los ejercicios exploran el comportamiento de las aplicaciones web tradicionales frente a las aplicaciones de una sola página (SPA), mediante diagramas de secuencia en sintaxis **Mermaid**.

## 📌 Ejercicios

### **0.4: Nuevo diagrama de nota**  
Diagrama que describe el flujo de red cuando un usuario crea una nueva nota en la aplicación **tradicional** (`/notes`).  
- Se muestra el envío del formulario (`POST`), la redirección del servidor (`302`), y la recarga completa de la página.

### **0.5: Diagrama de aplicación de una sola página (SPA)**  
Diagrama que representa la carga inicial de la versión **SPA** (`/spa`).  
- Se carga un HTML estático, luego se obtienen los recursos estáticos (`CSS`, `JS`) y finalmente los datos (`data.json`) mediante `fetch`.  
- **No hay recarga de página**: la UI se construye dinámicamente con JavaScript.

### **0.6: Nueva nota en diagrama de SPA**  
Diagrama que muestra la creación de una nueva nota en la versión **SPA**.  
- El formulario se envía mediante `fetch` (`POST` a `/new_note_spa`).  
- El servidor responde con el objeto creado en formato JSON.  
- La UI se actualiza **sin recargar la página**.

---

> 💡 Todos los diagramas están escritos en **sintaxis Mermaid** y se renderizan automáticamente en GitHub.
>
> 📚 Fuente: [https://studies.cs.helsinki.fi/exampleapp/](https://studies.cs.helsinki.fi/exampleapp/)

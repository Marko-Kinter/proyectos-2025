### **Situación problema**
Una tienda de artículos de oficina quiere mejorar la gestión de su inventario. Actualmente, el registro de productos y movimientos de inventario se realiza manualmente en hojas de cálculo, lo que ocasiona los siguientes problemas:  
1. **Errores humanos frecuentes** al registrar entradas y salidas.  
2. **Falta de visibilidad del stock en tiempo real**, lo que lleva a desabastecimientos o exceso de productos.  
3. **Dificultad para generar reportes** de ventas e inventario para la toma de decisiones.  

El dueño de la tienda desea implementar un sistema digital que facilite el control de inventarios, automatice ciertas tareas y permita consultar información de manera rápida y confiable.

---

### **Requerimientos del cliente**
#### **Requerimientos funcionales**  
1. Registrar productos con campos básicos como nombre, descripción, categoría, precio unitario y stock actual.  
2. Registrar movimientos de inventario (entradas y salidas) asociados a cada producto.  
3. Permitir consultar el stock actual de un producto por nombre o categoría.  
4. Generar reportes mensuales con:  
   - Productos más vendidos.  
   - Productos con bajo stock.  

#### **Requerimientos no funcionales**  
1. El sistema debe ser **intuitivo y fácil de usar** para empleados sin experiencia técnica.  
2. Debe responder rápidamente a las consultas, incluso con más de 1,000 productos registrados.  
3. El sistema debe ser **escalable**, permitiendo agregar nuevos productos y categorías sin necesidad de reconfiguraciones mayores.  

#### **Restricciones del cliente**  
1. El sistema debe funcionar en computadoras con Windows y sin necesidad de conexión a internet.  
2. Se debe priorizar el uso de software de bajo costo o gratuito (e.g., SQLite en lugar de bases de datos avanzadas).  

---

¿Te parece bien este planteamiento? ¡Avísame si necesitas ajustar algo! 😊
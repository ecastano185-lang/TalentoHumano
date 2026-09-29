1. ¿Tuviste que modificar calcularTotalNomina() para que incluyera a los comerciales?
2. no
3. ¿Por qué no?
4. no fue necesario modificar calcularTotalNomina(). Esto es posible gracias al polimorfismo. El método recorre los empleados y llama a calcularSalarioTotal() de cada uno.
5. ¿Qué concepto de POO lo hizo posible?
6. Como EmpleadoComercial sobrescribe ese método, Java ejecuta automáticamente el cálculo correspondiente al empleado Comercial, incluyendo su comisión


7. ¿Cuántos archivos de la capa modelo modificaste (no creaste)?
8. modifique 0 archivos existentes, solamente cree el nuevo archivo EmpleadoComercial.java
9. ¿Qué te dice eso sobre MVC?
10. que permite separar las responsabilidades del programa. Para agregar el nuevo tipo de empleado, los cambios principales se hicieron en el nuevo modelo y en las capas Controlador y Vista, sin tener que modificar los modelos existentes.

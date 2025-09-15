# Appde-Belleza_
Plataforma para personas interesadas en mejorar su estética personal de manera sencilla y personalizada. 
 ![belleza](https://zonales.quito.gob.ec/wp-content/uploads/maquillaje-y-maquillaje-profesional-1-scaled-1.jpg)

 # INTRODUCCIÓN
Bienvenidos a nuestra App-de-Belleza estamos encantados de presentarte una herramienta creada especialmente para realzar tu estilo y cuidar de tu imagen personal. En nuestra app, encontrarás una amplia galería de peinados y maquillajes, tutoriales prácticos para aprender nuevas técnicas, y la opción de agendar citas con estilistas de manera rápida y sencilla.

# PROPÓSITO
El propósito de mi app de belleza es ofrecer una experiencia personalizada para el cuidado y mejora de la apariencia, brindando recomendaciones, productos y servicios adaptados a las necesidades de cada usuario.

# OBJETIVOS
**Objetivos de mi app de belleza:**  
1. **Personalización** – Ofrecer recomendaciones y servicios adaptados a cada usuario según sus necesidades y preferencias.  
2. **Accesibilidad** – Facilitar el acceso a productos y servicios de belleza en un solo lugar.  
3. **Interactividad** – Permitir a los usuarios interactuar con expertos y recibir asesoría personalizada.  
4. **Innovación** – Integrar herramientas tecnológicas como inteligencia artificial para mejorar la experiencia del usuario.  
5. **Comunidad** – Fomentar una comunidad donde los usuarios puedan compartir experiencias, consejos y opiniones.

# CONTEXTO DEL PROBLEMA
El sector de la belleza y el peinado enfrenta desafíos relacionados con la personalización y la accesibilidad. Los usuarios a menudo pierden tiempo buscando estilos adecuados o gestionando citas de manera ineficiente. Además, los estilistas enfrentan problemas al organizar su agenda y promocionar sus servicios. Esta app resuelve estos problemas mediante una plataforma centralizada, intuitiva y accesible desde cualquier dispositivo.

# ANALISIS DE REQUERIMIENTO
**Funcionalidades principales:**

- Gestión de clientes

- Registrar, editar, buscar y eliminar clientes.

- Validar que no se repitan correos electrónicos o números de teléfono.

- Gestión de productos

- Agregar nuevos productos (nombre, precio, stock).

- Modificar o eliminar productos existentes.

- Mostrar el inventario completo.

- Gestión de servicios

- Registrar servicios (ejemplo: corte de cabello, manicure, maquillaje).

- Editar o eliminar servicios.

- Gestión de citas

- Agendar citas para un cliente en una fecha y hora específicas.

- Modificar o cancelar citas.

- Validar que no haya conflictos de horario.

- Reportes básicos

- Listar clientes.

- Listar productos con bajo stock.

- Consultar citas por fecha.

# FUNCIONALIDAD CLAVE
Mi app de belleza ofrece un diagnóstico personalizado para recomendar productos y rutinas adaptadas a cada usuario. Permite agendar citas con expertos, probar looks con realidad aumentada y comprar productos en una tienda integrada. Además, brinda un espacio para compartir experiencias y seguir el progreso en el cuidado personal.

# DESCRIPCIÓN DE TABLAS PRINCIPALES

**CLIENTE**

- Propósito: Almacenar información personal de los usuarios que usan los servicios del salón.

- Relevancia: Permite gestionar citas, llevar un historial de clientes y ofrecer servicios personalizados.

- Campos principales: id_cliente, nombre, apellido, telefono, correo.

**PRODUCTO**

- Propósito: Registrar los productos disponibles en la tienda o usados en los servicios (shampoos, cremas, tintes).

- Relevancia: Facilita el control de inventario, precios y disponibilidad de productos para los clientes y servicios.

- Campos principales: id_producto, nombre, precio, stock.

**SERVICIO**

- Propósito: Guardar los servicios que ofrece el salón (corte de cabello, manicure, maquillaje).

- Relevancia: Relaciona los servicios con citas y permite calcular costos y generar reportes.

- Campos principales: id_servicio, nombre, precio, descripcion.

**CITA**

- Propósito: Registrar las reservas de los clientes para un servicio en una fecha y hora específicas.

- Relevancia: Permite organizar la agenda de los estilistas y evitar conflictos de horario.

- Campos principales: id_cita, fecha, hora, id_cliente, id_servicio.

# SCRIPT DE MODELO FISICO
El script crea la base de datos app_belleza y las tablas CLIENTE, PRODUCTO, SERVICIO y CITA, definiendo sus campos, claves primarias y relaciones mediante claves foráneas.
Permite registrar clientes, productos, servicios y citas, asegurando integridad de los datos y facilitando la gestión eficiente de la información en la aplicación.

<img width="1292" height="488" alt="Captura de pantalla 2025-09-09 190836" src="https://github.com/user-attachments/assets/e563c3b0-cc23-4758-8a72-6a73061ab176" />
<img width="987" height="467" alt="Captura de pantalla 2025-09-09 191338" src="https://github.com/user-attachments/assets/ee932b89-5988-4219-b963-482f1c9a7fab" />



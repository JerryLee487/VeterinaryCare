VeterinaryCare - Diagrama de Casos de Uso (UML)

Descripción:
El sistema VeterinaryCare está diseñado para gestionar de forma integral las operaciones diarias de una clínica veterinaria.
Permite agendar citas, llevar historiales médicos de mascotas, gestionar inventario de medicamentos, procesar pagos y administrar personal.
El siguiente diagrama de casos de uso representa las interacciones entre los actores del sistema y sus funcionalidades principales.

👥 Actores principales
Dueño de Mascota: agenda citas, consulta historial médico y realiza pagos.
Veterinario: registra diagnósticos, prescribe tratamientos y actualiza el historial clínico.
Recepcionista: gestiona citas, registra nuevas mascotas y dueños, y procesa pagos.
Administrador del Sistema: administra usuarios, roles, reportes y configuraciones del sistema.
Proveedor de Medicamentos: suministra insumos médicos y recibe órdenes de compra.
Sistema de Facturación: genera facturas y registra transacciones económicas.

⚙️ Módulos del sistema

Citas y Atención
-Registro de nuevas citas.
-Asignación de veterinario y sala de consulta.
-Confirmación y cancelación de citas.
-Historial de visitas por mascota.

Historial Clínico
-Registro de diagnósticos y síntomas.
-Prescripción de medicamentos y tratamientos.
-Registro de vacunas y cirugías.
-Generación de informes médicos.

Inventario y Suministros
-Gestión de stock de medicamentos y materiales.
-Alertas por bajo inventario.
-Creación de órdenes de compra a proveedores.
-Registro de recepción de insumos.

Facturación y Pagos
-Generación de facturas por servicios y productos.
-Registro de pagos (efectivo, tarjeta, transferencia).
-Historial de transacciones por cliente.
-Reportes de ingresos mensuales.

Administración
-Gestión de usuarios y roles (veterinarios, recepcionistas, etc.).
-Configuración de tarifas de servicios.
-Copias de seguridad y auditoría del sistema.
-Generación de reportes operativos y financieros.

🧩 Casos de uso principales
Módulo de Citas y Atención
RF-01: Registrar nueva cita
RF-02: Asignar veterinario y sala
RF-03: Confirmar o cancelar cita
RF-04: Consultar historial de visitas
RF-05: Enviar recordatorios de citas
Módulo de Historial Clínico
RF-06: Registrar diagnóstico médico
RF-07: Prescribir tratamiento o medicamentos
RF-08: Registrar vacunas aplicadas
RF-09: Generar informe clínico
RF-10: Registrar procedimientos quirúrgicos
Módulo de Inventario y Suministros
RF-11: Actualizar stock de medicamentos
RF-12: Generar alerta por bajo inventario
RF-13: Crear orden de compra
RF-14: Registrar recepción de insumos
RF-15: Gestionar catálogo de proveedores
Módulo de Facturación y Pagos
RF-16: Generar factura por servicio
RF-17: Registrar pago de factura
RF-18: Consultar historial de pagos
RF-19: Aplicar descuentos o promociones
RF-20: Generar reporte de ingresos
Módulo de Administración
RF-21: Registrar nuevo usuario del sistema
RF-22: Asignar rol y permisos
RF-23: Configurar tarifas de servicios
RF-24: Realizar copia de seguridad
RF-25: Generar reporte global de operaciones

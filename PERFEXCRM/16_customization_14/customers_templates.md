# Resumen

## 1. **Cambiar la Apariencia del Área del Cliente:**
   - Copiar el tema principal existente de Perfex ubicado en `application/views/themes/` y renombrarlo al nombre deseado, por ejemplo, "flat".

## 2. **Copiar la Carpeta de Activos:**
   - Ir al directorio raíz `assets/themes/` y copiar la carpeta del tema Perfex. Luego, renombrar la carpeta a la que elegiste, como "flat".

## 3. **Configurar el Tema para Clientes:**
   - En el área de administración, dirigirse a Configuración -> Ajustes -> Clientes y cambiar el tema activo de clientes al tema recién creado.

## 4. **Advertencia sobre la Edición del Tema Original:**
   - No se recomienda editar el tema original debido a futuras actualizaciones que podrían sobrescribir todas las modificaciones.

## 5. **Estructura de Carpetas Después de los Cambios:**
   - Después de aplicar los cambios, la estructura de carpetas para el nuevo tema (por ejemplo, "flat") debería ser:
     ```
     assets/themes/flat
     application/views/themes/flat
     ```

## 6. **Archivos Principales de Plantilla:**
   - Los archivos principales que puedes editar son: `head.php`, `footer.php`, `index.php`, y `scripts.php`.

## 7. **Archivos de Tema Disponibles:**
   - Se proporciona una lista de archivos de tema disponibles ubicados en `application/views/themes/yourtheme/views/`.




# Plantillas para Clientes

Si deseas cambiar la apariencia del área del cliente, copia el tema principal existente de Perfex ubicado en `application/views/themes/` y renómbralo con el nombre de tu tema, por ejemplo, flat.

La siguiente parte consiste en copiar la carpeta de activos yendo al directorio raíz `assets/themes/` y copiando el tema Perfex, luego renombra la carpeta a flat, por ejemplo.

Ve al área de administración en Configuración -> Ajustes -> Clientes y cambia el tema activo de clientes a tu tema recién creado.

No se recomienda editar el tema original debido a las actualizaciones que vienen en las próximas versiones y todas tus modificaciones se sobrescribirán.

Después de aplicar los cambios, la estructura de carpetas para tu nuevo tema llamado flat debería verse así:

```
assets/themes/flat
application/views/themes/flat
```

Cuando uses tu propio tema, necesitarás mantenerlo en cada actualización y hacerlo compatible con la última versión.

## Archivos de Plantilla
### Archivos Principales

- `head.php`
- `footer.php`
- `index.php`
- `scripts.php`

### Archivos de Tema Disponibles
Aquí tienes una lista de todos los archivos de tema disponibles ubicados en `application/views/themes/yourtheme/views/` (vistas):

- `announcement.php` – Vista única de anuncio.
- `announcements.php` – Vista de lista de anuncios.
- `calendar.php` – Área del calendario del cliente.
- `company_profile.php` – Información de la empresa.
- `contractpdf.php` – Plantilla PDF de contrato.
- `contracts.php` – Vista de lista de contratos.
- `estimatehtml.php` – Plantilla HTML de estimado.
- `estimatepdf.php` – Plantilla PDF de estimado.
- `files.php` – Área del cliente para cargar archivos en el perfil del cliente.
- `forgot_password.php` – Plantilla de olvido de contraseña del cliente.
- `home.php` – Panel de clientes después de iniciar sesión.
- `invoicehtml.php` – Plantilla HTML de factura.
- `invoicepdf.php` – Plantilla PDF de factura.
- `invoices.php` – Vista de lista de facturas.
- `knowledge_base.php` – Todos los artículos de la base de conocimientos.
- `knowledge_base_article.php` – Artículo único de la base de conocimientos.
- `login.php` – Plantilla de inicio de sesión de contacto.
- `open_ticket.php` – Plantilla de apertura de nuevo ticket.
- `paymentpdf.php` – Plantilla PDF de recibo de pago.
- `profile.php` – Perfil del contacto conectado.
- `project.php` – Proyecto único.
- `proposalpdf.php` – Plantilla PDF de propuesta.
- `proposals.php` – Vista de lista de propuestas.
- `register.php` – Plantilla de registro de contacto/cliente.
- `reset_password.php` – Plantilla de restablecimiento de contraseña.
- `single_ticket.php` – Plantilla de visualización de ticket de contacto.
- `survey_view.php` – Plantilla de encuesta.
- `tickets.php` – Vista de lista de tickets.
- `viewproposal.php` – Plantilla HTML de propuesta.


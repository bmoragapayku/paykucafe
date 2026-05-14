# Payku Movistar Arena

Aplicación estática para gestionar invitaciones a eventos de Movistar Arena usando las mismas credenciales públicas de Supabase del proyecto Payku Café.

## Archivos

- `index.html`: solicitud de entradas y estacionamientos por trabajador.
- `login.html`: acceso administrador para páginas internas.
- `eventos.html`: importador XLSX de eventos y estado cancelado/activo.
- `trabajadores.html`: importador XLSX de nómina, alta manual y eliminación.
- `ranking.html`: ranking de trabajadores por entradas solicitadas.
- `admin.html`: asignación administrativa por mes, cupos, bajas y reubicaciones.
- `supabase-movistar.sql`: tablas, índices y políticas RLS necesarias.

## Instalación

1. Ejecutar `supabase-movistar.sql` en Supabase > SQL Editor.
2. Subir la carpeta `movistar` al hosting estático.
3. Abrir `movistar/index.html`.

Los importadores usan XLSX desde CDN en el navegador; no requieren servidor propio.

## Acceso admin

Las páginas `eventos.html`, `trabajadores.html`, `ranking.html` y `admin.html` requieren login.

- Correo: `andrea@payku.com`
- Contraseña: `Events9649`

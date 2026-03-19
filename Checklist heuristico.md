# Checklist Heurístico – Auditoría UX

## Resultados de la evaluación heurística

| ID | Heurística | Pantalla/Contexto | Descripción del problema | Evidencia | Severidad |
|----|-----------|------------------|--------------------------|----------|-----------|
| H1-A | H1 - Visibilidad del estado del sistema | Login (contraseña incorrecta) | El mensaje de error indica que la contraseña es incorrecta y muestra los intentos restantes, pero no ofrece orientación clara para corregir el error o recuperar el acceso. | flujoA_login_error.jpg | 3 |
| H2-A | H5 - Prevención de errores | Login | No se muestran indicaciones previas sobre los requisitos de la contraseña, lo que aumenta la probabilidad de error al ingresar credenciales. | flujoA_login_validacion.jpg | 2 |
| H3-A | H10 - Ayuda y documentación | Login | No hay acceso directo a ayuda contextual desde la pantalla de error, dificultando la recuperación de la cuenta. | flujoA_login_help.jpg | 2 |
| H4-B | H1 - Visibilidad del estado del sistema | Interfaz principal (saldo) | La pantalla principal muestra el saldo, pero no indica claramente si la información está actualizada o sincronizada en tiempo real. | flujoB_home_saldo.jpg | 2 |
| H5-B | H8 - Diseño estético y minimalista | Interfaz principal | La cantidad de elementos visuales en la pantalla principal puede generar sobrecarga cognitiva y distraer del objetivo principal del usuario. | flujoB_home_ui.jpg | 2 |
| H6-C | H4 - Consistencia y estándares | Movimientos (hoy) | La presentación de transacciones recientes no mantiene consistencia en formato de fechas o descripciones, dificultando la lectura rápida. | flujoC_movimientos_hoy.jpg | 2 |
| H7-C | H6 - Reconocimiento antes que recuerdo | Movimientos | El usuario debe interpretar manualmente el tipo de transacción (envío, recepción) sin suficiente apoyo visual o categorización clara. | flujoC_movimientos_contexto.jpg | 2 |
| H8-D | H1 - Visibilidad del estado del sistema | Más movimientos | No se indica claramente si la lista de movimientos antiguos está cargando o si se han mostrado todos los registros disponibles. | flujoD_movimientos_antiguos.jpg | 2 |
| H9-E | H2 - Relación sistema-mundo real | Servicios | Algunas opciones dentro de la sección de servicios no son completamente intuitivas para usuarios nuevos debido a la terminología utilizada. | flujoE_servicios.jpg | 2 |
| H10-F | H4 - Consistencia y estándares | Servicios principales | Los íconos de funciones principales (enviar, pedir, QR) no siempre son suficientemente descriptivos, lo que puede generar confusión. | flujoF_servicios_principales.jpg | 2 |
| H11-G | H3 - Control y libertad del usuario | Confirmación de envío de dinero | No es evidente cómo cancelar la transacción antes de confirmarla, lo que puede generar inseguridad en el usuario. | flujoG_confirmacion_envio.jpg | 3 |
| H12-H | H1 - Visibilidad del estado del sistema | Notificaciones | No hay una diferenciación suficientemente clara entre notificaciones leídas y pendientes, lo que puede afectar la comprensión del usuario. | flujoH_notificaciones.jpg | 2 |
| H13-I | H6 - Reconocimiento antes que recuerdo | Perfil | Algunas opciones dentro del perfil (documentos, certificados) no tienen descripciones claras, obligando al usuario a inferir su función. | flujoI_perfil.jpg | 1 |
| H14-J | H1 - Visibilidad del estado del sistema | Detalles del movimiento | La pantalla muestra información detallada, pero no indica claramente el estado de la transacción (exitosa, pendiente, fallida). | flujoJ_detalle_movimiento.jpg | 2 |

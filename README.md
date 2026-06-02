## 🛡️ Lista de Chequeo de Seguridad (Security Checklist)

- [x] **Configuración de GitHub Security:** Paso 1 completado (Dependabot y Secret Scanning activos).
- [ ] **Prevención de XSS:** Validar que el archivo `index.html` use `.textContent` y nunca `.innerHTML` si maneja datos del usuario.
- [ ] **Verificación de Enlaces:** Confirmar que `<link rel="stylesheet" href="estilos.css">` use una ruta local y segura.
- [ ] **Limpieza de Historial:** Revisar que no existan contraseñas, correos ni tokens comentados en el código actual.
- [ ] **Conexión Segura (HTTPS):** Asegurar que GitHub Pages tenga activado el cifrado HTTPS.

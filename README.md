# 🔐 Tarea - Proyecto Leluzca20

Repositorio configurado con **autenticación SSH** para máxima seguridad.

## 📍 UBICACIÓN DE LAS CLAVES SSH

### Tu máquina local:
\\\
C:\Users\Adrian\.ssh\
├── id_ed25519              # Clave privada personal
├── id_ed25519.pub          # Clave pública personal
├── id_ed25519_cliente      # ⭐ Clave privada del cliente (NO COMPARTAS)
├── id_ed25519_cliente.pub  # ⭐ Clave pública del cliente (registrada en GitHub)
└── config                  # Configuración SSH
\\\

## 🔑 Información de la Clave SSH del Cliente

- **Nombre de archivo**: id_ed25519_cliente
- **Ubicación completa**: C:\Users\Adrian\.ssh\id_ed25519_cliente
- **Variable de entorno**: \C:\Users\Adrian\.ssh\id_ed25519_cliente
- **Tipo**: Ed25519 (segura y moderna)
- **Identificador SHA256**: NEZaxndgbtBiqKr/5aE1CuLz4lGh0VvI/RnCv1Iudd0
- **Registrada en GitHub**: ✅ Como "Deploy Key" del repositorio

## 🚀 Primeros pasos para nueva sesión

1. **Verifica que exista la clave**:
   \\\powershell
   Test-Path C:\Users\Adrian\.ssh\id_ed25519_cliente
   \\\

2. **Usa el repositorio**:
   \\\powershell
   cd C:\Users\Adrian\ALvarado\Tarea
   git pull origin main
   git push origin main
   \\\

3. **Consulta \gent.md\ para más detalles** sobre cómo funciona la autenticación.

## ✅ Seguridad

- **Token local**: ✓ NO se elimina (sigue en Windows Credential Manager)
- **Clave SSH privada**: 🔒 Guardada de forma segura en tu máquina
- **Clave SSH pública**: ✓ Registrada en GitHub
- **SSH y HTTPS coexisten**: ✓ Ambos métodos funcionan

## 📚 Archivos importantes

- **agent.md**: Guía técnica completa (NO se sube a Git)
- **.gitignore**: Protege credenciales y secretos
- **README.md**: Este archivo, con guía rápida

---
**Última actualización**: 15 de mayo de 2026

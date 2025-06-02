# Reconocimiento
# Sistema de Seguridad Inteligente con Reconocimiento Facial

Este proyecto implementa un sistema de seguridad inteligente basado en **ESP32-CAM** con capacidades de **reconocimiento facial**, sensores de movimiento, control de acceso automatizado, ideal para aplicaciones de vigilancia.

## Descripción del Sistema

El sistema reconoce rostros autorizados  y responde en consecuencia:

- Si el rostro es **reconocido**, se permite el acceso.
- Si el rostro es **desconocido**, se activan alertas visuales y sonoras, y se bloquea el acceso.

### 🔧 Componentes Utilizados

| Componente                  | Función                                                                 |
|----------------------------|------------------------------------------------------------------------|
| ESP32-CAM                  | Captura de imagen y ejecución del reconocimiento facial                |
| Zumbador (Buzzer)          | Alarma sonora en caso de intrusión                                     |
| LED RGB                    | Indicador visual del estado del sistema (verde, rojo, azul)            |
| Firebase                   | Almacenamiento remoto de datos e historial de actividad                |

---

## ⚙️ Funcionalidades Principales

- ✅ **Reconocimiento facial** mediante red neuronal entrenada.
- 🚨 **Alerta de intrusos** con buzzer y LED RGB.
- 📡 **Envío de datos a Firebase** para monitoreo remoto.
---

## 🧠 Tecnologías y Software

- MicroPython 
- Firebase Realtime Database
- Reconocimiento facial 
- Librerías: `esp32cam`, `FirebaseESP32`, entre otras.

---

## 🛠️ Instalación y Configuración

1. **Flashear el ESP32-CAM** con el firmware (MicroPython o Arduino).
3. **Configurar el WiFi y Firebase** en el código fuente.
4. **Entrenar y subir los rostros autorizados** al sistema (según método de implementación).
5. **Encender el sistema** y observar el comportamiento desde la OLED y Firebase.

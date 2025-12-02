# 🛠️ Config Server (Paso 1)

**Puerto:** `8888`

Este es el **primer servicio que debe iniciarse**. Se encarga de leer las configuraciones desde el repositorio remoto (config-data) y distribuirlas al resto de los microservicios al arrancar.

---
### 🔗 Mapa de Arquitectura
0. [Config data](https://github.com/AlexaRamirezV/config-data.git)
1.  ➡️ **[Config Server]** (estamos aquí)
2.  [Registry Service (Eureka)](https://github.com/AlexaRamirezV/registry-service.git)
3.  [Gateway Service](https://github.com/AlexaRamirezV/gateway-service.git)
4.  [Admin Service](https://github.com/AlexaRamirezV/admin-service.git)
5.  APIs del sistema:
   * [Auth](https://github.com/AlexaRamirezV/DWB-auth.git)
   * [Customer](https://github.com/AlexaRamirezV/DWB-customer.git)
   * [Product](https://github.com/xEriis/Backend.git)
   * [Invoice](https://github.com/AlexaRamirezV/DWB-invoice.git).

# 🛰️ Cisco Packet Tracer - Configuración de Router Inalámbrico y Clientes

Este laboratorio fue desarrollado en **Cisco Packet Tracer** con el objetivo de configurar un **router inalámbrico doméstico** y conectar distintos dispositivos (PCs y laptops) mediante cable y WiFi, asegurando la correcta entrega de direcciones IP a través de **DHCP**.

## 🎯 Objetivos del laboratorio
- Configurar un **router inalámbrico** para la red doméstica.  
- Asignar direcciones IP de manera automática usando **DHCP**.  
- Conectar PCs mediante cable Ethernet.  
- Conectar laptops y otros dispositivos mediante **WiFi seguro**.  
- Verificar conectividad y funcionamiento de la red.

---

## 🛠️ Topología de Red
La red está compuesta por los siguientes dispositivos:

- **ISP Cloud** (proveedor de internet simulado).  
- **Cable Modem** conectado a un splitter coaxial.  
- **Router Inalámbrico** configurado con:
  - IP LAN: `192.168.0.1`
  - DHCP habilitado
  - Pool de direcciones: `192.168.0.1 - 192.168.0.10`
  - SSID: `LinksysPool`
  - Seguridad WPA2 con clave precompartida.  
- **Dispositivos finales**:
  - Office PC (cableado).  
  - Bedroom PC (cableado).  
  - Laptop (conectada por WiFi).  

---

## ⚙️ Configuración realizada

### 🔹 Router Inalámbrico
- Tipo de conexión a Internet: **DHCP automático**.  
- Dirección IP LAN: `192.168.0.1`.  
- Servidor DHCP activado:
  - Rango: `192.168.0.1 – 192.168.0.50`.  
  - Máx. usuarios: 50.  
- Configuración WiFi:
  - SSID: **LinksysPool**.  
  - Seguridad: **WPA2-PSK**.  
  - Contraseña: configurada para clientes.

### 🔹 Dispositivos finales
- **Office PC**: recibe IP vía DHCP (FastEthernet).  
- **Bedroom PC**: recibe IP vía DHCP (FastEthernet).  
- **Laptop**: conectada vía WiFi al SSID `LinksysPool`.  

---

## ✅ Resultados
- Todos los dispositivos reciben una **dirección IP válida**.  
- Se confirma la conectividad entre PCs y router.  
- Conexión inalámbrica funcionando con autenticación WPA2.  
- **Actividad completada al 100% en Packet Tracer** ✔️ (Score: 19/19).

---

## 📸 Evidencias
<img width="1920" height="1032" alt="image" src="https://github.com/user-attachments/assets/dafe0f4e-078e-4ce3-ab56-833710111d42" />
<img width="955" height="865" alt="image" src="https://github.com/user-attachments/assets/dbe67e99-8c28-4ed9-a8ef-6831c6678805" />
<img width="1920" height="1032" alt="image" src="https://github.com/user-attachments/assets/d3306dc2-3452-4bde-af37-8bc0700ed455" />



---

## 🚀 Conclusión
Este laboratorio permite comprender cómo configurar una **red doméstica básica con conexión inalámbrica** en Cisco Packet Tracer, asegurando la entrega automática de direcciones IP y la conexión segura de dispositivos cableados e inalámbricos.

# 🖥️ Portfolio de Fundamentos de Hardware - 1º ASIR

¡Bienvenido al repositorio del módulo de **Fundamentos de Hardware**!

Este espacio recopila la documentación, esquemas, presupuestos y apuntes teórico-prácticos desarrollados durante el curso. El objetivo de este módulo es comprender a bajo nivel la arquitectura de los equipos informáticos, dominar el ensamblaje y mantenimiento de los mismos, y conocer los principios físicos y lógicos que hacen posible el procesamiento de la información.

A continuación, se detalla el contenido técnico y las competencias adquiridas, divididas por bloques de aprendizaje:

---

## 🏗️ Arquitectura Base y Componentes Internos
Estudio exhaustivo de la estructura física del ordenador y la comunicación entre sus componentes.
* **Modelo de Von Neumann:** Comprensión de la arquitectura clásica (CPU, Memoria Principal, Sistema de E/S y Buses).
* **La Placa Base (Motherboard):** Identificación de formatos (ATX, Micro-ATX, Mini-ITX), chipsets (Puente Norte y Puente Sur/PCH), zócalos de CPU y ranuras de expansión (PCIe).
* **Procesadores (CPU):** Análisis de arquitecturas (x86, ARM), núcleos, hilos (multithreading), memoria caché (L1, L2, L3) y frecuencias de reloj.
* **Memoria RAM:** Diferenciación entre tecnologías (DDR3, DDR4, DDR5), latencias (CL), velocidades y el concepto de Dual/Quad Channel.
* **Fuentes de Alimentación (PSU):** Cálculo de potencias, raíles de voltaje, certificaciones de eficiencia (80 Plus) y formatos (modulares y no modulares).

## 💾 Sistemas de Almacenamiento y Tecnologías RAID
Gestión de la retención de datos, rendimiento y redundancia.
* **Almacenamiento Magnético vs Sólido:** Diferencias de funcionamiento, ventajas y cuellos de botella entre discos duros mecánicos (HDD) y unidades de estado sólido (SSD).
* **Interfaces y Protocolos:** Evolución de las conexiones, desde SATA III hasta las unidades NVMe operando sobre líneas PCI Express.
* **Sistemas RAID:** Configuración y casos de uso de arreglos de discos para redundancia y rendimiento (RAID 0, RAID 1, RAID 5, RAID 10).

## 🔢 Lógica Computacional y Representación de la Información
El lenguaje base de las máquinas y el procesamiento a nivel de bit.
* **Sistemas de Numeración:** Conversiones matemáticas entre bases Decimal, Binaria, Octal y Hexadecimal.
* **Medidas de Información:** Unidades de almacenamiento convencionales (Bits, Bytes, Kilobytes, Megabytes) y su estandarización internacional.
* **Puertas Lógicas y Álgebra de Boole:** Tablas de verdad y operaciones fundamentales (AND, OR, NOT, XOR) empleadas en la construcción de circuitos integrados.

## 🛠️ Ensamblaje, Mantenimiento y Configuración Lógica
Aplicación práctica del taller y configuración inicial de los equipos.
* **Técnicas de Montaje:** Procedimientos seguros de ensamblaje de PCs, gestión del cableado (*cable management*) y aplicación correcta de compuestos térmicos (pasta térmica).
* **Prevención de Riesgos (EPIs):** Manejo de la electricidad estática (pulseras antiestáticas), herramientas adecuadas y protocolos de seguridad en el taller de hardware.
* **BIOS y UEFI:** Acceso al firmware de la placa base, configuración de la secuencia de arranque (*boot priority*), perfiles XMP/EXPO para la memoria y monitorización de hardware (temperaturas y voltajes).
* **Resolución de Problemas (Troubleshooting):** Diagnóstico de fallos a través de pitidos de la BIOS (códigos POST), leds de depuración en la placa base y tests de estrés de componentes.

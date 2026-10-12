# Rele Casero

Autor : Demian David Ramirez

---
# **Descripción**

Este proyecto tiene la finalidad de poder recrear un módulo Relé funcional para accionar un dispositivo electrónico que opera a un voltaje mucho mayor mediante una señal digital proveniente de un microcontrolador programable.
Un ejemplo concreto sería encender un foco, o iniciar una máquina más grande que funciona a 220v.

# **Funcionamiento**

El Esp32 recibe una señal inalámbrica y envía una señal eléctrica con dirección al relé. El sistema es separado por un optoacoplador el cual transmite esa señal sin comprometer al microcontrolador. El transistor se conecta en modo saturación para entregar el voltaje necesario para encender el relé.

# **Justificación de componentes**

### ESP32:
Este microcontrolador permite el fácil control de componentes por señales electrónicas, contando con la capacidad de comunicarse inalámbricamente.

### Relé:
Permite que una señal de menor intensidad encienda un dispositivo de mayor voltaje.

### Optoacoplador:
Aísla dos partes del circuito para evitar que un voltaje mayor queme la parte de bajo voltaje.

### Transistor:
El Relé sólo recibirá corriente cuando el Transistor permite el paso(Como medida preventiva para asegurar el curso correcto de la corriente).

# Analisis Economico
### Materiales

| Componente | Precio |
| ------------- | ------------- |
| ESP32 C3 super mini | 8500 |
| Relé | 1800  |
| 4n25(Optoacoplador) | 3844 |
|2n2222(Transistor) | 200 |
| XL6009 | 3608 - 2990 |
|Placa de cobre|880|

Precio Final:18214

# ESQUEMATICO
![alt text](https://github.com/JuasHuex5/Rele-Casero/blob/main/Hardware/ESQUEMATICOrepro.png "Esquematico")

# PCB
![alt text](https://github.com/JuasHuex5/Rele-Casero/blob/main/Hardware/PCBpro.png "PCBxd")

# Objetivo
Se realiza este proyecto con la finalidad de poder armar un modulo Relay desde casa, ya que los que se encuentran en el mercado son mucho mas costosos que montandolo de manera casera.


# Eurobot 2027 · Robot principal · Diseño 3D

**Software CAD:** SolidWorks 2025

## Especificaciones

| Parámetro | Reglamento | Nuestro robot |
|---|---|---|
| Perímetro máx. | 1200 mm al inicio · 1400 mm desplegado | 800 mm · Sin actuador|
| Altura máx. componentes| 350 mm (robot y objetos manipulados) | [ ] mm |
| Altura máx | 375 mm (parada de emergencia) · 430 ± 5 mm (superficie del soporte de baliza) | [ ] mm |

## Estructura del repositorio

```
/Componentes
  /Motores               
  /Neumatica              # Componentes relacionados con el actuador y sistema pneumatico
  /Reguladores de tension 
  /Ruedas                 
/Garra                    # Actuador
/Subensamblajes
DT-Principal.SLDASM       # Ensamblaje Principal del Robot
```

## Lista de componentes (BOM)

| Subsistema | Componente | Fabricante | Modelo exacto | Cant. |
| :--- | :--- | :--- | :--- | :---: |
| Tracción | Motor | Makerblock |25mm encoder DC9V 185RPM Gear Ratio 1:45 | 2 |
| Tracción | Rueda | [ ] | Ojala lo supiese | 2 |
| Tracción | Rueda loca / omni | Polulu - Bricogeek| Rueda loca ABS 3/4  954 | 2 ó 4|
| Electrónica | Microcontrolador | ESP32 | no se, mirar | 1 |
| Electrónica | Driver de motores | [ ] | [ ] | 1 |
| Electrónica | Regulador de Tensión | [ ] | [ ] | 1 |
| Electrónica | RPI 5 | Raspberry Pi | RPi 5 | 1 |
| Electrónica | Batería | [ ] | [ ] | 1 |
| Electrónica | Parada de emergencia | Bricogeek | Y090 | 1 |
| Sensores | LiDAR | [ ] | [ ] | 1 |
| Sensores | Sensores de distancia | [ ] | [ ] | [ ] |
| Sensores | IMU | nose | MPU6050 (GY-521) | 1 |
| Actuadores | Servo Giro | FEETECH - Bricogeek| FS5115M-FB | 1 |
| Actuadores | Motor Paso a Paso | [ ] | [ ] | 1 |
| Actuadores | Bomba | DFRobot | 370 mini vaccum pump 6V | 3 |
| Actuadores | Ventosa | Festo | 30mm Festo VASB-30-1/8-PUR-B Fuelle Poliuretano G 1/8 | 6 |
| Estructura | Perfil | - |  | 20x20mm |
---
hide:
    - toc
---

# Proyecto Final: WHTMet - Estación Meteorológica IoT

# Lista de Materiales

En esta sección detallaré los componentes necesarios para armar un Nodo de WHTMet.

- **Detalle de los Componentes:**

**Sensor SHT31:**

<figure markdown="span">
  ![Imagen 1 - BOM - SHT31](../images/PF2/bom/sht31.png#soloBordesRed)
</figure>

**Sensor DHT11:**

<figure markdown="span">
  ![Imagen 2 - BOM - SHT11](../images/PF2/bom/sht11.png#soloBordesRed)
</figure>

**Insertos de Latón M3 (3mm x 4mm):**

<figure markdown="span">
  ![Imagen 3 - BOM - Insertos](../images/PF2/bom/insertos.png#soloBordesRed)
</figure>

**Tornillos M3 (8mm) :**

<figure markdown="span">
  ![Imagen 4 - BOM - Tornillos](../images/PF2/bom/tornillos.png#soloBordesRed)
</figure>

**ESP32-WROOM-32U (CP1202):**

<figure markdown="span">
  ![Imagen 5 - BOM - ESP32](../images/PF2/bom/esp32.png#soloBordesRed)
</figure>

**Antena 2,4 Ghz y 3dBi para ESP32:**

<figure markdown="span">
  ![Imagen 6 - BOM - Antena](../images/PF2/bom/antena.png#soloBordesRed)
</figure>

**Módulo RGB 3_C1r:**

<figure markdown="span">
  ![Imagen 6 - BOM - RGBLed](../images/PF2/bom/ledrgb.png#soloBordesRed)
</figure>

**Diodos LED:**

<figure markdown="span">
  ![Imagen 7 - BOM - LEDS](../images/PF2/bom/leds.png#soloBordesRed)
</figure>

**Resistencias 220 Ohms:**

<figure markdown="span">
  ![Imagen 8 - BOM - Resistencias](../images/PF2/bom/resistencias.png#soloBordesRed)
</figure>

**Sensor Hall KY-003:**

<figure markdown="span">
  ![Imagen 8 - BOM - SensorHall](../images/PF2/bom/sensorhall.png#soloBordesRed)
</figure>

**Protoboard y Set de Cables:**

<figure markdown="span">
  ![Imagen 9 - BOM - Protoboard](../images/PF2/bom/protoboard.png#soloBordesRed)
</figure>

<figure markdown="span">
  ![Imagen 10 - BOM - SetCables](../images/PF2/bom/cablesprotoboard.png#soloBordesRed)
</figure>

- **Cantidades y Costo de los Componentes:**

| **Componente**                          | **Cantidad** | **Especificaciones**                          | **Proveedor**       | **Precio Unitario (USD)** | **Costo Total (USD)** |
|-----------------------------------------|--------------|-----------------------------------------------|---------------------|---------------------------|-----------------------|
| Sensor SHT31                            | 1            | I2C, Precisión ±2% HR, ±0.3 °C Temp           | DigiKey             | 12.00                     | 12.00                 |
| Sensor DHT11                            | 1            | Rango: 0-50 °C, 20-90% HR                     | Amazon              | 3.50                      | 3.50                  |
| Insertos de Latón M3 (3mm x 4mm)        | 4            | Rosca M3, Material: Latón                     | Aliexpress          | 0.10                      | 0.40                  |
| Tornillos M3 (8mm)                      | 4            | Material: Acero Inoxidable                    | Ferretería Local    | 0.05                      | 0.20                  |
| ESP32-WROOM-32U (CP1202)                | 1            | Wi-Fi + BT, Microcontrolador                  | Amazon              | 6.00                      | 6.00                  |
| Antena 2.4 GHz, 3dBi                    | 1            | Frecuencia: 2.4 GHz, Ganancia: 3dBi           | AliExpress          | 1.50                      | 1.50                  |
| Módulo RGB 3_C1r                        | 1            | 3 LEDs RGB, 5V                                | eBay                | 2.00                      | 2.00                  |
| Diodos LED (Color Rojo)                 | 2            | 5mm, 20mA, Color Rojo                         | DigiKey             | 0.10                      | 0.20                  |
| Diodos LED (Color Azul)                 | 2            | 5mm, 20mA, Color Azul                         | DigiKey             | 0.15                      | 0.30                  |
| Resistencias 220 Ohms                   | 10           | 1/4W, 5%                                     | DigiKey             | 0.02                      | 0.20                  |
| Sensor Hall KY-003                      | 1            | Voltaje: 5V, Salida Digital                   | Banggood            | 1.50                      | 1.50                  |
| Protoboard                              | 1            | 830 puntos                                    | Amazon              | 3.00                      | 3.00                  |
| Set de Cables para Protoboard           | 1            | 65 cables macho-macho                         | Amazon              | 2.00                      | 2.00                  |

| **Total (USD)**                         |              |                                               |                     |                           | **31.80**            |
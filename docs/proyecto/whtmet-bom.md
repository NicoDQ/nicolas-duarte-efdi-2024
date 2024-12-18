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

| **Componente**                          | **Cantidad** | **Especificaciones**                          | **Proveedor**                                                                                   | **Precio Unitario (USD)** | **Costo Total (USD)** |
|-----------------------------------------|--------------|-----------------------------------------------|-------------------------------------------------------------------------------------------------|---------------------------|-----------------------|
| Sensor SHT31                            | 1            | I2C, 0-100% RH, -40°C a +125°C, RH tau63%: 8s | [AliExpress](https://es.aliexpress.com/item/1005006068631562.html?spm=a2g0o.order_list.order_list_main.41.5fda194daOznhO&gatewayAdapt=glo2esp4itemAdapt#nav-specification) | 6.80                      | 6.80                  |
| Sensor DHT11                            | 1            | Rango: 0-50 °C, 20-90% HR                     | [AliExpress](https://es.aliexpress.com/item/4001253056515.html?spm=a2g0o.productlist.main.1.1e012fb5RLTVYp) | 0.69                      | 0.69                  |
| Sensor Hall                             | 1            | Detección magnética                           | [AliExpress](https://es.aliexpress.com/item/1005004737218969.html?spm=a2g0o.productlist.main.9.6fe453207TK88e) | 0.54                      | 0.54                  |
| Insertos de Latón M3 (3mm x 4mm)        | 6            | Rosca M3, Material: Latón                     | [AliExpress](https://es.aliexpress.com/item/32890237459.html)                                    | 0.04                      | 0.24                  |
| Tornillos M3 (8mm)                      | 6            | Material: Acero Inoxidable                    | [AliExpress](https://es.aliexpress.com/item/32810852732.html)                                   | 0.03                      | 0.18                  |
| ESP32-WROOM-32U (CP1202)                | 1            | Wi-Fi + BT, Microcontrolador                  | [AliExpress](https://es.aliexpress.com/item/1005007498353201.html)                              | 8.28                      | 8.28                  |
| Antena 2.4 GHz, 3dBi                    | 1            | Frecuencia: 2.4 GHz, Ganancia: 3dBi           | [AliExpress](https://es.aliexpress.com/item/1005005218090899.html)                              | 0.86                      | 0.86                  |
| Módulo RGB 3_C1r                        | 2            | 3 LEDs RGB, 5V                                | [AliExpress](https://es.aliexpress.com/item/1005006856783025.html)                              | 0.18                      | 0.36                  |
| Diodos LED (Color Rojo)                 | 2            | 5mm, 20mA, Color Rojo                         | [AliExpress](https://es.aliexpress.com/item/32843059560.html)                                   | 0.04                      | 0.08                  |
| Diodos LED (Color Azul)                 | 2            | 5mm, 20mA, Color Azul                         | [AliExpress](https://es.aliexpress.com/item/32843059560.html)                                   | 0.04                      | 0.08                  |
| Resistencias 220 Ohms                   | 2            | 1/4W, 5%                                     | [AliExpress](https://es.aliexpress.com/item/1005002991904292.html)                              | 0.03                      | 0.06                  |
| Protoboard (400 puntos)                 | 1            | 400 puntos                                    | [AliExpress](https://es.aliexpress.com/item/1005003073275216.html)                              | 1.72                      | 1.72                  |
| Set de Cables para Protoboard           | 1            | 40 cables                                     | [AliExpress](https://es.aliexpress.com/item/1005003073275216.html)                              | 1.06                      | 1.06                  |

- **Resumen de Costo Total:**

Sumando todos los componentes:

6.80 + 0.69 + 0.54 + 0.24 + 0.18 + 8.28 + 0.86 + 0.36 + 0.08 + 0.08 + 0.06 + 1.72 + 1.06 = 20.95 USD
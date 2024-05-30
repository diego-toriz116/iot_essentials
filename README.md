<a id="presentacion"></a>
# iot_essentials
Repositorio del curso [IoT Essentials Developer](https://edu.codigoiot.com/?redirect=0 "Ir al curso")
Aqui se suben los ejercicios del curso IoT Essentials Developer.
| Modulo | Ejercicio | Fecha |
|:------------:|-------------:|:------------:|
| Utilizacion de R pi | Prender LED | 18 de mayo |
| Acceso Vehicular | RFID | 21 de mayo |

# Contenidos
* [Introduccion](#presentacion)
* [Ejercicios incluidos](#incluidos)
* [Advertencias de uso](#advertencias)
<a id="incluidos"></a>
## Ejercicios incluidos
1. Parpadear LED
    * Circuito sugerido
    * Codigo para prender LED desde Python
1. Lectura de tarjeta RFID
    * Requiere creer un ambiente de trabajo con:
    ```shell
    python -m venv <nombre_de_ambiente>
    source <nombre_de_ambiente>/bin/activate
    ```
    * Requiere las bibliotecas spidev mfrc522
    ```shell
    python -m pip install spidev
    python -m pip install mfrc522
    ```
    * Consulta [rfid.py](./RFID/rfid.py) para mas info
    
<a id="advertencias"></a>
## Advertencias de uso
**Este codigo es experimental y con fines educativos** ***uselo bajo su propio riesgo***
<a id="pendientes"></a>
## To Do
- [X] Iniciar Documentacion
- [ ] Incorporar codigo del LED
- [ ] Hacer notas sobre el Git

# Dashboard_Ventas_Power_BI

# Enlace informe de ventas

En el siguiente enlace pueden acceder al informe del proyecto de BI

['Informe_Ventas_PowerBI'](https://app.powerbi.com/view?r=eyJrIjoiOWRjZWFjM2MtMGNlMi00ZjFmLWFjMzYtNTNkYTFkNzgzZjQzIiwidCI6Ijk5ZTFlNzIxLTcxODQtNDk4ZS04YWZmLWIyYWQ0ZTUzYzFjMiIsImMiOjR9)

# 01 Fuentes de datos
----

* **Sales Dataset:**
  
**Formato:** Archivo de Excel.

**Contenido:** Registros simulados de ventas de productos electrónicos, suministros de oficina (office supplies) y mobiliario (furniture).

**Alcance Geográfico:** Sucursales en Estados Unidos.

**Periodo de tiempo:** Enero de 2020 a marzo de 2025.

* **API TRM:**
  
  Utilicé la API de la TRM (Tasa Representativa del Mercado) para crear una medida DAX que convierte las ganancias de USD a pesos colombianos. Para este ejercicio, se aplicó la tasa vigente para el 19 de febrero de 2026, la cual fue publicada oficialmente  aproximadamente a las 6:00 p. m. del día 18 de febrero (hora Colombia).

  Enlaces de ínteres
- [Definición TRM BanRep](https://www.banrep.gov.co/es/glosario/tasa-cambio-trm)
- [Serie Historica TRM](https://suameca.banrep.gov.co/estadisticas-economicas/informacionSerie/1/tasa_cambio_peso_colombiano_trm_dolar_usd)
- [Enlace API de TRM](https://www.datos.gov.co/Econom-a-y-Finanzas/Tasa-de-Cambio-Representativa-del-Mercado-TRM/32sa-8pi3/about_data)

Nota: si alguno de los enlaces no funciona, refrescar la pagina donde haya abierto el link y deberia ser suficiente.

Este recurso se implementó como un Tooltip para las tarjetas de ganancias en COP, permitiendo visualizar la conversión de los valores originales en USD. Como se observa en el adelanto, el Tooltip muestra la fecha de vigencia de la tasa y el valor aplicado para el cálculo. Cabe notar que, aunque la arquitectura del informe permite actualizaciones diarias automáticas, en este ejercicio se mantuvo una configuración de carga manual debido a las especificaciones de la licencia gratuita de Power BI y la configuración de la puerta de enlace (gateway).

  
<img width="558" height="114" alt="Captura de pantalla 2026-02-18 113953" src="https://github.com/user-attachments/assets/47d5ce15-5b80-4851-aa58-c1be33991bf4" />


<img width="602" height="196" alt="Captura de pantalla 2026-02-18 114026" src="https://github.com/user-attachments/assets/432ca695-ae6d-4032-9619-21cd44419758" />


Comparativa tras haber actualizado el informe a las 6 pm el día 18 de febrero de 2026


<img width="567" height="129" alt="image" src="https://github.com/user-attachments/assets/05606339-8a6c-417f-b8fb-dc2805f04c10" />

Probando el tooltip actualizado

<img width="634" height="206" alt="image" src="https://github.com/user-attachments/assets/67e4fc3b-4e5b-4e1f-b9e4-e349a0818658" />


# 02 Modelo relacional


<img width="1298" height="637" alt="image" src="https://github.com/user-attachments/assets/f3dc7b55-2c48-4bea-a842-379a3e6ece21" />


# 03 Vistazo general dashboard

* Ganancias
  ---

<img width="1339" height="743" alt="image" src="https://github.com/user-attachments/assets/e66d6f7d-0d84-4ea5-ab07-04c98f9aa9d9" />

* Demanda
  ---

<img width="1396" height="752" alt="image" src="https://github.com/user-attachments/assets/1079de22-6895-4003-985a-5dd9149d74db" />

* Clientes
  ---

<img width="1358" height="757" alt="image" src="https://github.com/user-attachments/assets/e5ac9889-be99-4208-a6a2-4d35a655274c" />




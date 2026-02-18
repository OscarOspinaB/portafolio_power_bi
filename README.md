# Informe_Ventas_Power_BI

# Enlace informe de ventas

En el siguiente enlace pueden acceder al informe del proyecto de BI

['Informe_Ventas_PowerBI'](https://app.powerbi.com/view?r=eyJrIjoiNmRjNzhlMjItMjY0ZS00MjVlLWJkOTctOGFlNzJkM2Y3NTE1IiwidCI6Ijk5ZTFlNzIxLTcxODQtNDk4ZS04YWZmLWIyYWQ0ZTUzYzFjMiIsImMiOjR9)

# Fuentes de datos
----

* **Sales Dataset:**
  
**Formato:** Archivo de Excel.

**Contenido:** Registros simulados de ventas de productos electrónicos, suministros de oficina (office supplies) y mobiliario (furniture).

**Alcance Geográfico:** Sucursales en Estados Unidos.

**Periodo de tiempo:** Enero de 2020 a marzo de 2025.

* **API TRM:**
  
  Utilicé la API de la TRM (Tasa Representativa del Mercado) para crear una medida DAX que convierte la ganancia de USD a pesos colombianos. La API actualiza el valor de la tasa diariamente a las 12:00 p. m., por lo cual el informe de Power BI está programado para refrescarse a las 12:30 p. m. (hora Colombia), asegurando así el uso del dato más reciente

  Enlaces de ínteres
- [Definición TRM BanRep](https://www.banrep.gov.co/es/glosario/tasa-cambio-trm)
- [Serie Historica TRM](https://suameca.banrep.gov.co/estadisticas-economicas/informacionSerie/1/tasa_cambio_peso_colombiano_trm_dolar_usd)
- [Enlace API de TRM](https://www.datos.gov.co/Econom-a-y-Finanzas/Tasa-de-Cambio-Representativa-del-Mercado-TRM/32sa-8pi3/about_data)

Nota: si algun de los enlaces no funciona, refrescar la pagina donde haya abierto el link y deberia ser suficiente.

Este recurso se implementó como un Tooltip para las tarjetas de ganancias en COP, permitiendo visualizar la conversión de los valores originales en USD. Como se observa en el adelanto, el Tooltip muestra la fecha de consulta y el valor de la tasa aplicada. Es importante notar que, aunque el Banco de la República actualiza la serie histórica a las 12:00 p. m., el informe de Power BI está programado para reflejar este cambio a las 12:30 p. m. (hora Colombia).

  
<img width="558" height="114" alt="Captura de pantalla 2026-02-18 113953" src="https://github.com/user-attachments/assets/47d5ce15-5b80-4851-aa58-c1be33991bf4" />


<img width="602" height="196" alt="Captura de pantalla 2026-02-18 114026" src="https://github.com/user-attachments/assets/432ca695-ae6d-4032-9619-21cd44419758" />

# MAPA DE CALOR POR FALLECIDOS POR COVID - PERÚ(Regiones)
##### Autor : Quispe Guzman Fausto
### Covid
La enfermedad por coronavirus (COVID‑19) es una enfermedad infecciosa provocada por el virus SARS-CoV-2.
La mayoría de las personas que padecen COVID‑19 sufren síntomas de intensidad leve a moderada y se recuperan sin necesidad de tratamientos especiales. Sin embargo, algunas personas desarrollan casos graves y necesitan atención médica.
![](https://www.un.org/sites/un2.un.org/files/styles/large-article-image-style-16-9/public/field/image/covid-19-variants.jpg?itok=_7yjJXSt)

### DATOS:
Los datos recopilados, fueron suministrados de la Organización Mundial de la Salud(OMS). Posteriormente filtrados los datos para Perú por regiones.
Los casos fueron registrados de manera diaria desde el inicio de la pandemia; asimismo se sumaron los valores de cada dia, para poder obtener el total de casos por dia.
### MAPA
El mapa se desarrolló usando la librerias plotly y en la parte de generar la geografia de este, se solicitó el siguiente trabajo de github en forma de Json `https://raw.githubusercontent.com/juaneladio/peru-geojson/master/peru_departamental_simple.geojson`

### LIBRERIAS INSTALADAS
<li>pip install plotly
<li>pip install pandas
  
### Mapa de Calor:
![newplot](https://user-images.githubusercontent.com/87513184/219402598-b45001fc-3ac5-46ad-ac31-65ccaf3b8dca.png)

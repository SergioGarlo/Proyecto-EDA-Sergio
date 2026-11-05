# Ventaja de jugar en casa en la Premier League

Análisis exploratorio de datos (EDA) para comprobar si los equipos de la Premier League rinden mejor como locales que como visitantes, y si esa ventaja ha cambiado con los años.

## Hipótesis y preguntas

**Hipótesis:** los equipos de la Premier League obtienen mejores resultados cuando juegan como locales que cuando juegan como visitantes.

1. ¿Se ganan más partidos jugando en casa?
2. ¿Se marcan más goles como local?
3. ¿Se realizan más tiros a puerta?
4. ¿Se consiguen más córneres?
5. ¿Ha disminuido la ventaja de jugar en casa con el paso de los años?

## Resultados principales

- **La hipótesis se cumple.** El local gana el 44,8 % de los partidos y el visitante el 29,9 %, lo que equivale a unos 8,5 puntos más por temporada jugando en casa.
- El local marca un 28 % más de goles, tira a puerta un 24 % más y consigue un 26 % más de córneres. Recibe un 21 % menos de tarjetas.
- Los tiros a puerta son la estadística que mejor se relaciona con ganar; los córneres informan poco.
- **La ventaja se reduce con los años:** las victorias locales pasan del 47,0 % (2000-2006) al 42,0 % (2014-2021), porque el visitante rinde mejor. La evidencia es moderada.

## Datos

Partidos de la Premier League de 1993-94 a 2021-22 (`results.csv`, 11.113 partidos y 23 columnas). Las estadísticas del partido solo existen desde 2000-01, así que el análisis usa una muestra estratificada de 2.007 partidos de las temporadas 2000-01 a 2021-22.

Fuente: *<<COMPLETAR: enlace de descarga del archivo>>*

## Tecnologías

Python, pandas, NumPy, Matplotlib, Seaborn, SciPy y Jupyter Notebook.

## Estructura del proyecto

```
.
├── README.md
├── requirements.txt
├── presentacion/          # presentación del proyecto
└── src/
    ├── memoria.ipynb      # memoria completa: limpieza, análisis y conclusiones
    ├── data/
    │   └── results.csv    # datos utilizados
    ├── notebooks/
    │   └── SCRIPT_EDA.ipynb   # notebook de pruebas
    └── utils/
        └── bootcampviztools.py  # funciones auxiliares de visualización
```

## Cómo ejecutarlo

```bash
pip install -r requirements.txt
cd src
jupyter notebook memoria.ipynb
```

Es importante abrir el notebook desde la carpeta `src`, porque las rutas a los datos y a `utils` son relativas a ella.

## Autor

*<<COMPLETAR: nombre y enlace a tu perfil de GitHub>>*

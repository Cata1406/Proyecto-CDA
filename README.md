# Proyecto-CDA

## :closed_book: Resumen 
Este proyecto tiene como objetivo desarrollar un modelo predictivo que identifique estudiantes de maestría con mayor riesgo de deserción en la Universidad de los Andes, utilizando técnicas de Machine Learning y análisis de datos históricos. El modelo busca ayudar a reducir la tasa de deserción y mejorar los índices de bienestar estudiantil, especialmente en los primeros tres semestres. El análisis se basa en datos de más de 15,000 estudiantes desde 2015, incluyendo información académica, sociodemográfica y financiera. 

## :receipt: Conclusiones

El modelo Random Forest fue seleccionado debido a su precisión (F1-Score de 0.89) y su capacidad de interpretación, ya que permite identificar factores clave como el promedio global, los semestres cursados, la edad y las tendencias en el rendimiento académico. Además, el proceso de limpieza y preparación de datos eliminó variables con altos porcentajes de nulos y valores atípicos; asimismo, se generaron variables derivadas, como el porcentaje de créditos aprobados (PCA), que mejoraron significativamente la capacidad predictiva del modelo. Por otro lado, el dashboard en Power BI integra estas predicciones para monitorear indicadores clave, identificar estudiantes en riesgo y priorizar intervenciones, optimizando recursos como el tiempo. En cuanto a las consideraciones éticas, el proyecto cumplió con normativas de protección de datos mediante la anonimización y la mitigación de riesgos, garantizando un enfoque ético. Por último, se recomienda automatizar la actualización de datos, incluir series temporales y enfocar las intervenciones en estudiantes con desafíos financieros, ya que todo esto consolida una herramienta robusta que no solo mejora la retención estudiantil, sino que también posiciona a la universidad como líder en el uso de tecnología avanzada para el bienestar de sus estudiantes. 

## :technologist: Autores
- Jairo Adolfo Céspedes Plata
- Lina María Gómez Mesa
- María Catalina Ibáñez Piñeres
- Santiago Iván Pardo Morales

## :computer: Corra localmente

Clone el proyecto

```bash
  git clone https://github.com/Cata1406/Proyecto-CDA
```

Vaya al directorio del proyecto

```bash
  cd Proyecto-CDA
```

Instale las dependencias

```bash
  pip install -r requirements.txt
```
## :open_file_folder: Base de Datos
Con el fin de que el proyecto le corra de manera exitosa, se requiere acceso a las bases de datos del proyecto las cuáles no son de público acceso. Si desea tener acceso a estes con fines investigativos comuníquese con m.ibanez@uniandes.edu.co.

## :open_file_folder: Archivos en el repositorio
- `Informe-Entrega-1.pdf`: corresponde al informe de la primera entrega
- `eda.ipynb`: Jupyter notebook que contiene la exploración de los datos que se hizo inicialmente, antes de calcular la etiqueta o variable target.
- `maestria_caracterizacion.pbix`: Archivo de PowerBI donde se encuentran gráficas en las que se caracteriza a los desertores, acá se hace la exploración de los datos, luego de calcular la etiqueta.
- `eda_training.ipynb`: Jupyter Notebook que contiene todo el proceso de unión/homogenización de bases de datos, limpieza de datos, cálculo de la etiqueta, entrenamiento y evaluación de modelos.
- `requirements.txt`: contiene las dependencias que debe instalar para poder correr los notebooks.
- `test_report.html`: reporte de pandas profiling sobre los datos de prueba.
- `train_report.html`: reporte de pandas profiling sobre los datos de entrenamiento.

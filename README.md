# Modelo de clasificacion en base a pruebas de autotest para COVID19
<p>Se creó un archivo csv con datos en base a las preguntas realizadas por la aplicación oficial.</p>
<p>Los datos del csv son aleatorios teniendo en cuenta los síntomas que puede presentar el paciente para su clasificación, <br>
fueron ingresados de forma manual (47 filas de datos para entrenamiento), llegando a un Score de 93%.
</p>
<br>
# Contenido del repositorio
<p>Archivo: <b>AutotestModelSklearn.ipynb:</b></p>
<p>Obtiene el set de datos armando de forma manual desde Google sheets.</p>
<p>Se crea el modelo KNeighboursClassifier de la librería sklearn y se lo entrena con los datos del autotest y sus clasificaciones.</p>
<p>Se expone como exportar o guardar el modelo con la librería joblib o pickle.</p>

<p>Archivo: <b>EjemploConsulta.ipynb</b></p>
<p>Contiene un ejemplo de consulta al proyecto ejecutándose en un servidor de Heroku<br>
Github del proyecto de la API: <a href="https://github.com/damianra/AutotestAPI-MachineLearning"></a><br>
Formulario Online: <a href="https://autotest-ml.herokuapp.com/">Link</a></p>
<br>
<p>Desarrollador: Damián Ramirez <a href="https://www.linkedin.com/in/damian-ramirez-677488172">LinkedIn</a></p>

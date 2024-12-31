# PREDICCION DE DIAGNOSTICO POSITIVO DE ALZHEIMER MEDIANTE MACHINE LEARNING

ABSTRACT

El diagnóstico temprano de la enfermedad de Alzheimer es crucial para mejorar la calidad de vida de los pacientes y permitir una planificación más efectiva de las estrategias de tratamiento. Esta enfermedad neurodegenerativa afecta a millones de personas en todo el mundo, especialmente en las poblaciones de mayor edad, y representa un desafío médico, social y económico significativo. A pesar de los avances en la investigación, la identificación de casos en etapas tempranas sigue siendo una tarea compleja debido a la variedad de factores que contribuyen a su desarrollo, incluyendo aspectos genéticos, biomédicos, y de estilo de vida. El objetivo de este proyecto es desarrollar un modelo de machine learning capaz de predecir de manera temprana los casos positivos de Alzheimer. Para ello, se utiliza un conjunto de datos clínicos y de estilo de vida que contiene información de 2149 pacientes. Este dataset incluye datos demográficos, evaluaciones cognitivas y funcionales, factores de riesgo relacionados con el estilo de vida (como actividad física, dieta y sueño) y antecedentes médicos (como historial familiar, enfermedades cardiovasculares y diabetes). La variable escogida como target del modelo es “Diagnóstico”, la cual indica la presencia o ausencia de la enfermedad en cada paciente. Los datos incluidos en este conjunto son ideales para investigadores y científicos de datos interesados en explorar los factores asociados con el Alzheimer, desarrollar modelos predictivos y realizar análisis estadísticos. Además, este proyecto busca no solo mejorar la precisión en la predicción del diagnóstico, sino también identificar los factores más relevantes, proporcionando una base sólida para intervenciones preventivas y nuevas líneas de investigación en el tratamiento de esta enfermedad devastadora.

DATASET UTILIZADO: https://https://www.kaggle.com/datasets/rabieelkharoua/alzheimers-disease-dataset

CITA DE AUTOR: @misc{rabie_el_kharoua_2024, title={Alzheimer's Disease Dataset}, url={https://www.kaggle.com/dsv/8668279}, DOI={10.34740/KAGGLE/DSV/8668279}, publisher={Kaggle}, author={Rabie El Kharoua}, year={2024} }

CONCLUSIONES

El resultado del proyecto fue muy satisfactorio. Se entreno y valido un modelo de machine learning que permite clasificar casos positivos de Alzheimer con minimos errores. En este caso, observamos que los modelos basados en arboles de decision, como Random Forest y XGBoost son los que expresan mejores resultados y compatibilidad con los datos. El desbalance entre las clases no influyo negativamente en el entrenamiento de estos modelos, cosa que se si ocurrio con los modelos de regresion logistica y KNN. La seleccion del dataset fue muy acertada, ya que estaba completamente normalizado y limpio, sin datos faltantes ni outliers en las features. Las modificaciones en los datos necesarias fueron minimas. A partir de las hipotesis planteadas y la posterior seleccion de features, podemos concluir tambien que, por mas que un determinado feature no muestre a simple vista una relacion con el diagnostico (en este caso, features asociadas con el estilo de vida), las mismas resultaban imprescindibles para el entrenamiento del modelo. En mi opinion, este tipo de proyectos se convertiran, en un futuro cercano, en una herramienta super complementaria en el diagnostico de pacientes con diversas patologias, ayudando al profesional en la toma de decisiones, disminuyendo a la vez los posibles errores de diagnostico.

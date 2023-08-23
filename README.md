# Enfermedad Cardiaca

Las enfermedades cardíacas son una de las principales causas de muerte para las personas de la mayoría de las razas en el mundo. Los factores de riesgo clave de enfermedad cardíaca son: presión arterial alta, colesterol alto y tabaquismo. Otros indicadores clave incluyen el estado diabético, la obesidad (IMC alto), no realizar suficiente actividad física o beber demasiado alcohol. Detectar y prevenir los factores que más inciden en las enfermedades del corazón es muy importante en el ámbito sanitario. 
Originalmente, el conjunto de datos proviene de los CDC y es una parte importante del Sistema de Vigilancia de Factores de Riesgo del Comportamiento (BRFSS), que realiza encuestas telefónicas anuales para recopilar datos sobre el estado de salud de los residentes de EE. UU. El conjunto de datos incluye datos de 2020, consta de 319795 filas y 279 columnas, pero para este proyecto se redujo a 18 variables. La gran mayoría de las columnas son preguntas que se hacen a los encuestados sobre su estado de salud. En este conjunto de datos, se incluyeron diferentes factores que directa o indirectamente influyen en la enfermedad cardíaca. Se debe tratar la variable "Enfermedad cardíaca" como binaria ("Sí", el encuestado tenía una enfermedad cardíaca; "No": el encuestado no tenía ninguna enfermedad cardíaca).

FUENTE: https://www.kaggle.com/datasets/kamilpytlak/personal-key-indicators-of-heart-disease

El dataset está conformado por 18 variables, la variable objetivo 'EnfermedadCardiaca', la cual es una variable categórica que indica si el individuo presenta o no alguna enfermedad cardiaca, 13 variables categóricas, que indican si el individuo presenta o no determinada condición, o describen alguna característica del mismo, las cuales son, 'Fumar', 'ConsumoAlcohol', 'AccidenteCerebroVascular', 'DificultadCaminar', 'Sexo', 'Edad'(categórica ya que la edad se encuentra diferenciada por rangos etarios), 'Raza', 'Diabetes', 'ActividadFísica', 'SaludGeneral', 'Asma', 'EnfermedadRenal', 'CancerDePiel', y 4 variables numéricas, 'IMC', 'SaludFisica', 'SaludMental' y 'HorasSueño'. A continuación se describen en detalle cada una de ellas:

*EnfermedadCardiaca: Encuestados que han reportado alguna vez haber tenido enfermedad coronaria o infarto de miocardio. Variable objetivo.
*IMC: Índice de Masa Corporal.
Fumar: ¿Has fumado al menos 100 cigarrillos en toda tu vida?
ConsumoAlcohol: Bebedores frecuentes (hombres adultos que toman más de 14 bebidas por semana y mujeres adultas que toman más de 7 bebidas por semana).
AccidenteCerebroVascular: ¿Alguna vez te han dicho que tuviste un accidente cerebrovascular?
SaludFisica: Pensando en tu salud física, que incluye enfermedades y lesiones físicas, ¿durante cuántos días de los últimos 30 días tu salud física fue mala?
SaludMental: Pensando en tu salud mental, ¿durante cuántos días de los últimos 30 días tu salud mental no fue buena?
DificultadCaminar: ¿Tienes dificultades graves para caminar o subir escaleras?
Sexo: ¿Eres hombre o mujer?
Edad: Categoría de edad de catorce niveles.
Raza: Raza/etnicidad.
Diabetes: ¿Alguna vez te han dicho que tienes diabetes?
ActividadFísica: Adultos que informaron haber realizado actividad física o ejercicio en los últimos 30 días que no fuera parte de su trabajo habitual.
SaludGeneral: Estado de salud general.
HorasSueño: En promedio, ¿cuántas horas de sueño obtienes en un período de 24 horas?
Asma: ¿Alguna vez te han dicho que tienes asma?
EnfermedadRenal: Sin incluir piedras en los riñones, infección de la vejiga o incontinencia, ¿alguna vez te han dicho que tienes enfermedad renal?
CancerDePiel: ¿Alguna vez te han dicho que tienes cáncer de piel?

Podría a partir del conjunto de datos predecirse la enfermedad cardiaca en pacientes en función de su historial médico? Esto puede ser útil para los profesionales de la salud en la identificación de pacientes que pueden estar en riesgo de desarrollar alguna enfermedad cardiaca y en el desarrollo de planes de tratamiento personalizados. Además, se puede explorar las relaciones entre varios factores médicos y la probabilidad de desarrollar otras enfermedades.

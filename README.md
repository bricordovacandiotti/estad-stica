Brigitte Carmen Córdova Candiotti 20170994

#¿QUE TRABAJO REALICE?
En el presente repositorio están las dos variables independientes que he utilizado: IDH y Rule of Law. Utilicé R Notebook, el archivo esta subido en RMD. He realizado un trabajo de limpieza en ambas variables. Asimismo, realicé el proceso de limpieza de la variable dependiente: ICP( index corruption perception). El trabajo de limpieza consistió en dividir columnas, eliminar corchetes, comas,etc. Luego de realizar la limpieza, procedí a realizar "merge" para unir las variables. Al realizar el trabajo de analizar los NA descubrí que muchos NA se generaban porque los nombres cambiaban entre bases. Por este motivo, procedí a estandarizar los nombres. Luego de una revisión muy conciezuda logré estandarizarlo completamente. Al final confirmé realizando nuevamente merge. 


#¿QUE VARIABLES UTILICE? 
Las variables que he trabajado son: "IDH"(Índice de Desarrollo Humano) y Rule of Law. 


#DEFINICIONES DE VARIABLES:
Las definiciones que usamos sobre estas variables son las siguientes:

#1)IDH: Indice de desarrollo humano
Es una medida resumida del logro promedio en dimensiones clave del desarrollo humano: vida larga y saludable, estar informado y tener nivel de vida decente. El IDH es la media geométrica de los índices normalizados para cada una de esas dimensiones.
Estimación: 0 a 1

#2)Rule of law: 
El Estado de derecho captura las percepciones del grado en que los agentes tienen confianza en las reglas de la sociedad y las acatan y, en particular, la calidad del cumplimiento de los contratos, los derechos de propiedad, policia y los tribunales, así como la probabilidad de que se cometan delidos y violencia.

Estimación: -2.5 a  2.5


#¿De dónde obtuve las variables?:
Data de la Organización "Human Developmet Report" (IDH) y Data base Banco Mundial (Rule of Law). Ambas están en formato CSV. 

#Año de estudio: 
2016.

#¿Por qué estamos utilizándolas?:
Considero que pueden tener una relación causal con la corrupción. Por un lado, a menores niveles de IDH mayores niveles de percepción de corrupción. Por otro lado, a menores niveles de rule of law o imperio de la ley, los niveles de percepción de la corrupción son mayores.

#Aclaración:
7344df0b-94f0-4c00-9f24-4731bff48948_Data.csv : Rule of law
Human development index (HDI).csv: IDH

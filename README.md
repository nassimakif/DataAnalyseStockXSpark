# Projet Big Data - Groupe 5 

**L'Objectif du Projet** :  <br />
Le but du projet est d'analyser des données provenant de plusieurs fichiers datasets (.csv) en utilisant les technos Hadoop/Spark.

**Données analysés** <br />
Les données analysées sont issue d'un dataset trouvable sur Kaggle.com. <br />
*Source: https://www.kaggle.com/hudsonstuck/stockx-data-contest*

Le dataset original contient environ 100 000 lignes. L'idée a été de splitter le dataset de base en 10 datasets d'environ 10 000 lignes pour apporter de la pertinence à l'usage de l'outil Spark. <br />

Les données sont trouvables ici: work/data/stockx/ <br />

**Environnement de travail** <br />
Nous avons travaillé sur Google Collab afin d'avoir un environnement propice au travail collaboratif et qui réponde à notre besoin.

**Imports liés à python** <br />

``` 
from pyspark.sql import SparkSession
spark = SparkSession.builder.getOrCreate()
import matplotlib.pyplot as plt
import numpy as np 
sc = SparkContext.getOrCreate()
from pyspark.sql import SparkSession
spark = SparkSession.builder.getOrCreate()
import matplotlib.pyplot as plt
import numpy as np
    
```

**Axes d'amélioration** <br />


**Membres du groupe** :
<br />
Jean TALGORN--THOMAS <br />
Benjamin PRADON <br />
Nassim AKIF <br />
Salim BAMBA <br />
Sophie PHOUANGSY <br />
Abdenour BENSOUNA <br />
Sarah PINTO


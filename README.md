# MovieLens_PySpark
MovieLens Dataset analysis using Hadoop and Pyspark 

## How to Run

 - Install Jupyter notebook
```pip install jupyter```

Now just write ```jupyter notebook``` in your command prompt and you will see a notebook opening in your localhost


- Install Java
Download Java and install it in your computer

Add Java to the path

Go to Program files > Java > jdk > bin

Copy the path

Go to environment variables and paste this in User variables ```"Path"```

- Setup Java
Add "JAVA_HOME" variable to environment variables

Go to Program files > Java > jdk

Copy the path and paste it in JAVA_HOME variable

- Setup Hadoop
Add ```"HADOOP_HOME"``` to environment variables

In the git repo there is hadoop folder

Copy the link to that folder

Add it to HADOOP_HOME variable

- Setup Spark
Add ```"SPARK_HOME"``` to environment variables

In the git repo there is spark zip

Unzip that 

Copy the link to that folder

Add it to ```SPARK_HOME``` variable

- Setup Pyspark
Setting up Pyspark variables

Go to environment variables and add these two 

```PYSPARK_DRIVER_PYTHON``` with value ```jupyter```

```PYSPARK_DRIVER_PYTHON_OPTS``` with value  ```notebook```

- Final Path setup
Go to Path in environment variables and add

```%SPARK_HOME%\bin```

```%HADOOP_HOME%\bin```



### Finally Go to the terminal Type ```pyspark```
and you will see Pyspark is setup and a new jupyter notebook will open with it

---

Some references to help you setup 

1. https://www.youtube.com/watch?v=cYL42BBL3Fo
2. https://www.youtube.com/watch?v=Xce3hccNf_c

spark-examples
==============

Spark examples
For more information about Apache Spark visit http://www.robertomarchetto.com

References : 

# Mesos :

install Mesos, startup Mesos and startup Slaves
https://mesosphere.com/blog/2014/07/07/installing-mesos-on-your-mac-with-homebrew/

./bin/spark-submit --class org.sparkexample.WordCount --master local[2] /Users/vramasahayam/workspace/PetProjects/spark-examples/first-example/target/first-example-1.0-SNAPSHOT.jar /Users/vramasahayam/workspace/PetProjects/spark-examples/first-example/src/test/resources/loremipsum.txt /tmp/data/dummy

# spark

http://www.robertomarchetto.com/spark_java_maven_example

1) Add this jar to the eclipse build path :  spark-assembly-1.4.0-hadoop2.4.0.jar
2)  String[] jars = {"/Users/vramasahayam/workspace/PetProjects/spark-examples/first-example/target/first-example-1.0-SNAPSHOT.jar"};
.setMaster(“mesos://localhost:5050”).setJars(jars);

https://blogs.perficient.com/multi-shoring/blog/2015/06/04/how-to-configure-eclipse-for-spark-application-in-the-cluster/

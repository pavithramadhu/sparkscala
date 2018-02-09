# sparkscala

Spark is an unified execution engine.It is easy with scala,an object oriented language which supports many features of functional programming like Lazy Evaluation ,pattern matching and so on.
Like Java,Scala source code is compiled to java bytecode,and the resulting executable code runs on JVM(Java Virtual Machine).
In Scala everything is considered as objects.Eg: Methods in Scala are considered as objects.Scala is a statically typed and dynamically inferred language.

Advantages of Spark:

Spark core supports Java 8,Scala,Phyton and R.
It's as fast 10 to 100 times when compared to mapreduce as it uses in-memory processing.
It uses single platform to handle variety of data.Spark is the replacement for map reduce.Spark enables distributed data processing through functional transformation on distributed collection of data.
 
   In spark,in -memory processing is acheived by RDD(Resilient Distributed Data).RDD is read only that's why it's called as immutable.Because of this only transformation is performed without overwriting the data.RDD acts as pointers to the partitions.They are transformed and are stored in memory or disks.
   RDD performs operations 
   1.Transformation(map,flatmap,filter,..)which acts as mapper
   2.Action(collect,count,reduce,min ,max,..)which is reducerthat does both shuffling and sorting.
   
   Lazy Transformation is done as it gets triggered and executed only when action is performed on RDD.Computations on RDD is represented as lineage Graph.There's possibility to step back and check how the output is derived from particular point i.e from the respective RDD.
   

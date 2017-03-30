# 9.1
1
. Ease of programming. It is trivial to achieve parallel execution of simple, "embarrassingly parallel" data analysis tasks. Complex tasks comprised of multiple interrelated data transformations are explicitly encoded as data flow sequences, making them easy to write, understand, and maintain.

. Optimization opportunities. The way in which tasks are encoded permits the system to optimize their execution automatically, allowing the user to focus on semantics rather than efficiency.

. Extensibility. Users can create their own functions to do special-purpose processing.

2
  Pig Latin provides all of the standard data-processing operations, such as join, filter, group by, order by, union, etc.
  Pig Latin queries are converted to Map and Reduce jobs and hence they take advantage of parallel processing.
  It has the ability to perform computations which can not be done by MapReduce.
  
3
Pig Engine – parses, optimizes, and automatically executes PigLatin scripts as a series of MapReduce jobs on a Hadoop cluster.
Importance - parsing the data.

4
Local
MapReduce

5
One of the main uses of Grunt is to enter Pig Latin in an interactive session. This can be particularly useful for quickly sampling data and for prototyping new Pig Latin scripts.

6
Pig Latin is a dataflow language. This means it allows users to describe how data from one or more inputs should be read, processed, and then stored to one or more outputs in parallel. These data flows can be simple linear flows like the word count. They can also be complex workflows that include points where multiple inputs are joined, and where data is split into multiple streams to be processed by different operators. To be mathematically precise, a Pig Latin script describes a directed acyclic graph (DAG), where the edges are data flows and the nodes are operators that process the data.

7
yes

8
Pig is called as Data flow language.

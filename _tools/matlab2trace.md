---
title: "Matlab2Trace"
excerpt: "A Matlab to Trace translator to visualise and analyse concurrent system activities and execution traces<br/>"
collection: tools
---
Matlab provides an environment to analyse and visualise data and develop algorithms. However, there is limited support for visualising and analysing system activities
executing concurrently, for instance, on a multiprocessor platform. Trace (www.esi.nl/solutions/trace/index.dot) is software that specialises in visualising and analysing
concurrent system activities and execution traces. We present a Matlab to Trace translator that directly generates a trace-input file from the Matlab environment.
Concurrent system activities and execution traces of the algorithms developed inside the Matlab environment can be visualised and analysed in Trace using the
generated trace-input file. The translator takes as input the logical or absolute starting and ending time of the algorithmic execution, and the number (and labels) of
processing cores.

TRACE visualizes concurrent activities in a Gantt-chart-like view which provides colouring, grouping and filtering options. TRACE also provides several analysis
methods, which sets it apart from the many other Gantt-chart visualization tools: i) Critical-path analysis can be used to detect tasks and resources that are bottlenecks
for performance; ii) Distance analysis can be used to compare execution traces with respect to structure, e.g. to check a model trace against an implementation trace; iii)
MTL checking provides a means to formally specify and verify properties of execution traces using Metric Temporal Logic. It is useful to express and check, for instance,
performance properties such as ``the processing latency is at most 50 ms’’; iv) The streaming performance DSL is a domain-specific language that captures often-used
performance properties for stream-processing systems (e.g., image or video processing), and which eases the use of the MTL checker; and v) The resource usage
feature can quickly give insight in the details of the resource usage.

The Matlab2Trace can be downloaded from [here](https://github.com/sajid-mohamed/Matlab2Trace).

## Contact
[s.mohamed@tue.nl](mailto:s.mohamed@tue.nl)

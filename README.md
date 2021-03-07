# CustomizeGC
# Is Customizing .NET Garbage Collector good for me?

<i>“Properly tuning GC configs for your service is a fun ride. A lot of precise public guidance / documentation is available. What’s clear though is that garbage collection can majorly impact the efficiency of your service.”</i>

# Summary
This document is not a detail deep dive into internals of .NET garbage collection however a case study of Office Collab Service’s (OCS) journey of customizing .NET garbage collector based on memory analysis of OCS processes. There are pointers to more details on each topic that this document will be touching, however the main goal is to get an idea of how we can leverage .NET garbage collector effectively to save memory and increase system throughput.

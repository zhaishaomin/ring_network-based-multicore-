# ring_network-based-multicore-
多核处理器 ;scalable ring network , four core, shared space memory ,directory-based cache coherency


Hello, everyone, this is a project from theory to practice. I would like to use this project to test the results of my study, and I am very pleased that some of friends with the common interest can actively communicate with me and learn from each other. In this project, I implemented a number issues in the simple processor  and explored some of the issues about cache consistency. I achieve Processor by using a simple five stage pipeline with simple branch prediction including BTB，RAS and BHT, instruction set is SMIPSv2 which could be found from the MIT courses resources or core_ISA.v file in the project. as for memory system part,I implement the directory ,which is supported by corresponding protocals, to achieve cache consistency rather than the bus. In order to make programming easier, I used a shared address space memory. In order to reduce the critical messages delay between cache and its parent cache  , I used the reply-forwarding protocal,whose details,however, is inspired by the MIT materias for computer architecture material. In the end, I am very grateful if you would make a good suggestion to improve my project! It is a work-in-progress and remains in active development.
I will try my best to make implemente the project well!


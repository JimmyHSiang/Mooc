##Heterogeneous Parallel Programming

This course introduces concepts, languages, techniques, and patterns for programming heterogeneous, massively parallel processors. Its content and structure has been significantly revised based on the experience gained from previous offerings. The course covers heterogeneous computing architectures, data-parallel programming models, techniques for memory bandwidth management, and parallel algorithm patterns.

###About the Course
All computing systems, from mobile to supercomputers, are becoming heterogeneous, massively parallel computers for higher power efficiency and computation throughput. While the computing community is racing to build tools and libraries to ease the use of these systems, effective and confident use of these systems will always require knowledge about low-level programming. This course is designed for students to learn the essence of low-level programming interfaces and how to use these interfaces to achieve application goals. CUDA C, with its good balance between user control and verboseness, will serve as the teaching vehicle for the first half of the course. Students will then extend their learning into closely related programming interfaces such as OpenCL, OpenACC, and C++AMP.

The course is unique in that it is application oriented and only introduces the necessary underlying computer science and computer engineering knowledge for understanding. It covers the concept of data parallel execution models, memory models for managing locality, tiling techniques for reducing bandwidth consumption, parallel algorithm patterns, overlapping computation with communication, and a variety of heterogeneous parallel programming interfaces. The concepts learned in this course form a strong foundation for learning other types of parallel programming systems. 

###Course Syllabus
Week One: Introduction to Heterogeneous Computing, Overview of CUDA C, and Kernel-Based Parallel Programming, with lab tour and programming assignment of vector addition in CUDA C.

Week Two: Memory Model for Locality, Tiling for Conserving Memory Bandwidth, Handling Boundary Conditions, and Performance Considerations, with programming assignment of simple matrix-matrix multiplication in CUDA C.

Week Three: Parallel Convolution Pattern, with programming assignment of tiled matrix-matrix multiplication in CUDA C.

Week Four: Parallel Scan Pattern, with programming assignment of parallel convolution in CUDA C.

Week Five: Parallel Histogram Pattern and Atomic Operations, with programming assignment of parallel scan in CUDA C.

Week Six: Data Transfer and Task Parallelism, with programming assignment of parallel histogram in CUDA C.

Week Seven: Introduction to OpenCL, Introduction to C++AMP, Introduction to OpenACC, with programming assignment of vector addition using streams in CUDA C.

Week Eight: Course Summary, Other Related Programming Models –Thrust, Bolt, and CUDA FORTRAN, with programming assignment of simple matrix-matrix multiplication in choice of OpenCL, C++AMP, or OpenACC.

Week Nine: complete any remaining lab assignments, with optional, bonus programming assignments in choice of OpenCL, C++AMP, or OpenACC.

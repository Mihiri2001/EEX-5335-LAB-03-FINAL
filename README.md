# EEX-5335-LAB-03-FINAL
LAB 03 FINAL


Memory System Simulator

This project is a **memory management simulator** implemented in C.  
It demonstrates key concepts of virtual memory, including:

- Translation Lookaside Buffer (TLB)
- Page Table
- Cache
- Main Memory
- Disk (backing store)

The simulator handles both read and write operations on virtual addresses, while keeping track of TLB hits/misses, cache hits/misses, page faults, and disk write-backs.



Features
- TLB lookup with FIFO replacement.
- Cache with LRU replacement.
- Page Table with page validity and dirty bit handling.
- Page Fault handling with FIFO page replacement.
- Simulated main memory and disk storage.
- Statistics for performance analysis:
  - TLB Hits / Misses
  - Cache Hits / Misses
  - Page Faults
  - Disk Writes (Write-Backs)



Assumptions
- Page size = 8 words  
- Number of virtual pages = 16  
- Number of physical frames = 4  
- Cache size = 4 lines  
- TLB size = 2 entries  
  

OPEN UBUNTU TERMINAL

ADD FILE PATH

cd /mnt/e

How to Compile

Make sure  `gcc` installed.


gcc memory_simulator_improved.c -o memory_simulator

How to Run

./memory_simulator


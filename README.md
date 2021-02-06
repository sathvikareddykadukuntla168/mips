# mips
This is a 32 bit MIPS processor design which is 5 stage pipelined with all necessary data and control hazard management blocks being built.
 
This project is built using logisim software in which we need to build gate level design and functionality of the whole processor.

# To check the result:
 1. install logisim 
 
    source: https://sourceforge.net/projects/circuit/
 2. Download the files above
 3. Check for the loaded instructions in ROM or RAM memory (If memory is seen empty please give some instructions)
 4. Now tick the clock and select a suitable frequency so that you could notice the changes seen at each stage of pipeline using the pins attached to results of each stage of pipeline
 5. At the end of execution you see that all the instructions are perfectly executed and have given correct results.

# Essence of the Project
 This project is mainly built to optimize the execution time of instructions in mips processor using the pipeline and ofcourse the problems that arises due to pipeling are solved using special blocks built.(ex: RAW dependency,control dependency,etc)
 

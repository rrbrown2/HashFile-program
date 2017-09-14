Description: Design and write a program that reads a text file and counts 
             the number of times each NON-WHITESPACE character occurs, then 
             computes a single integer (long) value based on the character 
             code and occurrence frequency of each such character.

             ***********************************************************
             ***********************************************************

Calculation: hash value = sum of products (char_code x char_frequency)

             ***********************************************************
             ***********************************************************

KEY:         The program must behave the same way as the Unix-executable
             program HashFile.run, which is stored in the course public (OP) 
             repository.

                OPcopy HashFile.run

                ./HashFile.run


NOTE:        A starter version is the OP repository file inclass1.cpp 

                OPcopy inclass1.cpp
                cp inclass1.cpp HashFile.cpp


EXAMPLE:     The file simple.dat contains:

                 Fat cat ran slow.
                 But the butterball turkey
                 got stuck on the Thanksgiving table.

             
             Program output: (note the FORMATTING--up to 10 per line, spacing)

                 SYMBOL FREQUENCIES: 
                   
                   2.    1B    1F    1T    6a    3b    2c    5e    3g    3h  
                   2i    3k    4l    4n    3o    3r    3s   11t    4u    1v  
                   1w    1y  

                 simple.dat HASH VALUE = 7037
.
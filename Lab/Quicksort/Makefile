# Start of the actual Makefile
#FLAGS = -Wall -Wconversion-null -std=c++11
FLAGS = -Wall -std=c++11
 
all:	runme 

setPermissions:
	/home/fac/msarr/public_files/set_file_permissions2.sh

sp:
	/home/fac/msarr/public_files/set_file_permissions2.sh


clean:
	rm  -f  *~ core *.log *.gch runme test functions.o logger.o binaryTree.o


runme: main.cpp  quicksort.h vt100ansi.h 
	# compile main.cpp to produce the executable "runme" link in logger.o
	g++ $(FLAGS) -o runme main.cpp  




# DO NOT DELETE THIS LINE -- make depend depends on it.





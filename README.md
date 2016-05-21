Usage:  
1. In your command line, go in source code directory.  
2. Run> chmod 777 makefile (just to make sure that you have the required permissions to go on)  
3. Run> ./makefile  
4. Run> make all  
5. Run> ./cacti C B A TECH RWP ERP EWP NSubbanks	(or ./cacti C B A TECH NSubbanks)  
  
where:  
  
C - cache size in bytes  
B - line size in bytes  
A - cache associativity  
TECH - technology generation (μm)  
RWP - read-write port  
ERP - exclusive read port  
EWP - exclusive write port  
NSubbanks - number of banks  

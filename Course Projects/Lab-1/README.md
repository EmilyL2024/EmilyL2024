
## Project Description:
-This is a Java program that processes a file containing a list of possible FQDNs (Fully Qualified Domain Name) to report on the number of unique FQDNs, 2LD (2nd Level Domain), and TLDs (Top-Level Domain) found in the file.
-To ensure the efficiency of the program, doubly linked-lists and sorted linked-lists are used for processing, and bouth of them implement the generic List interface that extends the Java Iterable interface.
-Both of the doubly linked-lists and sorted linked-lists relies on Java API LinkedList to store data. The only difference is that doubly linked-lists add items in the order they appear in the file, while sorted linked-lists add items in the sorted order.

## File Description:
-DList: doubly linked-lists implementation
-SortedList: sorted linked-lists implementation
-ProcessFQDN: main methods to execute the program and write out the results to a file

## Results:
The program will report:
 -type of list used
 -the number of FQDNs
 -the number of unique FQDNs
 -the number of unique TLDs
 -the number of unique 2LDs 
 -execution time.



# Analysis-of-CoAP-using-FlockLab

## Description
### Brief
Constrained Application Protocol (CoAP) is an application protocol for Internet of Things(IoT) and uses UDP for communication. This project aims to evaluate the performance of CoAP by using FlockLab.

### Required experience
Fundamentals of SSH and CLI

## Team Members
 1. Hardik Rana - 16CO138
 2. Amal Byju - 16CO205
 3. Harshal Shinde - 16CO223
 
## Mentors
Vishal Rathod, Mohit P. Tahiliani

## Steps to run Cooja
1. Go to contiki/tools/cooja
2. In terminal type: sudo ant jar
                     sudo ant run
                    
## Steps to compile:
1. sudo make clean TARGET=sky       //To remove any previously compiled code, this has to be done before compiling any new code
2. make TARGET=sky <program_name> //Do not enter any extension likke .c when compiling


## References
* CoAP (RFC 7252) (https://tools.ietf.org/html/rfc7252)
* Comparison of CoAP and CoCoA+ Congestion Control Mechanisms for Different IoT Application Scenarios      
  (https://ieeexplore.ieee.org/abstract/document/8024686/)
* CoCoA+: An advanced congestion control mechanism for CoAP
  (https://www.sciencedirect.com/science/article/pii/S1570870515000888)



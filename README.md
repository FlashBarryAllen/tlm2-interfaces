# TLM2 interfaces

TLM2 based interface definitions for AMBA AXI, ACE and CHI protocol compliance. The files allow development against a standard interface definition which will be compliant with other vendor-provided semiconductor IP models, for example, network-on-chip (NoC) interconnect models generated by Arteris IP products.

For installation, follow these steps:

mkdir build 
cmake -DCMAKE_PREFIX_PATH=$SYSTEMC_HOME ..  
make install 


The library depends on IEEE 1666-2011 SystemC and is tested against SystemC version 2.3.3 with gcc-6.3. Other combinations will most likely also work. SystemC libraries are available for download at https://www.accellera.org/downloads/standards/systemc.



# ATPG-DFT
Test pattern Generation for comb ckts
problem statements

Instructions

PART I

Choice of Tools

● You need to use the following tool: 

Name of the tool: Atalanta ATPG

(This tool is might already be installed on the lab machines (not on EDAserver). You may check 

if it is already installed)

Where and how to download? GitHub Project: https://github.com/hsluoyz/Atalanta

How to install? follow the ReadMe file attached or the steps

mentioned in the Github project ReadMe

How to run? atalanta -A -u -v example_netlist.v.bench

● You can use any technology library (if required)

 Fig 1
 example ckt:
ckt: (( A OR B ) NAND C ) NOR (C AND D)

The tool takes input in a “bench” format. This format is simple and straightforward. For the 

circuit shown in Fig. 1, the bench file is as follows.

Bench Netlist (example.v.bench file)

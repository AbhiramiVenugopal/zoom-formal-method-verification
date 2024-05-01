# zoom-formal-method-verification
-- CADP (CONSTRUCTION AND ANALYSIS OF DISTRIBUTED PROCESSES)
-- http://cadp.inria.fr

-- Authors : Abhirami Venugopal and Sayed Mohammed

[Last updated: Wed April 14 14:16:09 CET 2024]

This directory contains an example for SVL, LTS, MCL. It describes how zoom video calling application can schedule/cancel meetings, send messages and facilitate direct calls in LTS. 

The whole verification scenario is described and commented in the file 
"demo.svl". It can be executed by typing:
$	svl demo
or even simply 
$	svl

After execution of the SVL scenario, all generated files can be removed by 
typing
$	svl -clean demo
or even simply
$	svl -clean

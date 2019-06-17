The directory contains the acg files for running examples from ""

To run the examples, one needs the acgc.opt (or acgc) and acg.opt (or
acg) binaries. The software (called the ACG toolkit) and the installation procedure can be
loaded at: http://acg.loria.fr
Alternatelively, one can run the ACG toolkit using nix-shell.


After installing the ACG toolkit, one way to run examples is the following.

1. 
    acgc.opt amr.acg

2. 
    acg.opt 

3. 
    load o amr.acgo;

4.  

    evhol_sem realize Closure (C_sleeps I_s I_vp (C_man C_a)) : T;
This repository contains material for the Oct 9-11 EIC workshop at ANL.  The main goal is the use of Zgoubi to compute
the Derbenev-Kondratenko depolarization time integral.

jleicn0track.dat is the zgoubi file that computes dn/d\delta for jleic.  It has an include statemnt
jleic_vma_FIT.dat [MARK,COMPLETE_RING$START:MARK,COMPLETE_RING$END]

To use with another lattice, this line needs to be replaced and the appropriate labels need to be inserted in the accompanying
zgoubi lattice file.  That file is typically constructed to compute the Twiss parameters of the lattice, so that one can
check to make sure it has the right linear lattice.
# cimmsim-exe
C-ImmSim Linux executable

This material is relative to the paper (Castiglione et al., 2019) available at
https://www.frontiersin.org/articles/10.3389/fimmu.2019.01513/full

It contains the executable of the immune system simulator called C-ImmSim compiled for Intel/Linux machines:

cimmsim: ELF 64-bit LSB executable, x86-64, version 1 (SYSV), dynamically linked, 
interpreter /lib64/ld-linux-x86-64.so.2, for GNU/Linux 2.6.32, 
BuildID[sha1]=e3c73509535be14ba88692ffb14f2b9c86329938, not stripped

To execute it type :
	cimmsim -f d?

where d? is one of d0, ..., d8


The results will be in the folder OUTDIR/ORGAN_0

For a description of the content of the files refer to related publications. 
ASCII space-separated files *-details* contain the most important cumulative 
information. One file for each agent-cellular entity.
Each file has a header that describes its content.

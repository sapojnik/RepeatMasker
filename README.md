
```
RepeatMasker
Developed by Arian Smit and Robert Hubley
Please refer to: Smit, AFA, Hubley, R. & Green, P "RepeatMasker" at
http://www.repeatmasker.org

The github 'master' branch is no longer a development branch.  It
now represents the current release of RepeatMasker.  All development
is done on a seperate 'development' branch and should not be 
considered stable.  Official distributions of RepeatMasker may be
found at: http://www.repeatmasker.org/RMDownload.html
```

RepeatMasker
------------

RepeatMasker is a program that screens DNA sequences for interspersed
repeats and low complexity DNA sequences. The output of the program is
a detailed annotation of the repeats that are present in the query
sequence as well as a modified version of the query sequence in which
all the annotated repeats have been masked (default: replaced by
Ns). Sequence comparisons in RepeatMasker are performed by the program
cross_match, an efficient implementation of the Smith-Waterman-Gotoh
algorithm developed by Phil Green, or by WU-Blast developed by Warren
Gish.

See "INSTALL" for instructions on how to install RepeatMasker.
See "repeatmaker.help" for a detailed program manual.

Libraries Overview
------------------

Updates of the RepeatMasker program are distributed with a copy of the
Dfam database ( www.dfam.org ). Dfam is a small but growing "open" 
databases of Transposable Element seed alignments, profile Hidden 
Markov Models and consensus sequences.

RepeatMasker is also compatible with the RepBase database managed by 
the Genetic Information Research Institute and requires a license to 
use. Up until 2019 we maintained the "Repbase RepeatMasker Edition" 
libraries as co-editor of RepBase Update.  For newer versions of 
RepBase users will need to use the sequences in FASTA format with
RepeatMasker's "-lib" option.

RepeatMasker "open-4.0" and later versions are distributed under the
Open Source License.  Please read LICENSE file for more information.


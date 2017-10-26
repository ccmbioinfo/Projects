# Become a seqr specialist and help to bring seqr into variant interpretation in our lab
Variant (mutation) interpretation is a crucial step in diagnosing patients with rare Mendelian diseases.
[Seqr](https://github.com/macarthur-lab/seqr) is an open source web-portal developed in Daniel MacArthur lab.
We want to use seqr in our projects, but we need some modifications of seqr. The project will be to learn
the seqr code, and modify it to add some annotations. Also you will be responsible to load variants from 
our projects to seqr and, hopefully, find a way to speed up the loading process (mongodb). Another aspect is to master
the interaction between [Phenotips](https://github.com/phenotips/phenotips) and Seqr systems.

# Mendelian rna seq + crt
Less than 50 % of patients with Mendelian diseases receive a diagnosis using Whole Exome Sequencing (WES).
There are many efforts to improve the diagnostic rate: using RNA-seq, WGS, or matching patients across the globe.
We are trying to use RNA-seq, i.e. expression and splicing analysis, basing on [bcbio RNA-seq pipeline](https://github.com/chapmanb/bcbio-nextgen) 
and [MendelianRNA-seq](https://github.com/berylc/MendelianRNA-seq) scripts from MacArthur lab. We already introduced some
improvements into [MendelianRNA-seq](https://github.com/naumenko-sa/MendelianRNA-seq-DB),namely, fixed some bugs, and used the database of junctions instead of running junction discovery in the controls every time. Your project will be to help merging [crt](https://github.com/naumenko-sa/crt) code with [MendelianRNA-seq-DB](https://github.com/naumenko-sa/MendelianRNA-seq-DB), and make further improvements.

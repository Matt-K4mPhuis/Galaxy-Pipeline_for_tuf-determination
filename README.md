# Galaxy Pipeline for the determination of Staphylococcus species utilizing the tuf gene.
This pipeline uses the open source, web-based platform for data intensive biomedical research called Galaxy.
The pipeline is specificly designed to work with FastQ data that was acquired through the amplification of the tuf gene using custom primers and sequencing the products through MiniSeq(Illumina). Furthermore, an internal control is also added during the lab protocol and later removed by the pipeline. when this Internal control and specificly used primers are not added, the pipeline will indicate a error and not finish the analysis.
# Equipment used in Lab Protocols
-PCR
Quantstudio 4(Illumina)
Primersets: 
FW: 5'GCTGAAGCTGGTGACAACAT'3
RV: 5'CCAGTTACGTCAGTAGTACGGA'3
Internal control: 5'TGGTGCATGCTTACGTGGTGTTGCTAGTGAAGACGTACAACGTAGTCAAGCATTAGCTGCTCCTGGTTCAATTATACCAGATACTGAATTCACAGCAGAAGTATACGTATTATCACGAGACGAAGATGGACGTCACACTCCATGCTTCTCAGACTATCGTCCACAATTCTATT"
-Sequencing
Miniseq(Illumina)
150bp

# Tools used in Pipeline
1. make.contigs
2. trim.seqs
3. summary.seqs
4. cutadapt
5. replace
6. unique.seqs
7. fasta-tabular
8. remove columns
9. Cut (columns from a table)
10. Remove beginning
11. paste two files side
12. sort
13. add column
14. table compute
15. Arithmetic Operations
16. advanced cut
17. tabular to fasta
18. add header 
19. NCBI blast + reference 
20. filter
21. histogram


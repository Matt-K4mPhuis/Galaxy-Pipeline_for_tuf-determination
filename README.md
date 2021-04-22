# Galaxy Pipeline for the determination of Staphylococcus species utilizing the tuf gene.
This pipeline uses the open source, web-based platform for data intensive biomedical research called Galaxy.
The pipeline is specificly designed to work with FastQ data that was acquired through the amplification of the tuf gene using custom primers and sequencing the products through MiniSeq(Illumina). Furthermore, an internal control is also added during the lab protocol and later removed by the pipeline. when this Internal control and specificly used primers are not added, the pipeline will indicate a error and not finish the analysis.
# Equipment used in Lab Protocols
-PCR
Quantstudio 4(Illumina)
Primersets: 
FW 5'
RV 5'
Internal control: 5'
-Sequencing
Miniseq(Illumina)
150bp

# Tools used in Pipeline

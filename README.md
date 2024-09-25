**Data** 
Raw .fastq files for all BBA-seq mouse and sheep samples, measuring methylation at cg21524116 
Accompanying “SampleInfo.xlsx” file outlining all sample details - age, sex, castration status, treatment, etc. 

**AIC_linearmodels.Rmd**
R script, using Akaike Information Criterion to evaluate models built with 1-20 asDMP sites

**ModelMice.Rmd**
R script, concerns the analysis of C-DHT, PNA and ARKO mouse models

**MouseAndrogenClock.Rmd**
R script, construction of the mouse androgen clock using published mouse array data (A. T. Lu, et al., Universal DNA methylation age across mammalian tissues. Nat. aging 3, 1144–1166 (2023), and A. Haghani, et al., DNA methylation networks underlying mammalian traits. Science (80-. ). 381 (2023))

**SheepAndrogenClockConstruction_CrossPlatform_Compare.Rmd**
R script, comparison of sheep androgen clock models built with data from one methylation profiling platform and tested on the other (i.e., BBAseq vs array), demonstration of methylation adjustment

**SheepAndrogenClock_Array.Rmd**
R script, construction of the sheep androgen clock using published sheep array data (V. J. Sugrue, et al., Castration delays epigenetic aging and feminizes DNA methylation at androgen-regulated loci. Elife 10, e64932 (2021))

**SheepAndrogenClock_BBAseq.Rmd**
R script, construction of the sheep androgen clock using sheep BBAseq data

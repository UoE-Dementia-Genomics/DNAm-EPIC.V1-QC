# DNA methylation QC pipeline
You can use this scripts to do general QC on DNA methylation data (EPIC V1) using R Markdown. To run this pipeline you only need to set your input arguments in `QC_Config.txt` file and then run the following command:

`bash RunQC.sh QC_Config.txt`

You can submit it as a job in `slurm` by replacing `bash` with `sbatch` in the previous command.

# Requiered R packages:

```
methylumi
wateRmelon
FlowSorted.Blood.EPIC
gdata
minfi
ggplot2
require(gridExtra
glmnet
yarrr
IlluminaHumanMethylationEPICmanifest
tidyr
dplyr
gplots
colorRamps
IlluminaHumanMethylationEPICanno.ilm10b2.hg19
IlluminaHumanMethylationEPICanno.ilm10b4.hg19
IlluminaHumanMethylation450kmanifest
FlowSorted.DLPFC.450k
FlowSorted.Blood.450k
FlowSorted.CordBlood.450k
```



Try this command:

    seqpipe -m ../bwa.pipe bwa_map PICARD_JAR=/path/to/picard.jar \
        REF=MT.fa FQ1=r1.fq.gz FQ2=r2.fq.gz SAI1=r1.sai SAI2=r2.sai BAM=out.bam SORT_BAM=out.sort.bam

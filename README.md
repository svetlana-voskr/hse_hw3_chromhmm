# hse_hw3_chromhmm
[Ссылка на colab](https://colab.research.google.com/drive/15umUh2vXqvAk3fWwrGRBwJZNNDFFmy-f?usp=sharing)
# Часть 1

Клеточная линия, рассматриваемая в Дз2 (IMR-90), не содержит ChIP-seq эксперименты в рассматриваемых гистоновых метках
![](./img/noIMR.png)
Поэтому для этого дз будет рассматриваться HepG2.

## Список гистоновых меток

| Гистоновая метка | Ссылка |
|------------------|--------|
|   H2AFZ          |    http://hgdownload.cse.ucsc.edu/goldenPath/hg19/encodeDCC/wgEncodeBroadHistone/wgEncodeBroadHistoneHepg2H2azStdAlnRep1.bam    |
|   H3K4me1        |    http://hgdownload.cse.ucsc.edu/goldenPath/hg19/encodeDCC/wgEncodeBroadHistone/wgEncodeBroadHistoneHepg2H3k04me1StdAlnRep1.bam    |
|   H3K9me3        |    http://hgdownload.cse.ucsc.edu/goldenPath/hg19/encodeDCC/wgEncodeBroadHistone/wgEncodeBroadHistoneHepg2H3k09me3AlnRep1.bam    |
|   H3K4me2        |    http://hgdownload.cse.ucsc.edu/goldenPath/hg19/encodeDCC/wgEncodeBroadHistone/wgEncodeBroadHistoneHepg2H3k4me2StdAlnRep1.bam    |
|   H3K9ac         |    http://hgdownload.cse.ucsc.edu/goldenPath/hg19/encodeDCC/wgEncodeBroadHistone/wgEncodeBroadHistoneHepg2H3k9acStdAlnRep1.bam    |
|   H3K27ac        |    http://hgdownload.cse.ucsc.edu/goldenPath/hg19/encodeDCC/wgEncodeBroadHistone/wgEncodeBroadHistoneHepg2H3k27acStdAlnRep1.bam    |
|   H3K36me3       |    http://hgdownload.cse.ucsc.edu/goldenPath/hg19/encodeDCC/wgEncodeBroadHistone/wgEncodeBroadHistoneHepg2H3k36me3StdAlnRep1.bam    |
|   H3K79me2       |    http://hgdownload.cse.ucsc.edu/goldenPath/hg19/encodeDCC/wgEncodeBroadHistone/wgEncodeBroadHistoneHepg2H3k79me2StdAlnRep1.bam    |
|   H4K20me1       |    http://hgdownload.cse.ucsc.edu/goldenPath/hg19/encodeDCC/wgEncodeBroadHistone/wgEncodeBroadHistoneHepg2H4k20me1StdAlnRep1.bam    |
|   H3K27me3       |    http://hgdownload.cse.ucsc.edu/goldenPath/hg19/encodeDCC/wgEncodeBroadHistone/wgEncodeBroadHistoneHepg2H3k27me3StdAlnRep1.bam    |

## cellmarkfiletable.txt

[Файл](./cellmarkfiletable.txt)

## ChromHMM
[Папка с выдачей](./ChromHMM/)

| |  |
|------------------|--------|
|   ![](./ChromHMM/emissions_10.png)    |    ![](./ChromHMM/HepG2_10_overlap.png) |
|   ![](./ChromHMM/HepG2_10_RefSeqTES_neighborhood.png)       |  ![](./ChromHMM/HepG2_10_RefSeqTSS_neighborhood.png)   |

## Эпигетические типы

| Состояние | Название |Встречаемость в гистоновых модификациях| Описание | Изображение из USCC |
|-----------|----------|------|----------|---------------------|
|     1     |          |  во всех, но чаще всего: <ul><li> H2AFZ <ul><li> H3K4me1 <ul><li> H3K4me2 <ul><li> H3K4me3 <ul><li> H3K9ac <ul><li> H3K27ac <ul><li> H3K79me2  |    |        ![](./img/1.png)              |
|     2     |          |      |    |        ![](./img/2.png)              |
|     3     |          |      |    |        ![](./img/3.png)              |
|     4     |          |      |    |        ![](./img/4.png)              |
|     5     |          |      |    |        ![](./img/5_.png)              |
|     6     |          |      |    |        ![](./img/6.png)              |
|     7     |          |      |    |        ![](./img/7.png)              |
|     8     |          |      |    |        ![](./img/8.png)              |
|     9     |          |      |    |        ![](./img/9.png)              |
|    10     |          |      |    |        ![](./img/10.png)              |


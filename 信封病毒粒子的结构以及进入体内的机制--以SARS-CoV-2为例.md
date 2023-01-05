资料整理

## 信封病毒粒子的结构以及进入体内的机制--以SARS-CoV-2为例
                                      by wuzengding 2023/1/4
****

### SARS-CoV-2的基因组结构及对应编码的蛋白

SARS-COV-2的基因组（genome）是一个完整的postive-sense 的单链RNA，长度大约30kb，具有5‘-cap结合和3’-poly-A 尾。该病毒基因组编码了29个蛋白，其中25个为非结构性蛋白（Non-structural proteins : NSPs）或辅助蛋白(accessory proteins)，4个为结构性蛋白。【1】

其中**NSPs蛋白**由基因组5‘-end的大约2/3区域编码。有两个开放阅读框Orf1a 和Orf1b，有意思的是Orf1b是由于-1 Ribosomal Frameshift导致的（关于Ribosomal Frameshift，见参考文献【2】）

![](https://github.com/wuzengding/images_for_md/blob/main/2023-01-05-10-46-03-image.png)

<font size=2>图1a 是 SARS-CoV-2的完整基因组结构图，5’-端是是编码NSPs的Orf1a/Orf1ab，3‘-端 是编码结构蛋白; 图1b是ribosomal framshift元件的二级结构示意图；图1c 是Orf1a 和NSPs的两个pp1a和pp1ab蛋白结构示意图</font>

其中**结构性蛋白**分为核壳蛋白（nucleocapsid: N）、刺突蛋白（spike: S）、膜蛋白（membrance：M）、信封蛋白（envelope：E）

![](https://github.com/wuzengding/images_for_md/blob/main/2023-01-05-10-45-41-image.png?msec=1672928528581)

![](https://github.com/wuzengding/images_for_md/blob/main/2023-01-05-10-44-11-image.png?msec=1672928528580)

<font size=2> 图2. 结构性蛋白的示意图。结构蛋白大约在基因组的3’-端1/3的位置编码。除了S/E/M/N蛋白，还编码了辅助蛋白（绿色部分）</font>

****
### SARS-CoV-2的病毒粒子结构

施一公2020年解析了SARS-CoV-2病毒粒子的结构【3】，获得了5A级别的分辨率。病毒粒子直径在60-90nm之间。在Cryo-EM下，病毒粒子的Spike蛋白和RNPs是最显著的特征。

![](https://github.com/wuzengding/images_for_md/blob/main/2023-01-05-11-11-07-image.png?msec=1672928528597)

将病毒粒子简化为图4模型【4】。可以看到病毒粒子由四种结构蛋白组成，分别是Spike糖蛋白、核蛋白复合物（RNPs）、信封蛋白、膜蛋白组成。其中RNPs充满了病毒粒子的内部，Spike蛋白分布在病毒粒子的表面，信封蛋白和膜蛋白包裹了RNPs并且为Spike蛋白提供了锚定支架。

![](https://github.com/wuzengding/images_for_md/blob/main/2023-01-05-11-16-26-image.png?msec=1672928528588)
****
### SARS-CoV-2的感染生命周期

第一步：SARS-CoV-2病毒在人体受体细胞表面的TMPRSS2的辅助下，通过刺突蛋白Spike结合到受体细胞表面的ACE2受体。一旦Spike蛋白结合ACE2受体后，病毒粒子的Spike蛋白发生构象改变，进一步驱动病毒粒子和受体细胞进行融合；

第二步：病毒粒子和受体细胞融合后，病毒粒子释放病毒viral RNA进入到受体细胞内部；

第三步：病毒viral RNA在劫持宿主细胞，利用宿主细胞的蛋白表达系统，来翻译viral RNA 基因组的NSPs区域，得到的pp1a和pp1ab蛋白。然后通过病毒编码表达产生的main protease和 papain-like protease两种蛋白酶，将pp1a和pp1ab这两个前提蛋白切割，得到16种成熟的NSPs蛋白；

第四步：上一步合成的NSPs蛋白组组装澄复制和转录复合物（replication and transcription complex : RTC），RTC在宿主体内以viral RNA 的原始正链（+Strand）为模板启动病毒 viral RNA 转录，得到全长的负链（-Strand）的Viral RNA 序列。这个过程是重复的，所以最终得到大量的全长负链（-Strand）Viral RNA的基因组；

第五步：与第四步相反，现在以得到的全长负链（-Strand）Viral RNA为模板，进行转录又得到全长正链（+Strand）Viral RNA。这个过程也是重复的，所以第四、五步就会在宿主细胞内复制得到大量的全长正链（+Strand）Viral RNA，也就是病毒的基因组；

第六步：正链（+Strand）Viral RNA 中负责编码结构蛋白的区域，转录得到核壳蛋白（N）、刺突蛋白（ S）、膜蛋白（M）、信封蛋白（E）对应的mRNA。然后细胞内的核糖体又以这四种mRNA为模板，表达翻译得到结构蛋白: 核壳蛋白（N）、刺突蛋白（ S）、膜蛋白（M）、信封蛋白（E）以及辅助蛋白;

第七步：第六步生产的刺突蛋白（ S）、膜蛋白（M）、信封蛋白（E）以及辅助蛋白，脱离核糖体后，在宿主细胞内质网中穿梭转运至达高尔基体中，并在高尔基体中进行组装和加工，从而形成成熟的刺突蛋白（ S）、膜蛋白（M）、信封蛋白（E）；

第八步：然后这些蛋白去包裹和封装第五步产生的全长正链（+Strand）Viral RNA，也就是包裹病毒的基因组。从而得到一个新的成熟的SARS-CoV-2病毒粒子；

第九步：新的成熟的SARS-CoV-2病毒粒子跨过宿主细胞膜，被释放到宿主细胞外，然后进一步寻找新的宿主细胞来感染。并重新计入第一步。下图4是SARS-CoV

![The infection cycle of SARSCoV2](https://www.invivogen.com/sites/default/files/pictures/01-covid-spotlight-invivogen.png)
****
### SARS-CoV-2的Spike蛋白结构
整理中
****

### 参考文献

*1.Wu, Cr., Yin, Wc., Jiang, Y. et al. Structure genomics of SARS-CoV-2 and its Omicron variant: drug design templates for COVID-19. Acta Pharmacol Sin **43**, 3021–3033 (2022). https://doi.org/10.1038/s41401-021-00851-w*

*2.[Ribosomal frameshift - Wikipedia](https://en.wikipedia.org/wiki/Ribosomal_frameshift)*

*3.https://doi.org/10.1016/j.cell.2020.09.018*

*4.[COVID-19 | Infection Cycle | InvivoGen](https://www.invivogen.com/spotlight-covid-19-infection)*

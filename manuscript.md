---
author-meta:
- Sharik Hernandez
- null
bibliography:
- content/manual-references.json
date-meta: '2020-05-30'
header-includes: '<!--

  Manubot generated metadata rendered from header-includes-template.html.

  Suggest improvements at https://github.com/manubot/manubot/blob/master/manubot/process/header-includes-template.html

  -->

  <meta name="dc.format" content="text/html" />

  <meta name="dc.title" content="3D tumor spheroids" />

  <meta name="citation_title" content="3D tumor spheroids" />

  <meta property="og:title" content="3D tumor spheroids" />

  <meta property="twitter:title" content="3D tumor spheroids" />

  <meta name="dc.date" content="2020-05-30" />

  <meta name="citation_publication_date" content="2020-05-30" />

  <meta name="dc.language" content="en-US" />

  <meta name="citation_language" content="en-US" />

  <meta name="dc.relation.ispartof" content="Manubot" />

  <meta name="dc.publisher" content="Manubot" />

  <meta name="citation_journal_title" content="Manubot" />

  <meta name="citation_technical_report_institution" content="Manubot" />

  <meta name="citation_author" content="Sharik Hernandez" />

  <meta name="citation_author_institution" content="Department of" />

  <meta name="citation_author_orcid" content="XXXX-XXXX-XXXX-XXXX" />

  <meta name="twitter:creator" content="@None" />

  <meta name="citation_author" content="None" />

  <meta name="citation_author_institution" content="Department of" />

  <meta name="citation_author_institution" content="Department of" />

  <meta name="citation_author_orcid" content="XXXX-XXXX-XXXX-XXXX" />

  <link rel="canonical" href="https://SharikHR.github.io/review/" />

  <meta property="og:url" content="https://SharikHR.github.io/review/" />

  <meta property="twitter:url" content="https://SharikHR.github.io/review/" />

  <meta name="citation_fulltext_html_url" content="https://SharikHR.github.io/review/" />

  <meta name="citation_pdf_url" content="https://SharikHR.github.io/review/manuscript.pdf" />

  <link rel="alternate" type="application/pdf" href="https://SharikHR.github.io/review/manuscript.pdf" />

  <link rel="alternate" type="text/html" href="https://SharikHR.github.io/review/v/f32698fa976996f319d0d54cdd86d48988b20093/" />

  <meta name="manubot_html_url_versioned" content="https://SharikHR.github.io/review/v/f32698fa976996f319d0d54cdd86d48988b20093/" />

  <meta name="manubot_pdf_url_versioned" content="https://SharikHR.github.io/review/v/f32698fa976996f319d0d54cdd86d48988b20093/manuscript.pdf" />

  <meta property="og:type" content="article" />

  <meta property="twitter:card" content="summary_large_image" />

  <link rel="icon" type="image/png" sizes="192x192" href="https://manubot.org/favicon-192x192.png" />

  <link rel="mask-icon" href="https://manubot.org/safari-pinned-tab.svg" color="#ad1457" />

  <meta name="theme-color" content="#ad1457" />

  <!-- end Manubot generated metadata -->'
keywords:
- markdown
- publishing
- manubot
- 3D
- spheroid
- cancer
lang: en-US
manubot-clear-requests-cache: false
manubot-output-bibliography: output/references.json
manubot-output-citekeys: output/citations.tsv
manubot-requests-cache-path: ci/cache/requests-cache
title: 3D tumor spheroids
...






<small><em>
This manuscript
([permalink](https://SharikHR.github.io/review/v/f32698fa976996f319d0d54cdd86d48988b20093/))
was automatically generated
from [SharikHR/review@f32698f](https://github.com/SharikHR/review/tree/f32698fa976996f319d0d54cdd86d48988b20093)
on May 30, 2020.
</em></small>

## Authors



+ **Sharik Hernandez**<br>
    ![ORCID icon](images/orcid.svg){.inline_icon}
    [XXXX-XXXX-XXXX-XXXX](https://orcid.org/XXXX-XXXX-XXXX-XXXX)
    · ![GitHub icon](images/github.svg){.inline_icon}
    [SharikHR](https://github.com/SharikHR)<br>
  <small>
     Department of
     · Funded by Grant XXXXXXXX
  </small>

+ **None**<br>
    ![ORCID icon](images/orcid.svg){.inline_icon}
    [XXXX-XXXX-XXXX-XXXX](https://orcid.org/XXXX-XXXX-XXXX-XXXX)<br>
  <small>
     Department of; Department of
  </small>



## Abstract {.page_break_before}

A hallmark of pancreatic ductal adenocarcionoma (PDAC) is a pronounced collagen-rich fibrotic extracellular matrix known as the desmoplastic reaction. The absence of appropriate models capable of reproducing *in vitro* the heterogeneous tumor microenvironment of pancreatic cancer makes its study difficult and conventional culture approaches do not mimic the characteristics of tumors. Multicellular spheroids (MCS) have emerged as a powerful tool to narrow down the gap between the *in vitro* and *in vivo* model. In this review, we discussed the structure and biology of MCS and detailed fabricating methods, as well as the models currently in use for the study of the heterogeneous microenvironment of pancreatic cancer. 


## Introduction

Pancreatic cancer belongs to the top ten of cancer-related deaths in the world @url:https://gco.iarc.fr and the poor prognosis is primarily due to its advanced stage at diagnosis , the progress in it's treatment remains too slow as a consequence of the complex physiopathology of this tumor.
The most common type of pancreatic cancer is pancreatic ductal adenocarcinoma (PDAC) characterized by a heterogeneous cellular composition and the accumulation of a very dense fibrotic tissue @doi:10.1158/1078-0432.CCR-11-3114.
Due to that pancreatic cancer is a heterogeneous disease, is often modelled using established cell lines in the laboratory.

Two dimensional (2D) monocultures of isolated cancer cells do not show any structural architecture and lack the complex physiology and the microenvironment of real tumor tissues such as fibroblasts, macrophages, endothelial cells, immune cells which are embedded in an extracellular matrix (ECM) @doi:10.1186/s13058-016-0740-2. Gene expression and signalling pathways are altered during monolayer conditions when compared to cells grown in the native tumor tissue [@doi:10.1186/s12885-018-4145-8; @doi:10.3892/or.2016.4581]. Moreover, when cells are growing in monolayer they do not replicate cell-to-cell and cell-to-ECM interactions, and the oxygen and pH gradients @doi:10.3390/ijms16035517.
However, there is an urgent need to make the use of models capable of closely mimicking the heterogeneity and the microenvironment of the in vivo conditions.

In recent years, three-dimensional (3D) culture systems have gained increasing recognition as an effective tool for biological research. One widely used 3D culturing technique is the application of multicellular spheroids (MCS).Cells cultured in 3D more closely mimic the physiological environment compared to conventional monolayer culture systems. Spheroids are three-dimensional spherical cellular aggregates with high cell-density, that more closely simulate conditions existing in solid tumors where hypoxia and alterations related to intracellular metabolism occur due to poor availability of nutrients from blood vessels @doi:10.1371/journal.pone.0177737.

Aiming to face this issue, this review will provide an overview of the application of multicellular spheroids, the widest employed 3D tumor model so far, for the evaluation of cancer. Finally, relevant examples of models in which MCS have been included in pancreatic cancer research are described.


## Pancreatic tumor microenvironment

In Pancreatic ductal adenocarcinoma (PDAC), the major components of the tumor microenvironment are a complex population of fibroblasts forming the bulk of the stroma, vasculature, inflammatory and immune cells @doi:10.1002/jcb.21209.
PDAC is associated with evolving alterations in the tumor microenvironment, including increasing fibrosis and extracellular matrix deposition (desmoplasia). Increasing desmoplasia accompanies progressive disease and creates intratumoral pressure that compresses the vasculature, resulting in limited blood flow to the tumor and consequent hypoxia and low nutrient delivery @doi:10.1158/2159-8290.CD-15-0671.

Interactions between the neoplastic and non-neoplastic cells and cellular matrix have been proposed to stimulate the extensive desmoplastic reaction. Stroma production is promoted by the activation of multiple cell signalling pathways [@doi:10.1002/ijc.22178; @doi:10.1002/mc.20827] these signalling cascades lead to secretion of structural matrix components including proteoglycans, collagen and fibronectin and the activation of catalytic enzymes such as proteinases.

PDAC tumours are enriched in collagen where cancer cells form gland-like structures, the main collagen proteins found in human PDAC are collagens I and IV @doi:10.1038/ncomms16031. Collectively, had been demostrated PDAC extracellular matrix also represents a nutrient reservoir for tumour cells when other fuels are limited @doi:10.1038/ncomms16031.

The interstitial matrix-associated collagens I/III, the basement membrane-associated collagen IV and the glycosaminoglycan hyaluronan have been found expressed at high levels in primary tumors and metastatic lesions in pancreatic cancer and are associated with poor survival[@doi:10.1158/1078-0432.CCR-14-1051]. Likewise, collagen type V is expressed by pancreatic stellate cells in the stroma of pancreatic ductal adenocarcinoma and promotes the malignant phenotype in pancreatic cancer cell lines @doi:10.1016/j.canlet.2014.10.020. In contrast, collagen XV a secreted non-fibrillar collagen reduces invasion of pancreatic adenocarcinoma cells therefore hab been proposed as a tumor suppressor in the basement membrane zone [@doi:10.1371/journal.pone.0072250; @doi:10.1089/104454903321908601].

The laminins are a family of extracellular matrix glycoproteins localized in the basement membrane that separates epithellal cells from the underlying stroma. They are involved in several biological processes including cell-matrix, cell growth, migration, tumour growth and metastases @doi:10/bxqv94.

Laminin-332 is a major member of the laminin family, consisting of α3, β3, and γ2 chains, encoded by the LAMA3, LAMB3, and LAMC2 genes, respectively. Laminin subunit beta-3 (LAMB3) is upregulated in PDAC and suppressing its expression reduces cell proliferation, invasion, and migration by downregulating epithelial‒mesenchymal transition (EMT)-related proteins (N-cadherin, vimentin, Snail, Slug) by regulation of PI3K/Akt signaling pathway @doi:10.1038/s41419-019-1320-z; @doi:10.3892/ol.2018.8678. Besides, the expression of laminin subunits LAMA3 and LAMC2 are upregulated with a favorable ability of distinguishing between PDAC and non-tumor tissues @doi:10.18632/aging.102007; @doi:10.3892/ol.2018.8678; @doi:10.1074/mcp.M112.023507. 

Fibronectin is an extracellular matrix ECM glycoprotein that supports cell-ECM interactions and is crucial for wound healing response, development, and maintaining tissue homeostasis @doi:10.1016/j.canlet.2015.12.027. Moreover,fibronectin is an extracellular protein that is upregulated in pancreatic cancer and confers chemoresistance and metastasis [@doi:doi.org/10.1186/s12885-019-5803-1; @doi: 10.1186/s12957-019-1574-z]. 
Fibronectin induces distinct signals that promote survival and migration of PDAC cells @doi:10.1016/j.canlet.2015.12.027.Cell surface integrins are the most well characterized receptors for fibronectin. Fibronectin binds to integrin receptors (α5β1), thereby activating the FAK pathway [@doi:10.1126/science.285.5430.1028; @doi:10.1016/s0002-9440(10)65005-5]. These signals regulates cellular responses such as survival, proliferation, differentiation, adhesion and migration @doi:10.1242/jcs.018093; @doi:10.1242/jcs.01014. 

Matrix metalloproteinases (MMPs) are a family of zinc-dependent endopeptidases, they are involved in degradation of the extracellular matrix . MMPs support tissue remodeling and stimulate neovascularization and inflammatory response, both in physiological and in pathological conditions, for example, in tumors @doi:10.1006/cbir.2000.0647.

MMP-2, MMP-7, and MMP-9 expressions correlate with various morphological features of the PDAC tumor such as inflammation, necrosis, and formation of the new blood vessels @doi:10.1155/2016/9895721 and their tissue inhibitors (TIMPs) TIMPs 1–3 compared with normal pancreas @doi:10.1158/1078-0432.CCR-1157-03.

Pancreatic stellate cells (PSC) are responsible for desmoplasic generation @doi:10.1111/cas.13847. The activation of PSC from a quiescent to an activated state is an intercellular stimuli from tumor‐stromal interactions. PCS can be transform into myofibroblast‐like cells, which express α‐smooth muscle actin (α‐SMA) as cancer‐associated fibroblasts (CAF) [@doi:10.1053/j.gastro.2012.11.037; @doi:10.1053/j.gastro.2010.05.084]. 

CAF are important components of tumor stroma and affect cancer growth, survival, metastasis, angiogenesis and resistance to chemotherapy or radiotherapy through various cytokines @doi:10.2217/fon.15.176, and contribute to a diminished immune function @doi:10.3389/fimmu.2019.00847.

	



## 2D and 3D cell culture

Cell culture is a widely used *in vitro* tool to improve the understanding of cell biology, cellular mechanisms, tissue morphology, drug action, protein production and the development of tissue engineering @doi:10.5114/aoms.2016.63743.

Three-dimensional (3D) cell culture is well documented to regain intrinsic metabolic properties and to better mimic the *in vivo* situation than two-dimensional (2D) cell culture @doi:10.1073/pnas.1918607117.


A comparative molecular analyses from 2D and 3D *in vitro* conditions revealed that cancer cell phenotype is highly influenced by its microenvironment.Through the examination of cancer cell transcriptional behavior, cellular processes were closely linked to functions promoted by different culturing conditions. 
Cancer cells grown in monolayers favored rapid proliferation, and this behavior was corroborated by up-regulation of cell cycle progression genes in addition to metabolic processes that synthesize DNA, RNA, and proteins. Unlike cancer cells cultured in monolayers, cancer cells in 3D down-regulate proliferative processes, while up-regulating genes involved in ECM organization and cell adhesion @doi:10.3390/cancers12030690. 

When performing 3D cell culture experiments, the cell environment can be manipulated to mimic that of a cell in vivo and provide more accurate data about cell-to-cell interactions, tumor characteristics, drug discovery, metabolic profiling, stem cell research, and other types of diseases @doi:10.3389/fmolb.2020.00033. 

Alterations in cancer cell behavior under different growth conditions underlie the importance of defining culturing conditions that preserve endogenous tumor behavior. While monolayer cultures promote the most non-native behavior of cancer cells, this model still maintains value due to its ease and scalability towards applications targeting cancer-growth driving pathways. However, analysis and discovery of potential therapeutics targeting stromal interactions, ECM development, or cell signaling may yield erroneous results in this system.The 3D culturing and inclusion of stromal cell types do show increased similarity to in vivo cancer behavior. However, improvements upon ex vivo culture conditions that allow all stromal components to persist will greatly enhance our ability to conduct pre-clinical screens that may more closely recapitulate the biological responses of patients @doi:10.3390/cancers12030690.


## The structure of multicellular spheroids.

MCSs are cell aggregates with complex cell-to-cell adhesions and cell-to-matrix interactions, which results in gradient generation for nutrients, gases, growth factors and signal factors @doi:10.1098/rsif.2016.0877.

It has been reported that MCS formation involves three critical steps. In the first stage, dispersed single-cells are drawn closer to form aggregations where ECM fibers act as a long-chain linker through the binding of integrins. This is followed by a period in which cell aggregates pause in compaction, because of the accumulation of sufficient amounts of E-cadherins. Finally, in the third stage, cells are compacted into solid aggregates to form MCSs due to the homophilic cadherin–cadherin binding @doi:10.1007/s00441-005-0148-2.

The formation of MCS process initiates with an spontaneous self-assembly and cell-cell interactions. These interactions are regulated by adhesions proteins such as E-cadherin,  α-catenin and P-cadherin [@doi:10.1242/bio.037051; doi.org/10.1038/s41598-018-19384-0; @doi:10.3892/ijo.31.6.1403]
Cell-to-matrix interactions is the base for cell building and is influenced by integrins mainly by β1-integrin. The integration of integrin-ECM facilitates the cell aggregation process that connect a cell with its environment in the context of spheroid formation [@doi:10.1007/s00441-005-0148-2; @doi:10.1016/S0002-9440(10)63058-1].

The cytoskeleton also plays an important role in spheroid formation. During spheroid formation the actin filaments undergo significant changes and the expanded microfilaments as stress fibres become along the cell periphery. In this step, the cytoskeleton is a force generation structure performing a continuos pre-stressed lattice that keeps structural stability [@doi:10.1021/acsbiomaterials.6b00144; @pmid:11223949]. 

The internal structure of spheroids comprises different cell layers. MCS include hypoxic, proliferative apoptotic/necrotic areas as a consequence of oxygen and nutrient gradients. Small micro-spheroids of <200μm diameter mostly include proliferating and normoxic cells, mimic three-dimensional cell-cell and cell-matrix interactions but they are inappropriate to reflect pathophysiological conditions with hypoxic areas in the spheroid center or to mimic proliferation gradients @doi:10.1039/C8AN01752B. 
However, spheroids with diameters of approximately 200-300μm results in a typical zonation, with proliferative zones at the surface co-existing with normoxic quiescent zones in the middle and hypoxic zones in the core @doi:10.1038/srep19103. Finally, MCS > 500 μm diameter the formation of necrotic areas is observed  as described in microregion of tumor *in vivo* @doi:10.1016/j.neo.2014.12.004.

Due to these characteristics, MCS mimic the first avascular stages of tumor formation, and exhibit important tumor aggressiveness features such as enhanced multicellular resistance, migration, and invasion, as well as an enhanced clonogenic capacity @doi:10.3892/or.2015.3767.

## Methods for the generation of MCS

Many 3D culture techniques are available for the generation of spheroids. These methods prevent cell attachment to the culture substratum, thereby increasing interactions with neighboring cells and extracellular matrix.

Nowadays, there are four major techniques for spheroids formation by avoiding the cells adhesion to the surfaces and favoring the cell–cell interactions and cells self-aggregation.

### The agitation-based approaches.

Agitation-based approaches to culture cells as spheroids include gyratory rotation techniques, such as gyratory shakers, rotary culture systems and stirred suspension culture systems @doi:10.1016/j.semcancer.2005.05.002.

The general principle behind these methods is that a cell suspension is placed into a container and the suspension is kept in motion, that is, either it is gently stirred or the container is rotated. The continuous motion of the suspended cells allows that cells do not adhere to the containers walls, but instead form cell-cell interactions @doi:10.1016/j.drudis.2012.10.003.

Furthermore, batches of 3D spheroids formed in spinner flasks are typically of a broad range of sizes and so would require subsequent manual selection to obtain a group of similarly sized 3D spheroids for analysis @doi:10.1002/biot.200700228. Rotatory culture system function by similar means as the spinner flask but, instead of using a stirring bar to keep cell suspensions in motion, the culture container itself is rotated, enables large-scale production and allows for long-term culture of 3D spheroids [@doi:10.1016/j.drudis.2012.10.003, @doi:10.1038/nrmicro2423]. 

### The hanging drop technique.

The hanging drop technique relies on the formation of spheroids in small drops of culture medium, which are suspended on a glass coverslip. This is a simple method in which cells are placed in hanging drop culture and incubated under physiological conditions until they form 3D spheroids. The method requires no specialized equipment and can be adapted to include addition of any biological agent in very small quantities, can also be used to co-culture two (or more) different cell populations so as to elucidate the role of cell-cell or cell-ECM interactions in specifying spatial relationships between cells @doi:10.3791/2720.
The hanging drop method generated well-rounded MCS and represents an attractive alternative for spheroids production, because it is mild, can be applied to a wide variety of cell lines, and can produce spheroids of a homogeneous size without the need for sieving or manual selection @doi:10.1002/bit.10655, for some cell lines spheroid formation occured within 72 hours @doi:10.4172/2168-9431.1000170. This method has also been applied to the co-cultivation of mixed cell populations, including the co-cultivation of endothelial cells and tumor cells as a model of early tumor angiogenesis @doi:10.1007/s10456-004-8911-7.
Although they have disadvantage as producing variable size spheroids, low throughput, hard to handle, long-term culture, they provide an efficient way to obtain biological insights that are often lost in 2D platforms @doi:10.1039/c0an00609b. 

### Liquid overlay technique.

Liquid overlay technique includes the formation of spheroids by seeding the cells on top of non-adhesive surfaces, is one of the simplest and less expensive approaches for spheroid formation forming spheroids without size or shape limitation @doi:10.1016/j.tibtech.2012.12.003. In short, wells are coated with a non-adherence layer such as agarose or poly-HEMA before adding cell suspension. Besides providing a non-adhesive surface, the agarose-coated wells or ultra-low attachment plates also increase cell-to-cell contact as cells collect on their concave bottoms @doi:10.1038/nprot.2008.226.

The rate of yield for this technique is between 60% and 100% for monoculture spheroids and 100% for co-culture spheroids. The size of the spheroids ccan be adjusted easily and precisely by varying the number of seeded cells organized in one spheroid. The formation of co-culture spheroids consisting of three different cell types is possible with this method [@doi:10.3109/14653249.2011.583233,@doi:10.1002/bit.25210].

### Microfluidics.

Microfluidics has been recently investigated for spheroids formation. Usually, microfluidics are chips composed of microchannels and microchambers, where cells suspended in media circulate and accumulate in the chambers forming the spheroids @doi:10.1016/j.snb.2018.01.223. Microfluidics, as an emerging tool to control the flow within micrometer-scale channels, is capable of manipulating the parameters dynamically and spatially, thus creating unique environments to meet the requirements for MCS formation. In addition, microfluidics can reduce the shear stress in order to minimize cell damage, and micrometer-scale chambers inside the microfluidics can be manipulated to control the size of MCS @doi10.1039/c4an00015c.

The microfluidic devices are designed to enhance the spheroid formation process by: providing size control; allowing rapid aggregation; requiring minimal interaction between the user and the device, and; replacing manual handling with engineered and automated procedures. These important capabilities have been achieved with the aid of transparent and biocompatible materials @doi:10.1016/j.snb.2018.01.223.

The emergence of “tumor-on-chip” technology provides an alternative to study multicellular and tumor microenvironment interactions in vitro. These chip devices have been extensively used to study tumor–stroma interactions, tumor-associated angiogenesis, and, recently, tumor–immune interactions @doi:10.1158/0008-5472.CAN-19-0342.

Microfluidic channels are used to promote the formation of cellular aggregates. This method opens possibilities for the continuous production of highly controlled aggregates. However, this method currently requieres a technological capacity @doi:10.1039/b618439a.

### Three-Dimensional Organoids

## MCS and PDAC
Due to that pancreatic cancer is a heterogeneous disease researchers have been developed models capable to reproduce *in vitro* the heterogeneous tumor microenvironment.

Several methods to create 3D tumors *in vitro* have been proposed, with hanging drop technique being the simplest and most frequently used. However, in many cell lines this method has failed to form the desired 3D tumor structures. 

A modified hanging drop method for 3D spheroid formation  facilitated with methylcellulose yield a straightforward production of spheroids in PDAC cells and form well-rounded spheroids after 5 days in hanging drops. These spheroidshave have high tolerance to mechanical force, thus enabling standard manipulations and display some hallmarks of solid tumors, such as hypoxic zone, proliferating cells, and apoptotic regions @doi:10.1089/ten.tec.2015.0280.

3D pancreatic cancer spheroids, based on pancreatic cancer cells and fibroblast co-culture demonstrate innate desmoplastic properties and stay poorly permeable with relevant diffusion barrier function @doi:10.1016/j.tranon.2018.10.003. Moreover,spheroids derived from pancreatic cancer cell lines cultivated with fibroblast-conditioned medium also mimic growth pattern of circulating tumor cell clusters and macrometastases @doi:10.1007/s00432-017-2434-2. Spheroid-based xenografts produced different extracellular matrix (ECM) components with uniformity in terms of ECM architecture recapitulating clinical PDA tumors. Moreover, establishment of tumors by transplantation of spheroids demonstrate higher expression of pro-fibrotic and pro-survival PDAC hallmarks @doi:10.1016/j.tranon.2018.10.003. 

In the last years the characterization of a novel 3D tumor model has been in full swing.
A triple co-culture of pancreatic cancer cells (PANC-1), fibroblasts (MRC-5) and endothelial cells (HUVEC) to form a heterotype multicellular spheroid. The integration of the three cell types enable the presence of a core rich in fibroblasts and fibronectin in which endothelial cells are homogeneously distributed @doi:10.1016/j.actbio.2018.08.008.

A microchannel model allow to develop a 3D pancreatic tumor in *vitro* by co-culturing pancreatic tumor spheroids with PSC in a collagen matrix. Under these conditions spheroids and PSCs are mutually activated when co-cultured. Under co-culture condition, tumor spheroids acquire a migratory phenotype with cancer cell-cell interactions, cell-ECM interactions, and cancer cell-PSC interactions @doi:10.1186/s13046-017-0654-6. Additionally, a humanized PDAC model in microfluidic device has been developed that incorporates the *in vivo* complexities of multicellularity, ECM components, and a rationally-defined 3D microarchitecture. This humanized PDA model monitors the interactions between primary PSCs (from patients with PDA), cancer cells (PANC-1), and ECM components (neonatal human dermal fibroblasts) within the PDA microenvironment @doi:10.1039/c3lc50487e.







## References {.page_break_before}

<!-- Explicitly insert bibliography here -->
<div id="refs"></div>

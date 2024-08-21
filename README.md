# Figure-one-Lab-Internship-Emulator
## Subject: Understanding and Application of Antibody Therapies in Cancer Treatment
## Memo: Breaking Down the KSQ for Cancer Drug Development Using scRNA-seq Data
The KSQ seeks to investigate how existing FDA-approved antibody therapies, specifically Trastuzumab (targeting HER2) and Bevacizumab (targeting VEGF), can be applied to treat a broader range of cancers beyond their currently approved indications. This exploration aims to leverage single-cell RNA sequencing (scRNA-seq) data from cancer cell lines to uncover potential therapeutic opportunities.
### What are Cancer Cell Lines?
Cancer cell lines are cultured cells that originate from a cancerous tissue (Mirabelli & Salvatore,2019). They are used extensively in research as in vitro models to study cancer biology and test drug efficacy.
### What is scRNA-seq?
Single-cell RNA sequencing (scRNA-seq) is a genomic technique used to analyze the gene expression of individual cells.  It allows researchers to study cellular responses and understand the molecular characteristics of individual cells, revealing cellular heterogeneity and identifying rare cell populations (Haque et al., 2017).
#### Why Use scRNA-seq Data in Cancer Research
scRNA-seq data helps to understand the heterogeneity of cancer cells, revealing how different cells within a tumor respond to therapies. It enables researchers to identify which cells express specific targets like HER2 or VEGF, crucial for therapies like Trastuzumab or Bevacizumab(Jovic, et al.,2022).
### What are Antibody Therapies?
Antibody therapies are treatments that use antibodies to target specific diseases. Antibodies are designed to bind to specific antigens, such as proteins on the surface of cancer cells or viruses, to neutralize them or mark them for destruction by the immune system*(Sharma et al., 2023). They work by blocking receptors, activating immune responses, or delivering cytotoxic agents directly to diseased cells.
#### Connecting scRNA-seq Data to Antibody Therapies
By analyzing scRNA-seq data, researchers can identify the expression levels of HER2 and VEGF in various cancer cell lines. If a cancer cell line shows high expression of HER2 or VEGF, it could be a candidate for treatment with Trastuzumab or Bevacizumab.
### How does Trastuzumab target HER2 (mechanism of action)?
Trastuzumab targets HER2(human epidermal growth factor receptor 2) through several collective mechanisms of action(Maadi et al., 2021):
1. It binds to the extracellular domain of the HER2 receptor, inhibiting the formation of HER2 homodimers and HER2-HER3 heterodimers, which disrupts crucial downstream signaling pathways like the PI3K/AKT pathway that promote cell survival and proliferation. 
2. Trastuzumab induces the internalization of the HER2 receptor, leading to its degradation or recycling, thereby affecting its availability for signaling. 
3. The drug also facilitates antibody-dependent cellular cytotoxicity (ADCC) by allowing the Fc region of trastuzumab to be recognized by Fcγ receptors on immune effector cells, such as natural killer (NK) cells, which then release cytotoxic molecules that induce apoptosis in HER2-positive tumor cells.
4. Trastuzumab increases the expression of ADAM17, which inhibits the production of HER-specific ligands, further reducing HER2 activation. 
### How does Bevacizumab target VEGF (mechanism of action)?
Bevacizumab  is a humanized anti-VEGF monoclonal IgG1 antibody that binds to and neutralizes circulating VEGF (Vascular endothelial growth factor A). VEGF, a potent proangiogenic growth factor  that stimulates the proliferation, migration, and survival of endothelial cells plays a critical role in the development of tumor angiogenesis(Kazazi et al,2010).
By binding to VEGF, bevacizumab inhibits the binding of VEGF to its cell surface receptors VEGFR-1 and VEGFR-2 on endothelial cells. This inhibition of VEGF signaling leads to a reduction in the microvascular growth of tumor blood vessels, thereby limiting the blood supply to the tumor tissues. The reduced blood supply also lowers the tissue interstitial pressure, increases vascular permeability, may improve delivery of chemotherapeutic agents, and favors apoptosis of tumor endothelial cells.
### References
1. Haque, A., Engel, J., Teichmann, S.A. et al. (2017)A practical guide to single-cell RNA-sequencing for biomedical research and clinical applications. Genome Med 9, 75. https://doi.org/10.1186/s13073-017-0467-4
2. Jovic, D., Liang, X., Zeng, H., Lin, L., Xu, F., & Luo, Y. (2022). Single-cell RNA sequencing technologies and applications: A brief overview. Clinical and translational medicine, 12(3), e694. https://doi.org/10.1002/ctm2.694
3. Kazazi-Hyseni, F., Beijnen, J. H., & Schellens, J. H. (2010). Bevacizumab. The oncologist, 15(8), 819–825. https://doi.org/10.1634/theoncologist.2009-0317
5. Maadi, H., Soheilifar, M. H., Choi, W. S., Moshtaghian, A., & Wang, Z. (2021). Trastuzumab Mechanism of Action; 20 Years of Research to Unravel a Dilemma. Cancers, 13(14), 3540. https://doi.org/10.3390/cancers13143540
5. Mirabelli P, Coppola L, Salvatore M. Cancer Cell Lines Are Useful Model Systems for Medical Research. Cancers (Basel). 2019 Aug 1;11(8):1098. doi: 10.3390/cancers11081098. PMID: 31374935; PMCID: PMC6721418.
6. Sharma, P., Joshi, R. V., Pritchard, R., Xu, K., & Eicher, M. A. (2023). Therapeutic Antibodies in Medicine. Molecules (Basel, Switzerland), 28(18), 6438. https://doi.org/10.3390/molecules28186438

## The Paper
The main reference for this F1L internship emulator project is the study by Kinker et al. (2020) titled Pan-cancer single cell RNA-seq uncovers recurring programs of cellular heterogeneity
### What was the Research Focus?
Kinker and colleagues explored a critical question in cancer biology: Can cancer cell lines, commonly used in research, faithfully replicate the cellular heterogeneity and plasticity that characterize human tumors? In simper terms, how well do cancer cell lines grown in the lab reflect the diversity of cancer cells found within actual tumor samples from patients? 
To investigate this, the authors employed single-cell RNA sequencing (scRNA-seq) to analyze the expression patterns associated with intra-tumoral heterogeneity (ITH). 
The researchers hypothesized that a significant fraction of the intratumoral heterogeneity reflects intrinsic cellular plasticity that may be partially preserved even in the absence of genetic diversity and the native tumor microenvironment.Their primary objective was to determine whether cancer cell lines from the Cancer Cell Line Encyclopedia (CCLE) could mimic the complex cellular heterogeneity observed in actual tumors.
### What were the key findings of the study?
The study identified 12 recurrent heterogeneity programs (RHPs) present in various cell lines, including those associated with the cell cycle, stress/interferon response, epithelial-mesenchymal transition (EMT), senescence, and protein folding/degradation. Many of these RHPs closely resembled heterogeneity patterns observed in human tumor samples, demonstrating that cancer cell lines can effectively replicate key aspects of intratumoral heterogeneity. Further analysis of two head and neck squamous cell carcinoma (HNSCC) cell lines revealed that an epithelial senescence-associated (EpiSen) program is dynamically regulated, linked to reduced proliferation, and results in differential drug sensitivity compared to more proliferative subpopulations. Additionally, the study found that genetic heterogeneity within cell lines contributed primarily to distinct subpopulations, while the continuous RHPs were likely driven by non-genetic mechanisms of cellular plasticity.
### Further Questions
#### How did the authors handle the potential caveat of co-culturing cell lines before profiling by scRNA-seq? Why do you think that caveat was or was not adequately addressed?
The authors acknowledged a potential caveat of their multiplexing approach, where the previously generated CCLE cell line pools (but not the custom HNSCC pool) were co-cultured for 3 days prior to profiling by scRNA-seq. The authors were concerned that this co-culturing could have affected the expression patterns of the cells.

To address this potential caveat, the authors performed several analyses:

1. They showed that the patterns of heterogeneity were as similar between cell lines from the same pool as between cell lines of different pools, suggesting a limited effect of co-culturing.

2. They conducted a control experiment where six cell lines were profiled with and without 3 days of co-culturing. They found that co-culturing had only a modest effect on average gene expression, while the patterns of heterogeneity were highly consistent between the two conditions.

Based on these analyses, the authors concluded that the potential effect of co-culturing was limited, particularly when focusing on the heterogeneity within each cell line, which was the primary focus of their study.
I think the authors adequately addressed this potential caveat through the control experiments and comparisons. The data they provided suggests that the co-culturing did not significantly alter the key findings

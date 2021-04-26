---
course_id: 20-109-laboratory-fundamentals-in-biological-engineering-fall-2007
layout: course_section
parent_title: Labs
title: 'Module 2.4: Journal Article Discussion'
type: course
uid: cd9396b1623dc6388b3994f34a2dccd5

---

Modules: [2.1]({{< baseurl >}}/sections/labs/sirna_design) | [2.2]({{< baseurl >}}/sections/labs/transfection) | [2.3]({{< baseurl >}}/sections/labs/luciferase_assay) | 2.4 | [2.5]({{< baseurl >}}/sections/labs/mod2_5) | [2.6]({{< baseurl >}}/sections/labs/mod2_6)

Journal Articles to be Discussed
--------------------------------

The news story:

Check, Erika. "RNA Interference: Hitting the Switch." _Nature_ 448 (2007): 855-8.

The original paper:

Li, Long-Cheng, et al. "[Small dsRNAs Induce Transcriptional Activation in Human Cells](http://www.pnas.org/cgi/content/abstract/103/46/17337)." _PNAS_ 103, no. 46 (2006): 17337-42.

Questions to Guide Your Reading
-------------------------------

Helpful information and guidelines for reading are presented here. Questions you should try to answer are called out below in bullets. The answers will not be collected but most or all will be part of the class discussion of this paper.

1\. Read the Nature news story by Erika Check first, noting particularly the reporter's description of the scientists motivation and path to RNA activation.

*   Compare this description to how the scientific authors describe their path to RNAa in the introduction to the paper they wrote. Keep track of other reactions you have to the news story. Does it raise any questions for you? Is there anything surprising?
*   Would you characterize the events as comedy or tragedy or neither?

2\. Next skim the whole scientific article by Li et al. This means read the abstract once. Read the first and last sentence of the introduction. Read the subdivision headings of the Results section. Look at all the figures and their legends. Read the first and last paragraph of the Discussion.

3\. Now it's time to really comb through the data. We'll focus on the reported results, including the [supplemental information](http://www.pnas.org/cgi/content/full/0607015103/DC1). To help you organize the material, a few links and tables are given here.

3A. Experimental Matrix
-----------------------

| TREATMENTS | PROMOTERS EXAMINED | CELL TYPES EXAMINED |
| --- | --- | --- |
|  {{< br >}}{{< br >}} dsRNA {{< br >}}{{< br >}} Aza-C (demethylase) {{< br >}}{{< br >}} IFN-alpha2a (nonspecific inducer) {{< br >}}{{< br >}}  |  {{< br >}}{{< br >}} E-cadherin {{< br >}}{{< br >}} p21 {{< br >}}{{< br >}} VEGF {{< br >}}{{< br >}}  |  {{< br >}}{{< br >}} PC3 and DU45 (human prostate cancer cell lines) {{< br >}}{{< br >}} Hela (human cervical carcinoma) MCF-7 (human breast cancer line) {{< br >}}{{< br >}} HEK293 (embryonic kidney line) {{< br >}}{{< br >}} LNCaP (human prostate cancer) {{< br >}}{{< br >}} J82 and T24 (bladder cancer) {{< br >}}{{< br >}}  

3B: Experimental Techniques
---------------------------

### Western Analysis

See the [Module 1 Day 6 lab]({{< baseurl >}}/sections/labs/mod1_6) for refresher info.

Data can be presented like this

![Sample western data.](/courses/biological-engineering/20-109-laboratory-fundamentals-in-biological-engineering-fall-2007/labs/samplewestern.jpg)

Sample western data, fig 10B. Source: Li, Long-Cheng, et al. "Small dsRNAs Induce Transcriptional Activation in Human Cells." _PNAS_ 103 no. 46 (2006): 17337-42. (© 2006 National Academy of Sciences, U.S.A. Used with permission.)

Where the treatment variation is shown above the gel lanes, the intensity of the protein band is shown inside the boxes (a cutout of the whole blot to show just the relevant bands). GAPDH is a "housekeeping gene" whose level is rarely affected by experimental perturbations.

*   Why is it important to include data for this gene product? Thinking back to when you performed your Western analysis, did you included a similar control?

### RT-PCR (also sometimes called q-PCR)

See [this link](http://openwetware.org/wiki/BE.109:Systems_engineering/Measuring_DNA,_RNA,_protein) for some description of RNA measurement techniques including RT-PCR. You might also want to learn a little about standard PCR if you're not already familiar with this technique. Most biology textbooks describe PCR or you could look at some animations of the process, for example [here](http://www.dnai.org/b/index.html), just follow the links through "techniques" and "amplifying DNA."

![Sample RT-PCR data.](/courses/biological-engineering/20-109-laboratory-fundamentals-in-biological-engineering-fall-2007/labs/sample_rtpcr.jpg)

Sample RT-PCR data, fig 12A and 12B. Source: Li, Long-Cheng, et al. "Small dsRNAs Induce Transcriptional Activation in Human Cells." _PNAS_ 103 no. 46 (2006): 17337-42. (© 2006 National Academy of Sciences, U.S.A. Used with permission.)

Data can be presented as bands on a gel (top panel in sample figure) or normalized to some baseline and shown as bargraphs (bottom panel in the sample figure). The authors describe their RT-PCR protocol in the very last paragraph of the Materials & Methods section where they call it "semiquantitative." You should read that paragraph. In short: they isolate total RNA from their samples (as you did last time), convert the RNA to cDNA (as you will do next time), and then measure the amount made by PCR amplification, running the product on a gel. They use GAPDH as a control, as they did for Westerns.

*   What if the PCR primers they used aren't all equally efficient at binding their cDNA template?

### Cell Physiology

Microscopic observation, though qualitative, can be an important "sanity check" for the molecular results like Westerns and RT-PCR. Cell numbers can be compared after different treatments, and cell appearance can be noted. For example

![Sample microscopy data.](/courses/biological-engineering/20-109-laboratory-fundamentals-in-biological-engineering-fall-2007/labs/samplecellshape.jpg)

Sample microscopy data, fig 11. Source: Li, Long-Cheng, et al. "Small dsRNAs Induce Transcriptional Activation in Human Cells." _PNAS_ 103 no. 46 (2006): 17337-42. (© 2006 National Academy of Sciences, U.S.A. Used with permission.)

The cell type is noted to the left of the images, the treatment is described above the images and the magnification and a few experimental details are described in the figure legend. This format can serve a useful model for your own lab report figures.

*   Since the images are qualitative and indirect assessments of the cells response to the perturbations, how much weight do you give the data? Are there ways to make the data more or less convincing?

### ChIP ("chromatin immunoprecipitation")

This technique is **used to quantitatively assess a protein's occupancy at a particular place on the DNA**. Proteins get chemically crosslinked to the DNA, the DNA gets sheered into small (~350 bp) fragments, and an antibody to the protein is used to precipitate (i.e. pull out of solution) the DNA that the protein is bound to. What makes this technique so powerful is the variety and specificity of antibodies that are available. For example, antibodies can recognize the difference between a methyl group on a histone protein's lysine 9 and a methyl group on the same histone protein's lysine 4. Another antibody can distinguish one methyl group on lysine 9 from two methyl groups on lysine 9. After immunoprecipitation, PCR is used (again!) to measure the amount of DNA that was precipitated. Because the number of PCR cycles is limited, a brighter band for the product means more starting DNA in the PCR tubes, which in turn means more of the protein that was recognized by the antibody. Data is usually presented as bands on a gel, as with RT-PCR, or as bar graphs that normalize the intensity to some reference sample. For example

![Sample ChIP data.](/courses/biological-engineering/20-109-laboratory-fundamentals-in-biological-engineering-fall-2007/labs/samplechip.jpg)

Sample ChIP data, fig 6. Source: Li, Long-Cheng, et al. "Small dsRNAs Induce Transcriptional Activation in Human Cells." _PNAS_ 103 no. 46 (2006): 17337-42. (© 2006 National Academy of Sciences, U.S.A. Used with permission.)

Working from the bottom of this figure up: the panels labeled "input" are the samples before antibody precipitation. The antibodies used for the precipitation are shown between the panels. The experimental treatments are shown above the panels. Finally, the regions amplified by the PCR primers (here called "Region 1" and "Region 2") are shown in the sketch above the data panels. This figure also includes DNA features and the regions targeted by dsRNA.

*   What does the "input" sample tell you?
*   If the authors made a bar graph (and BTW why didn't they?), which sample would be used to normalize intensities?
*   If the DNA is sheared into 350 bp pieces, what is the resolution of Region 1 vs Region 2?

4\. Whew! With the experimental techniques themselves under control and the overall scope of the paper approximated, it's time to think critically about what the authors found and what they did. Since there are 6 figures in the article and 6 groups in the lab you and your partner will be randomly assigned a figure and will have to lead the discussion around it. Please be ready to:

*   explain what the authors were examining
*   explain the experiment they performed and the controls they used
*   describe what each panel in the figure shows (i.e. what kind of experiment is it?)
*   narrow the data down to the most meaningful pieces
*   state what the authors conclude (you may have to go to the results text for this info)
*   consider any ambiguities...what would you like to see the authors do or say? is there another way to think about the effect they observe?

Once we've worked our way through all the figures and addressed any questions about techniques or the data, we'll look at the discussion section together to consider the persuasiveness of the data as well as the language.

For Next Time
-------------

Prepare a figure from the digital photographs you took of your cells last time. The figure and its legend should resemble the ones you saw in the paper discussed today.

Calculate the volume for 4 µg, 2 µg, 1 µg and 0.5 µg of each RNA sample that you prepared. Show your work. Save a copy of your answer since you'll need to know this volume to perform your experiment.

Please familiarize yourself with the basics of microarrays by reading [NCBI's primer on the technique](http://www.ncbi.nlm.nih.gov/genome/probe/doc/TechMicroarray.shtml).
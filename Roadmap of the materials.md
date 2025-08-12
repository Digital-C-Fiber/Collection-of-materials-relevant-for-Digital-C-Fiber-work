# Work under construction, more content is coming soon

# Research direction 1: Computational modelling of activity-dependent speed propagation changes in C-fibers
## Decoding Neuropathic Pain: Can We Predict Fluctuations of Propagation Speed in Stimulated Peripheral Nerve?
File: [Link](https://www.frontiersin.org/journals/computational-neuroscience/articles/10.3389/fncom.2022.899584/full)

License: CC-BY

Comment: The first approach to the speed propagation modelling based on machine learning. The used data is a mix of mice, rat and human microneurography recording with human-supported spike sorting. We predict ADS (activity-dependent slowings) based on the preceeding activity history. The results are promising, but there is a need for bigger harmonized data sets, work on model calibration, and a protocol to represent differently timed firing patterns.

Abstract: To understand neural encoding of neuropathic pain, evoked and resting activity of peripheral human C-fibers are studied via microneurography experiments. Before different spiking patterns can be analyzed, spike sorting is necessary to distinguish the activity of particular fibers of a recorded bundle. Due to single-electrode measurements and high noise contamination, standard methods based on spike shapes are insufficient and need to be enhanced with additional information. Such information can be derived from the activity-dependent slowing of the fiber propagation speed, which in turn can be assessed by introducing continuous “background” 0.125–0.25 Hz electrical stimulation and recording the corresponding responses from the fibers. Each fiber's speed propagation remains almost constant in the absence of spontaneous firing or additional stimulation. This way, the responses to the “background stimulation” can be sorted by fiber. In this article, we model the changes in the propagation speed resulting from the history of fiber activity with polynomial regression. This is done to assess the feasibility of using the developed models to enhance the spike shape-based sorting. In addition to human microneurography data, we use animal in-vitro recordings with a similar stimulation protocol as higher signal-to-noise ratio data example for the models.

Citation: Kutafina E, Troglio A, de Col R, Röhrig R, Rossmanith P and Namer B (2022) Decoding Neuropathic Pain: Can We Predict Fluctuations of Propagation Speed in Stimulated Peripheral Nerve? Front. Comput. Neurosci. 16:899584. doi: 10.3389/fncom.2022.899584

Code: TODO

## Convolution model of activity-dependent speed propagation
File: Coming soon

License:

Comment:

Abstract:

Citation: 

# Research direction 2: Spike Detection and Sorting in Microneurography
## Supervised Spike Sorting Feasibility of Noisy Single-Electrode Extracellular Recordings: Systematic Study of Human C-Nociceptors recorded via Microneurography
File: [Link](https://www.biorxiv.org/content/10.1101/2024.12.31.630860v1)

License: CC-BY

Comment: In this paper we present the first systematic analysis of 24 raw microneurography recordings from two labs (B. Namer, J. Dunham) and investigate the challenges of spike sorting. This is possible due to a new "ground truth protocol" used to produce time-locked spikes which serve as reliably labelled data and allow to compare and evaluate algorithms. Data show high variability, but the success potential of the sorting of the given file can be assessed and in the future serve as real-time experimental feedback for data quality.

Abstract: Using electrophysiological methods like microneurography, scientists can record nerve activity in humans to understand how peripheral nerves transmit sensations such as pain and itch. These recordings capture electrical signals, known as spikes, which represent nerve impulses. However, since several nerve fibers are often recorded simultaneously, the differentiation of the individual spikes, known as spike sorting, is critical for accurate analysis.

Existing methods for spike sorting in single electrode in-vivo recordings are often insufficient due to low signal-to-noise ratios and the absence of ground truth data needed for validation. In microneurography, low-frequency electrical stimulation (marking method) is used routinely to label part of the recorded spikes. We applied the marking method to create a ground truth data set for developing and validating a supervised approach for spike sorting.

Our transparent and lightweight algorithm showed promising results. Their high variability between the recordings, with a strong reversed link between the morphological similarities of the different fibers’ spikes and the sorting accuracy indicated a possibility to assess the “sortability” of individual recordings by applying use-case specific thresholds. This work provides a foundation for improving spike sorting in noisy peripheral nerve recordings, helping researchers study better how the nervous system processes sensations like pain and itch.

Citation: Supervised Spike Sorting Feasibility of Noisy Single-Electrode Extracellular Recordings: Systematic Study of Human C-Nociceptors recorded via Microneurography
Alina Troglio, Peter Konradi, Andrea Fiebig, Ariadna Pérez Garriga, Rainer Röhrig, James Dunham, Ekaterina Kutafina, Barbara Namer
bioRxiv 2024.12.31.630860; doi: https://doi.org/10.1101/2024.12.31.630860

Code: [SpikeSortingPipeline](https://github.com/Digital-C-Fiber/SpikeSortingPipeline)

## Advanced Spike Sorting on Microneurography Data: Proof-of-Concept of VPNet as a Universal Approach (poster)
File: [Link](https://www.researchgate.net/publication/383943886_Advanced_Spike_Sorting_on_Microneurography_Data_Proof-of-Concept_of_VPNet_as_a_Universal_Approach?_sg%5B0%5D=Bl7xvKZcxFL-jp_s2ju3SveryWH7_fP3d6XZKJGQBxvBAJ56MrkJ_L224-jFCG7h1fUlAOdjIUrUoW3u5B41-C9nNCupYprzZfewm7wU.Wr9uoIKhgvX0_Ex4vgyBkeZQjwsnldg9-Ha1th9y01KjDqaQ0Pc2WG9v3xtDk0A3Tpm1QEoj0Cj-yiAFbTL9Pg&_tp=eyJjb250ZXh0Ijp7ImZpcnN0UGFnZSI6InB1YmxpY2F0aW9uIiwicGFnZSI6InByb2ZpbGUiLCJwb3NpdGlvbiI6InBhZ2VDb250ZW50In19)

Comment: A conference poster to present the first results of VPNet approach to spike sorting in Microneurography (GMDS 2024). In comparison to the SVM-based classification, the results were not much higher, but the VPNet approch was possible to use without calibratons on data set level. 

## TODO: Troglio et al. 2025
File: Coming soon

License:

Comment:

Abstract:

Citation: 

## TODO: Darabos et al. 2025
File: Coming soon

License:

Comment:

Abstract:

Citation: 

Code:

# Research direction 3: FAIR Microneurography and Open Science

##  Analysis of the Research Infrastructure Needs in Emerging Interdisciplinary Consortia (2025)
File: [Link](https://zenodo.org/records/16736006)

License: Creative Commons Attribution 4.0 International

Comment: NFDI4Health pilot project

##  Harmonizing neuropathic pain research: outcomes of the London consensus meeting on peripheral tissue studies (2025)
File: [Link](https://doi.org/10.1097/j.pain.0000000000003445)

License:  CC-BY

Comment:

Abstract: Neuropathic pain remains difficult to treat, with drug development hampered by an incomplete understanding of the pathogenesis of the condition, as well as a lack of biomarkers. The problem is compounded by the scarcity of relevant human peripheral tissues, including skin, nerves, and dorsal root ganglia. Efforts to obtain such samples are accelerating, increasing the need for standardisation across laboratories. In this white paper, we report on a consensus meeting attended by neuropathic pain experts, designed to accelerate protocol alignment and harmonization of studies involving relevant peripheral tissues. The meeting was held in London in March 2024 and attended by 28 networking partners, including industry and patient representatives. We achieved consensus on minimal recommended phenotyping, harmonised wet laboratory protocols, statistical design, reporting, and data sharing. Here, we also share a variety of relevant standard operating procedures as supplementary protocols. We envision that our recommendations will help unify human tissue research in the field and accelerate our understanding of how abnormal interactions between sensory neurons and their local peripheral environment contribute towards neuropathic pain.

Citation: Villa S, Aasvang EK, Attal N, Baron R, Bourinet E, Calvo M, Finnerup NB, Galosi E, Hockley JRF, Karlsson P, Kemp H, Körner J, Kutafina E, Lampert A, Mürk M, Nochi Z, Price TJ, Rice ASC, Sommer C, Taba P, Themistocleous AC, Treede RD, Truini A, Üçeyler N, Bennett DL, Schmid AB, Denk F. Harmonizing neuropathic pain research: outcomes of the London consensus meeting on peripheral tissue studies. Pain. 2025 May 1;166(5):994-1001. doi: 10.1097/j.pain.0000000000003445. Epub 2024 Oct 16. 


## Semi-Automatic Export of Electrophysiological Metadata to NFDI4Health Local Data Hubs: Use Case of Microneurography odML-Tables - A Technical Case Report (2024)
File: [Link](http://dx.doi.org/10.3233/SHTI240836)

License: CC BY-NC 4.0

Comment:

Abstract: The Local Data Hub (LDH) is a platform for FAIR sharingof medical research (meta-)data. In order to promote the usage of LDH in differentresearch communities, it is important to understand the domain-specific needs,solutions currently used for data organization and provide support for seamlessuploads to a LDH. In this work, we analyze the use case of microneurography, whichis an electrophysiological technique for analyzing neural activity. Methods Afterperforming a requirements analysis in dialogue with microneurography researchers,we propose a concept-mapping and a workflow, for the researchers to transform andupload their metadata. Further, we implemented a semi-automatic upload extensionto odMLtables, a template-based tool for handling metadata in theelectrophysiological community. Results The open-source implementation enablesthe odML-to-LDH concept mapping, allows data anonymization from within thetool and the creation of custom-made summaries on the underlying data sets.Discussion This concludes a first step towards integrating improved FAIR processesinto the research laboratory’s daily workflow. In future work, we will extend thisapproach to other use cases to disseminate the usage of LDHs in a larger researchcommunity. 

Citation: Elwes MR, Troglio A, Abedi M, Golebiewski M, Meineke F, Kirsten T, et al. Semi-Automatic Export of Electrophysiological Metadata to NFDI4Health Local Data Hubs: Use Case of Microneurography odML-Tables – A Technical Case Report. In: German Medical Data Sciences 2024 [Internet]. IOS Press; 2024 [cited 2024 Sep 10]. p. 40–8. 

## openMNGlab



Code: https://github.com/Digital-C-Fiber/openMNGlab 

## odML-Tables as a Metadata Standard in Microneurography (2023)
File: [Link](http://dx.doi.org/10.3233/SHTI230687)

License: CC BY-NC 4.0

Comment:

Abstract: Metadata is essential for handling medical data according to FAIR principles. Standards are well-established for many types of electrophysiological methods but are still lacking for microneurographic recordings of peripheral sensory nerve fibers in humans. Developing a new concept to enhance laboratory workflows is a complex process. We propose a standard for structuring and storing microneurography metadata based on odML and odML-tables. Further, we present an extension to the odML-tables GUI that enables user-friendly search functionality of the database. With our open-source repository, we encourage other microneurography labs to incorporate odML-based metadata into their experimental routines.

Citation: Troglio A, Nickerson A, Schlebusch F, Röhrig R, Dunham J, Namer B, et al. odML-Tables as713a Metadata Standard in Microneurography. Stud Health Technol Inform. 2023 Sep 12; 307:7143–11. 

Code: [Link](https://github.com/Digital-C-Fiber/odMLtablesForMNG)

## PyDapsys: an open-source library for accessing electrophysiology data recorded with DAPSYS (2023)
File: [Link](https://www.frontiersin.org/journals/neuroinformatics/articles/10.3389/fninf.2023.1250260/full)

License: 

Comment: CC-BY

Abstract: In the field of neuroscience, a considerable number of commercial data acquisition and processing solutions rely on proprietary formats for data storage. This often leads to data being locked up in formats that are only accessible by using the original software, which may lead to interoperability problems. In fact, even the loss of data access is possible if the software becomes unsupported, changed, or otherwise unavailable. To ensure FAIR data management, strategies should be established to enable long-term, independent, and unified access to data in proprietary formats. In this work, we demonstrate PyDapsys, a solution to gain open access to data that was acquired using the proprietary recording system DAPSYS. PyDapsys enables us to open the recorded files directly in Python and saves them as NIX files, commonly used for open research in the electrophysiology domain. Thus, PyDapsys secures efficient and open access to existing and prospective data. The manuscript demonstrates the complete process of reverse engineering a proprietary electrophysiological format on the example of microneurography data collected for studies on pain and itch signaling in peripheral neural fibers.

Citation: Konradi P, Troglio A, Pérez Garriga A, Pérez Martín A, Röhrig R, Namer B and Kutafina E (2023) PyDapsys: an open-source library for accessing electrophysiology data recorded with DAPSYS. Front. Neuroinform. 17:1250260. doi: 10.3389/fninf.2023.1250260

Code: [Link](https://github.com/Digital-C-Fiber/PyDapsys) 

## Measuring pain and nociception: Through the glasses of a computational scientist. Transdisciplinary overview of methods (2023)
File: [Link](https://www.frontiersin.org/journals/network-physiology/articles/10.3389/fnetp.2023.1099282/full)

License: CC_BY 

Comment:

Abstract: In a healthy state, pain plays an important role in natural biofeedback loops and helps to detect and prevent potentially harmful stimuli and situations. However, pain can become chronic and as such a pathological condition, losing its informative and adaptive function. Efficient pain treatment remains a largely unmet clinical need. One promising route to improve the characterization of pain, and with that the potential for more effective pain therapies, is the integration of different data modalities through cutting edge computational methods. Using these methods, multiscale, complex, and network models of pain signaling can be created and utilized for the benefit of patients. Such models require collaborative work of experts from different research domains such as medicine, biology, physiology, psychology as well as mathematics and data science. Efficient work of collaborative teams requires developing of a common language and common level of understanding as a prerequisite. One of ways to meet this need is to provide easy to comprehend overviews of certain topics within the pain research domain. Here, we propose such an overview on the topic of pain assessment in humans for computational researchers. Quantifications related to pain are necessary for building computational models. However, as defined by the International Association of the Study of Pain (IASP), pain is a sensory and emotional experience and thus, it cannot be measured and quantified objectively. This results in a need for clear distinctions between nociception, pain and correlates of pain. Therefore, here we review methods to assess pain as a percept and nociception as a biological basis for this percept in humans, with the goal of creating a roadmap of modelling options.

Citation: Kutafina E, Becker S and Namer B (2023) Measuring pain and nociception: Through the glasses of a computational scientist. Transdisciplinary overview of methods. Front. Netw. Physiol. 3:1099282. doi: 10.3389/fnetp.2023.1099282






# Simulational modelling of C-fibers based on Hodgkin-Huxley approach

## 
##  Modeling activity-dependent changes of axonal spike conduction in primary afferent C-nociceptors (2014)
File: [Link](https://pubmed.ncbi.nlm.nih.gov/24371290/)

License:

Comment: 

Abstract: Action potential initiation and conduction along peripheral axons is a dynamic process that displays pronounced activity dependence. In patients with neuropathic pain, differences in the modulation of axonal conduction velocity by activity suggest that this property may provide insight into some of the pathomechanisms. To date, direct recordings of axonal membrane potential have been hampered by the small diameter of the fibers. We have therefore adopted an alternative approach to examine the basis of activity-dependent changes in axonal conduction by constructing a comprehensive mathematical model of human cutaneous C-fibers. Our model reproduced axonal spike propagation at a velocity of 0.69 m/s commensurate with recordings from human C-nociceptors. Activity-dependent slowing (ADS) of axonal propagation velocity was adequately simulated by the model. Interestingly, the property most readily associated with ADS was an increase in the concentration of intra-axonal sodium. This affected the driving potential of sodium currents, thereby producing latency changes comparable to those observed for experimental ADS. The model also adequately reproduced post-action potential excitability changes (i.e., recovery cycles) observed in vivo. We performed a series of control experiments replicating blockade of particular ion channels as well as changing temperature and extracellular ion concentrations. In the absence of direct experimental approaches, the model allows specific hypotheses to be formulated regarding the mechanisms underlying activity-dependent changes in C-fiber conduction. Because ADS might functionally act as a negative feedback to limit trains of nociceptor activity, we envisage that identifying its mechanisms may also direct efforts aimed at alleviating neuronal hyperexcitability in pain patients.

Citation: Tigerholm J, Petersson ME, Obreja O, Lampert A, Carr R, Schmelz M, Fransén E. Modeling activity-dependent changes of axonal spike conduction in primary afferent C-nociceptors. J Neurophysiol. 2014 May;111(9):1721-35. doi: 10.1152/jn.00777.2012. Epub 2013 Dec 26. 






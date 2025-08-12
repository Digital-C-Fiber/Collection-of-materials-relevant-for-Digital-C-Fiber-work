# Research direction 1: Computational modelling of activity-dependent speed propagation changes in C-fibers
## Decoding Neuropathic Pain: Can We Predict Fluctuations of Propagation Speed in Stimulated Peripheral Nerve?
File: [Link](https://www.frontiersin.org/journals/computational-neuroscience/articles/10.3389/fncom.2022.899584/full)

License: CC-BY

Comment: The first approach to the speed propagation modelling based on machine learning. The used data is a mix of mice, rat and human microneurography recording with human-supported spike sorting. We predict ADS (activity-dependent slowings) based on the preceeding activity history. The results are promising, but there is a need for bigger harmonized data sets, work on model calibration, and a protocol to represent differently timed firing patterns.

Abstract: To understand neural encoding of neuropathic pain, evoked and resting activity of peripheral human C-fibers are studied via microneurography experiments. Before different spiking patterns can be analyzed, spike sorting is necessary to distinguish the activity of particular fibers of a recorded bundle. Due to single-electrode measurements and high noise contamination, standard methods based on spike shapes are insufficient and need to be enhanced with additional information. Such information can be derived from the activity-dependent slowing of the fiber propagation speed, which in turn can be assessed by introducing continuous “background” 0.125–0.25 Hz electrical stimulation and recording the corresponding responses from the fibers. Each fiber's speed propagation remains almost constant in the absence of spontaneous firing or additional stimulation. This way, the responses to the “background stimulation” can be sorted by fiber. In this article, we model the changes in the propagation speed resulting from the history of fiber activity with polynomial regression. This is done to assess the feasibility of using the developed models to enhance the spike shape-based sorting. In addition to human microneurography data, we use animal in-vitro recordings with a similar stimulation protocol as higher signal-to-noise ratio data example for the models.

Citation: Kutafina E, Troglio A, de Col R, Röhrig R, Rossmanith P and Namer B (2022) Decoding Neuropathic Pain: Can We Predict Fluctuations of Propagation Speed in Stimulated Peripheral Nerve? Front. Comput. Neurosci. 16:899584. doi: 10.3389/fncom.2022.899584

Code: TODO

## Supervised Spike Sorting Feasibility of Noisy Single-Electrode Extracellular Recordings: Systematic Study of Human C-Nociceptors recorded via Microneurography
File: [Link](https://www.biorxiv.org/content/10.1101/2024.12.31.630860v1)

License: CC-BY

Comment:

Abstract: Using electrophysiological methods like microneurography, scientists can record nerve activity in humans to understand how peripheral nerves transmit sensations such as pain and itch. These recordings capture electrical signals, known as spikes, which represent nerve impulses. However, since several nerve fibers are often recorded simultaneously, the differentiation of the individual spikes, known as spike sorting, is critical for accurate analysis.

Existing methods for spike sorting in single electrode in-vivo recordings are often insufficient due to low signal-to-noise ratios and the absence of ground truth data needed for validation. In microneurography, low-frequency electrical stimulation (marking method) is used routinely to label part of the recorded spikes. We applied the marking method to create a ground truth data set for developing and validating a supervised approach for spike sorting.

Our transparent and lightweight algorithm showed promising results. Their high variability between the recordings, with a strong reversed link between the morphological similarities of the different fibers’ spikes and the sorting accuracy indicated a possibility to assess the “sortability” of individual recordings by applying use-case specific thresholds. This work provides a foundation for improving spike sorting in noisy peripheral nerve recordings, helping researchers study better how the nervous system processes sensations like pain and itch.

Citation: Supervised Spike Sorting Feasibility of Noisy Single-Electrode Extracellular Recordings: Systematic Study of Human C-Nociceptors recorded via Microneurography
Alina Troglio, Peter Konradi, Andrea Fiebig, Ariadna Pérez Garriga, Rainer Röhrig, James Dunham, Ekaterina Kutafina, Barbara Namer
bioRxiv 2024.12.31.630860; doi: https://doi.org/10.1101/2024.12.31.630860

Code: [SpikeSortingPipeline](https://github.com/Digital-C-Fiber/SpikeSortingPipeline)

## Convolution model of activity-dependent speed propagation
File: Coming soon

License:

Comment:

Abstract:

Citation: 

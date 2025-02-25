# Google Cloud Platform for Genomics Pipelines

Genomics on GCP includes using data, service and patterns.  This page summarizes these topics.

<img src="https://github.com/lynnlangit/TeamTeri/blob/master/Images/GCP-Genomics.png" width=600>

❗**IMPORTANT:** - For more detail on implementation, see my open source course `gcp-for-bioinformatics` at https://github.com/lynnlangit/gcp-for-bioinformatics

---

## Genomic Datasets on GCP 

* **SEARCH** for public datasets via Google Dataset search, see this [link](https://toolbox.google.com/datasetsearch)
* **LIST** public genomics datasets, many hosted on GCP, see this [link](http://googlegenomics.readthedocs.io/en/latest/use_cases/discover_public_data/index.html)
* **LIST** of public genomic datasets on GCP, see this [link](https://cloud.google.com/life-sciences/docs/resources/public-datasets)

* * *

## Genomic Analysis Patterns on GCP

* **SEE** the GCP Google Cloud Life Sciences API, see this [link](https://cloud.google.com/genomics/overview). General pattern shown above.  GCP Web UI for Google Life Sciences (job run output example) shown in screenshot below.
* **USE** the GCP Life Sciences API Quick Start steps to get started, see this [link](https://cloud.google.com/genomics/quickstart)
* **LEARN** more - I have created an open source course `gcp-for-bioinformatics`, see this [link](https://github.com/lynnlangit/gcp-for-bioinformatics)
* **UNDERSTAND** architecture patterns - see my [reference architecture diagrams for genomic analysis](https://github.com/lynnlangit/gcp-for-bioinformatics/blob/master/6_ARCHITECTURE.md)
* **READ** GCP Genomics Reference [architecture](https://cloud.google.com/solutions/genomic-data-processing-reference-architecture) article
* **End-to-end pipeline** patterns and documentation, see the Google Genomics Cookbook, see this [link](http://googlegenomics.readthedocs.io/en/latest/)

<img src="https://github.com/lynnlangit/TeamTeri/blob/master/Images/GCP-Genomics-Jobs.png" width=600>

---

## Google Genomics Deep Variant Tool

DeepVariant is an open source deep learning library which reconstructs the true genome sequence from HTS sequencer data with significantly greater accuracy than previous classical methods. DeepVariant transforms the task of variant calling, as this reconstruction problem is known in genomics, into an image classification problem using TensorFlow.

DeepVariant is a deep learning-based variant caller that takes aligned reads (in BAM or CRAM format), produces pileup image tensors from them, classifies each tensor using a convolutional neural network, and finally reports the results in a standard VCF or gVCF file. DeepVariant supports germline variant-calling in diploid organisms.

- Source Code for [`Deep Variant` on GCP](https://github.com/google/deepvariant) 
- Google [`Deep Variant `Tutorial](https://cloud.google.com/genomics/docs/tutorials/deepvariant)  
- Google blog post - [`Looking through Deep Variant eyes`](https://google.github.io/deepvariant/posts/2020-02-20-looking-through-deepvariants-eyes/) 

<img src="https://github.com/lynnlangit/TeamTeri/blob/master/Images/deep-variant.png" width=800>
***



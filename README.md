# Source separation proof-of-concept

![Full diagram](https://user-images.githubusercontent.com/97224401/228294426-ebb03fab-94b2-42f1-8915-e393701e29fd.png)


> A proof-of-concept pipeline for modelling interaction in the jazz rhythm section using source-seperated commercial audio recordings
## Introduction
This repository introduces a proof-of-concept pipeline for modelling interaction and rhythmic adaptation in commercial jazz recordings using a process of source separation, automatic onset detection, and linear phase correction modelling.  Whereas previously researchers have been restricted to multi-tracked recordings they have made themselves in experiments, this pipeline is designed to enable the modelling of ensemble interaction in commercial audio recordings.  

This proof-of-concept uses a 30-second audio excerpt from "Peri's Scope" by the Bill Evans trio, recorded on the 1959 album *Portrait in Jazz*. The excerpt can be downloaded [freely from the Internet Archive](https://archive.org/download/cd_portrait-in-jazz_bill-evans-trio/disc1/06.%20Bill%20Evans%20Trio%20-%20Peri%27s%20Scope_sample.mp3). If you wish to use your own audio file, you'll need to replace the `INPUT_AUDIO` variable in the notebook to point towards your file path or address. While many of the settings and parameters in the pipeline should, in theory, transfer to similar piano trio recordings, **there is no guarantee *(yet)* that it will produce anything remotely reasonable with any other audio file**.

You can listen to the isolated, source-separated double bass performance below, with each 'click' corresponding to a detected onset in the perofrmance:

https://user-images.githubusercontent.com/97224401/227532070-b946390f-8073-4ec5-ac60-8d4877600db5.mp4


## Usage
<a target="_blank" href="https://colab.research.google.com/github/HuwCheston/source-seperation-test/blob/main/source_seperation_test.ipynb"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a>

### ^^^ *Hit the "Open in Colab" button to run the script online!* ^^^
Just click the *Open in Colab* button above to open a new Colaboratory window in a browser. You'll then need to click Runtime -> Run all to run all the code cells. Alternatively, you can clone the repository and run the `source_seperation_test.ipynb` file in any notebook editor, e.g. DataSpell, Jupyter.

## License
Distributed under the MIT License. See `LICENSE.txt` for more information.

## Contact
Huw Cheston - [@huwcheston](https://twitter.com/huwcheston) - hwc31@cam.ac.uk

Project Link: [https://github.com/HuwCheston/source-seperation-test](https://github.com/HuwCheston/source-seperation-test)

# CueExperimentPsychology

This repository performs analysis on the results obtained from the experiment titled "The Interplay of Attention and Recall: A Cue-Based Analysis". 

## Experiment Description

### Experiment Groups
The experiment consisted of two main groups, the experimental and the control group. The control group were given no cues, and the exact same paragraph as the experimental group was provided. 

In the experimental group, participants were provided with two types of cues: Highlighted Cues and Semantic Cues. For the highlighted cues, the experimental group were provided a few phrases in bold. For the semantic cues, a topic sentence was also given to the experimental group which related to some phrases of the paragraph. 

The semantic cue phrases were written so that they were present as naturally as possible without actually being semantically related to the core idea of the paragraph provided by the topic cue. 

### Core Idea of the experiment and Data Collection

The idea was to test which cue grabs more attention and thus leads to better recall in participants. 24 hours after presenting the cues, participants were called in again to write down what they remember. The Sentences folder contains the anonymized responses of participants along with the original sentences presented to the participants.

### Results

It was found that participants in the control group recalled both highlighted and semantic cue phrases with similar mean semantic similarity distance. The experimental group also recalled the highlighted cue associated phrases with the same mean semantic similarity distace. However, there was a drop in the distance for the semantic cue associated phrases. 

This suggests that participants tended to focus their attention on the highlighted cues, and this overpowered any semantic cue that was present to the point where they ignored non-highlighted sentences. Although the difference was not significant, this was expected given the small sample size. Therefore, further exploration needs to be performed to truly grasp the significance of this phenomenon.

## Installation

You can copy the code and data by cloning this repository.

```Bash
cd path/to/repo/directory
git clone https://github.com/prajasnaik/CueExperimentPsychology
```

To run the analysis, refer to the analysis notebook present in the repository. The system needs to have python installed.

To get started, initialize and run a virtual environment with the following command: - 
``` Bash
python -m venv path/to/virtual/environment
source path/to/virtual/environment/bin/activate
```

Next, install the requirements using the following command: - 

``` Bash
pip -r requirements.txt
```
Once this is setup, connect the virtual environment to the analysis notebook and you are good to go!
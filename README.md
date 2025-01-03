# ICON-2024-Faux-Hate-NOVA_RMK_ADS
# Overview
The Faux-Hate shared task is designed to challenge participants to tackle both fake and hate detection in social media comments, with additional emphasis on identifying the target and severity of hateful speech.
# Key Concepts
Fake: Misinformation deliberately spread with the intention to mislead.
Hate: Speech intended to marginalize individuals or groups based on attributes like religion, ethnicity, or political beliefs.
Target: The intended subject of the hate speech, classified as either an individual, organization, or religion.
Severity: The intensity of the hate speech, ranging from low (disagreement) to high (advocating violence).
# Tasks
Task A - Binary Faux-Hate Detection
In Task A, the objective is to identify whether a social media comment contains both fake information and hate speech. This involves:

Fake Label: Whether the content is fake (1) or real (0).
Hate Label: Whether the content contains hate speech (1) or not (0).
Participants are expected to develop a model capable of predicting both labels from the text samples.

Task B - Target and Severity Prediction
In Task B, the objective is to classify the target and severity of hate speech in the text. The labels to predict are:

Target: The intended target of the hate speech, which could be:

Individual (I)
Organization (O)
Religion (R)
Severity: The severity of the hate speech, which could be:

Low (L)
Medium (M)
High (H)
The task requires a model that predicts both the target and the severity labels for each given text sample.
# Approach
We solved the problem by using the machine learning algorithms for the task A we use Logestic regression and for the task B we used Random Forest
# Requirements

To run the code in this repository, you need the following Python libraries:

- numpy
- pandas
- torch
- transformers
- sklearn
- matplotlib
- seaborn

You can install all required dependencies by running:

bash
pip install -r requirements.txt


# Citation

bibtex
@article{biradar2024faux,
  title={Faux Hate: Unravelling the Web of Fake Narratives in Spreading Hateful Stories: 
         A Multi-Label and Multi-Class Dataset in Cross-Lingual Hindi-English Code-Mixed Text},
  author={Biradar, Shankar and Saumya, Sunil and Chauhan, Arun},
  journal={Language Resources and Evaluation},
  pages={1--32},
  year={2024},
  publisher={Springer}
}

# Acknowledgements
- The ICON 2024 organizers for hosting this shared task.
- Hugging Face for providing powerful transformer-based models.
- The open-source community for providing tools and libraries that facilitated our work.


### FINAL PROJECT
`Authors: Dipto Biswas (1075562), Ivan Odiel Magtangob (1092635)`
`Last Updated: December 8th, 2023`

#### FILES:
- Notebook (.ipynb) files for each evaluated model
    - Naive Bayes
    - K-Nearest Neighbours
    - Decision Tree
    - Logistic Regression
    - Stochastic Gradient Descent
    - Support Vector Machine
- audio_embeddings.pt (torch file storing processed audio embeddings)
- README.md

#### RUNNING
Each model is self-contained in its own Jupyter Notebook file, where dependencies are automatically checked and downloaded.

The Naive Bayes classifier (`naivebayes.ipynb`) was created first and is responsible for processing the audio dataset
into embeddings. These embeddings are then saved locally for other classifiers to access. Thus, **run Naive Bayes first**
**before any other classifier**.

Execute each Notebook file by pressing 'Run All' in each Notebook's upper toolbar.

#### DATASET
The dataset used for this project from is from [Huggingface](https://huggingface.co/datasets/TrainingDataPro/speech-emotion-recognition-dataset) by TrainingDataPro, which contains 80 .wav files  (<10s) of conversation of 4 classes: ['euphoric', 'joyfully', 'sad', 'surprised'].

#### RESULTS SUMMARY
After evaluation, the following mean testing accuracies were obtained:
- Naive Bayes: 30.00%
- K-Nearest Neighbours: 22.50%
- Decision Tree: 20.00%
- Logistic Regression: 28.75%
- Stochastic Gradient Descent: 28.75%
- Support Vector Machine: 27.50%

<a href="https://www.kaggle.com/datasets/uwrfkaggler/ravdess-emotional-speech-audio">Kaggle Dataset</a>

<h2>Speech Emotion Recognition (SER)</h2>
<p>This project uses machine learning techniques to focus on Speech Emotion Recognition (SER). The aim is to classify emotions from speech audio signals using feature extraction and neural network models.</p>

<h2>Overview</h2>
<p>Speech Emotion Recognition (SER) is the task of identifying the emotional state of a speaker based on audio data. It is widely applied in fields like human-computer interaction, healthcare, and entertainment.</p>


<h2>Dataset</h2>
<p>This project uses the RAVDESS dataset for training and evaluating models. Features such as Mel-frequency Cepstral Coefficients (MFCCs) are extracted, and a Multi-Layer Perceptron (MLP) Classifier is used for emotion classification.</p>

<h2>Features</h2>
<ul>
  <li>Audio Feature Extraction: Using Librosa for MFCCs and other frequency-based features.</li>
  <li>Machine Learning Model: Implemented with Scikit-learn's MLPClassifier.</li>
  <li>Dataset: Leveraging the RAVDESS dataset for high-quality labeled emotional speech data.</li>
  <li>Evaluation: Assessing model performance with accuracy and other metrics.</li>
</ul>

<h2>Requirements</h2>
<p>Install the required Python libraries:</p>
<code>pip install -r requirements.txt</code>
<!-- Key Libraries
librosa
numpy
scikit-learn
matplotlib
soundfile
Usage -->
<h4>Clone the Repository:</h4>
<code>git clone https://github.com/HiteshReddy28/Speech_Emotion_Recognition.git</code>

<h4>Run the Notebook:</h4>
<p>Open the Jupyter Notebook (SER.ipynb) in your preferred environment (e.g., Jupyter Lab, Google Colab).</p>

<h4>Train the Model:</h4>
<ul>
  <li>Load and preprocess the RAVDESS dataset.</li>
  <li>Extract features from the audio files.</li>
  <li>Train the MLP model on the extracted features.</li>
  </ul>

<h2>Applications</h2>
<ul>
<li>Human-Computer Interaction: Making systems responsive to user emotions.</li>
<li>Healthcare: Detecting emotional distress in patients.</li>
<li>Customer Support: Monitoring and analyzing customer satisfaction.</li>
<li>Entertainment: Personalizing content or creating adaptive gaming environments.</li>
</ul>

<h2>Future Improvements</h2>
<ul>
  <li>Implement deep learning models like CNNs or RNNs for better performance.</li>
  <li>Use pretrained audio models (e.g., Wav2Vec or HuBERT).</li>
  <li>Experiment with hyperparameter tuning for the current model.</li>
  <li>Deploy the model using FastAPI or Flask.</li>
</ul>

<h2>Results</h2>


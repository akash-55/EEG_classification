<h2>Classification of Alcoholic and Control Subjects using Spiking Neural Network</h2>

<p>This project focuses on leveraging Spiking Neural Networks (SNNs) within the NeuCube computational framework to classify subjects with alcohol use disorders and control subjects based on EEG data.</p>

<h2>Key Aspects:</h2>

<h3>1. Dataset</h3>
<p>The EEG dataset consists of recordings from 122 control and alcoholic subjects, each undergoing 120 trials. Data were collected from 64 scalp-mounted electrodes.</p>

<h3>2. Preprocessing</h3>
<p>Using Python and bash scripts, the dataset was converted into NeuCube format and separated into two classes (Alcoholic and Control), with 100 samples from each class used for the experiment.</p>

<h3>3. NeuCube Framework</h3>
<p>NeuCube utilizes a spiking neural network (SNN) architecture designed to mimic the structural and functional aspects of specific brain regions. The SNN learns from spatio-temporal brain data (STBD), establishing connections between neuron clusters exhibiting sequences of neural activity.</p>

<h3>4. Visualization</h3>
<p>NeuCube's network analysis revealed notable differences in interconnectivity between control and alcoholic subjects. Visualizations demonstrated higher interconnectivity in the control group's brain activity.</p>

<h3>5. Feature Extraction</h3>
<p>Network analysis was used to identify and remove non-informative EEG channels, enhancing classification accuracy.</p>

<h3>6. Results</h3>
<p>Without feature extraction, the accuracy varied minimally between single and multiple training sessions. With feature extraction, accuracy significantly improved, achieving 80.20% after training the cube once and 75.25% after training it three times.</p>

<p>This project demonstrates the effectiveness of SNNs in handling complex neuroinformatic data, surpassing traditional machine learning methods in classifying alcohol use disorders. The use of NeuCube's feature extraction capabilities further enhanced the model's performance, showcasing the potential of advanced machine learning techniques in neuroinformatics.</p>

</body>
</html>

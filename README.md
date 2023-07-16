# hugging-face-transformers
<p>Hugging Face Transformers package is very popular and versatile Python library that provides pre-trained models for a variety of applications in NLP, as well other areas such as image analysis, audio analysis, multimodal analysis (optical character recognition, video classification, visual question answering and many more).</p>
<center> <img src="https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-GPXX0AIAEN/Transformers_models.png" width="60%" alt="iris image"> <center>
<h3>Applications of Hugging Face Transformers</h3>
<h3>Objectives</h3>
<ul> 
<li>Sentiment Analysis</li>
<li>Topic Classification</li>
<li>Text Generation</li>
<li>Name Entity Recognition</li>
<li>Question Answering</li>
<li>Text Summarization</li>
<li>Text Translation</li>
</ul>
<h2>What is a Transformer Model?</h2>
<p>
A Transformer Model is a neural network that learns context and thus meaning by tracking relationships in sequential data, for example, words in a sentence. Transformer models apply an evolving set of mathematical techniques, called attention or self-attention, differently weighing the significance of each part of the input data. They are used primarily in the fields of natural language processing and computer vision. Similarly to recurrent neural networks (RNNs), transformers are designed to process sequential data, for example a body of text, with applications such as translation and text summarization. However, unlike RNNs, transformers process the entire input all at once. The attention mechanism provides context for any position in the input sequence. For example, if the input data is a natural language sentence, the transformer does not have to process one word at a time. This allows for more parallelization than RNNs, and therefore, reduces training times. The additional training parallelization allows training on larger datasets. This led to the development of pre-trained systems such as BERT (Bidirectional Encoder Representations from Transformers) and GPT (Generative Pre-trained Transformer), which were trained with large language datasets, such as the Wikipedia Corpus and Common Crawl, and can be fine-tuned for specific tasks.</p>
<h2>What do Transformer Models do?</h2>
<p>
Transformer Models have many useful applications in today world. They are widely used in near real-time translation tasks, opening communication spaces to language-diverse and hearing-impaired audiences. These models are advancing medical research by helping scientists to understand the DNA and amino acid sequences to speed up the development and improve the quality of treatments for different diseases. The models can detect anomalies to prevent fraud detection, streamline manufacturing, make recommendations and overall improve our day-to-day quality of life.</h3>
<h2>Transformer Model Architecture</p>
<img src="https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBM-GPXX0AIAEN/The-Transformer-model-architecture.png" width="50%" alt="iris image"> 
<p>The diagram above describes the pipeline between the input, output and positional encoding. For more information on Transformer Architecture visit this <a href = "https://en.wikipedia.org/wiki/Transformer_\(machine_learning_model\" alt="">wikipedia</a> page.</p>
<h2>How to use Hugging Face Transformers</h2>
<p>There is very easy way to apply Hugging Face Transformers, it is to use the pipeline() function. The pipeline makes it simple to use any model from the Hugging Face Hub for inference on any language, computer vision, speech, or multimodal tasks. Each task has an associated pipeline. However, it is simpler to use the general pipeline abstraction, which contains all the task-specific pipelines. The pipeline() automatically loads a default model and a pre-processing class capable of inference for any of your desired tasks. Hugging Face community contains more information about the models and data they were trained on. This <a href = "https://huggingface.co/models?utm_medium=Exinfluencer&utm_source=Exinfluencer&utm_content=000026UJ&utm_term=10006555&utm_id=NA-SkillsNetwork-Channel-SkillsNetworkGuidedProjectsIBMGPXX0AIAEN102-2022-01-01" alt = "">Hugging Face Page</a> contains ALL the models created by this community.</p>

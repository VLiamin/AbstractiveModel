# AbstractiveModel
The objective of this project is to build a seq2seq model that can create relevant summaries for russian news. The architecture of this model is based on the architecture of Xin Pan and Peter Liu(https://modelzoo.co/model/textsum). The TensorFlow library was used to help build the model.  The encoder consists of two-layered Bidirectional RNN and decoder consists of two-layered Uni-directional RNN. Bahdanau Attention mechanism is used in the decoder layer. Using it helps the model to train faster and can produce better results.

# Technology

Yandex DataSphere was chosen as the cloud on which the calculations will take place. Since it surpasses Google Colab in the required parameters. This is an unlimited lifetime of the virtual machine and memory.

TensorFlow was chosen as the library for automatic summarization. It was chosen because it is one of the best libraries for machine learning. Also, a large amount of detailed documentation has been written for it, and it is installed by default in Yandex DataSphere.

# Training

For testing, you need to upload data in csv format. It is desirable to take data of a sufficiently large size for better training of the model. Before training, you need to think about what will be a reference summary and what will be text. Training and testing was carried out in Yandex DataSphere.

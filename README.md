# QuestionAnswer
### Introduction
I created this project to showcase the abilities of deep neural networks with regard to natural language processing tasks such as question-answering systems. 
This project was created for educational purposes only and is by no means perfect. If you have any questions, please feel free to contact me at micahreich02@gmail.com

### Deep Neural Networks
Neural networks are a set of algorithms, modeled loosely after the human brain, that are designed to recognize patterns. They interpret sensory data through a kind of machine perception, labeling or clustering raw input. The patterns they recognize are numerical, contained in vectors, into which all real-world data, be it images, sound, text or time series, must be translated.
(Skymind.ai)

### GRU Networks
This question-answering system utilizes a GRU (gated recurrent unit) deep neural network

<img src="https://www.data-blogger.com/wp-content/uploads/2017/08/gru.png"/>
<br />
GRU Networks utilize two gates to deal with the problem of "vanishing gradients" which arise in regular recurrent neural networks.
To do this, GRU networks use a update and reset gate.

- The update gate: decides which information to pass along from previous time steps of the model to future cells
- The reset gate: decides decides which information to forget from previous time steps
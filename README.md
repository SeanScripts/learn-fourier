# learn-fourier
 Simple neural net example to learn a Fourier transform. 
 
 Used a convolutional neural network; only one layer is required. The number of filters required is equal to the number of wavelengths in the output, or twice that if phase is encoded (with sine and cosine components; I'm not sure whether I can use complex coefficients in a neural network, but if I could, that would be awesome.) Precision of the encoding depends on the length of the input signal, for basically the same reason as the uncertainty principle.
 
 This is an interesting exploration of the connection between representation theory and neural networks, I think, since the filters learned were essentially the characters of the representation. It's easy to determine exactly what number of filters is required here, but if it were designed differently, or run on a more complex problem, the question of how to pick the right hyperparameters would be a difficult one, and this problem, neural architecture search, is one of the main problems in machine learning that I am interested in.
 
 

# Music Generation AI

This project consists of two parts:
1. An LSTM neural network for generating songs in a certain genre
2. A traditional machine learning classifier that detects song genres

---

The LSTM neural network was trained on simplified MIDI song files so that it would learn the rules of nuances of the music. The model's predictive capabilities were then used to generate original pieces. And to quantitatively measure the performance of the model, a classifier was used to assign a similarity score between a generated song and the target genre.
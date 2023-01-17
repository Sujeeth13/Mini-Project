##Image dehazing in CCTV cameras:  

• Approached the problem using an Attentive Generative Adversarial Network.  

• The trained model creates attention maps using LSTM blocks in the generator phase for identifying the hazy
regions. High attention values implies dense haze regions.  

• The autoencoder phase in the generator creates the haze free images with guidance from the attention maps and
the discriminator checks its legitimacy.  


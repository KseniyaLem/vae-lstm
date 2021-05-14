ANOMALY DETECTION FOR TIME SERIES USING VAE-LSTM HYBRID MODEL

https://www.oxford-man.ox.ac.uk/wp-content/uploads/2020/06/ANOMALY-DETECTION-FOR-TIME-SERIES-USING-VAE-LSTM-HYBRID-MODEL.pdf


Proposal:
[proposal (2).pdf](https://github.com/KseniyaLem/vae-lstm/files/6404273/proposal.2.pdf)



Project goals: 

1. Reproduce the model, see how the model depends on hyperparameters. 

2. Check the model on artificial datasets. 

3. Change the model: simulate a complex VAE, then a complex LSTM, check what is best for detecting anomalies. 

4. To train the VAE model, we generate rolling windows from the training data. The LSTM model operates on the VAE embeddings of a sequence of k non-overlapping windows. How much will the model change if the windows are the same for both models? 


![Scheme](https://user-images.githubusercontent.com/66911275/118230764-d49bb380-b496-11eb-803b-c8cd31fabd9d.JPG)

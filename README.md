# LSTM_autoencoder<br/><br/>

This code was written based on Pytorch.<br/>
I'm not an expert, but i think i've studied enough about LSTM autoencoder<br/>

Dataset was obtained my experiment which was acoustic emission testing under scratch motion using CSM scratch tester<br/>
The dataset was sliced by moving window size of 1,000 and mini-batch size of 100 was consisted for training<br/>
The model structure consisted of 1 layer of encoder and 1 layer of decoder<br/>
The "time-distributed layer" was used i referenced what someone had made already<br/>
For the validation and test process, the different dataset were hired<br/>
I checked the performance was good enough i think<br/><br/>

Inside of "test" folder, there are a code based on Keras platform also<br/>

It was my first code for Deep Learning, let me know if there is anything i miss<br/>
Hope someone who feel difficult about LSTM-autoencoder this help to understand<br/>

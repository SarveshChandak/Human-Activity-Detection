# Human-Activity-Detection-using-LRCN

Human activities such as walking, fighting, running have been identified from video input using UCF50 dataset. Model has been created using Long-term Recurrent Convolutional Network (LRCN), which is a combination of CNN and LSTM. LRCN processes the variable-length visual input with a CNN. Their output are fed into a stack of recurrent sequence models (LSTM). The final output from the LSTM is a vaiable-length prediction. This makes LRCN proper model to handle tasks with time-varying inputs and output. Around 83% accuracy was achieved.  
  
This can be further enhanced to be used in live CCTV camera feeds to detect human activities and find out any suspicious activity such as violence and running on roads.

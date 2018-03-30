# Incremental-Learning<br>
Ability of a machine learning model to adjust to new data of previously unseen classes without forgetting the previously
learnt knowledge
<p align="center">
<img src="https://github.com/ShwetaSood/Incremental-Learning/blob/master/photos/ICR.png"><br>
</p>

The following folders are present<br>
Note - Needs internet connectivity to download the MNIST files<br><br>

1. Full_Trained_CNN:<br>
		(a) cnn_model.py - The file describing the CNN model<br>
		(b) dataread.py - The file used for reading MNIST data and using cnn_model.py to train a network on class 1,2. Saves checkpoints that will be used for incremental training<br><br>

2. Vanilla_Trained_CNN_class_1_2_3: Regular Vanilla CNN initilialized with pre-trained_weights for class 1,2 and tested on class 1,2,3<br>
		(a) vanilla_cnn_model.py - The file describing the CNN model<br>
		(b) vanilla_dataread.py - The file used for reading MNIST data and using cnn_model.py to train a network on class 1,2 and tested on class 1,2,3<br><br>

3. Vanilla_Trained_CNN_class_1_2_3_4: Regular Vanilla CNN initilialized with pre-trained_weights for class 1,2 and tested on class 1,2,3,4<br>
		(a) cnn_model.py - The file describing the CNN model<br>
		(b) dataread.py - The file used for reading MNIST data and using cnn_model.py to train a network on class 1,2 and tested on class 1,2,3,4<br><br>

4. Incr_Trained_CNN_Class_1_2_3: The proposed CNN with revised cost function initilialized with pre-trained_weights for class 1,2 and tested on class 1,2,3<br>
		(a) vanilla_cnn_model.py - The file describing the CNN model<br>
		(b) vanilla_dataread.py - The file used for reading MNIST data and using cnn_model.py to train a network on class 1,2 and tested on class 1,2,3<br><br>

5. Incr_Trained_CNN_Class_1_2_3_4: The proposed CNN with revised cost function initilialized with pre-trained_weights for class 1,2 and tested on class 1,2,3,4<br>
		(a) cnn_model.py - The file describing the CNN model<br>
		(b) dataread.py - The file used for reading MNIST data and using cnn_model.py to train a network on class 1,2 and tested on class 1,2,3,4<br><br>

6. Exp_Incr_Trained_CNN_Class_1_2_3: Testing the CNN without incorporating loss on old class images (only using new class images and weight norm)<br>
		(a) cnn_model.py - The file describing the CNN model<br>
		(b) dataread.py - The file used for reading MNIST data and using cnn_model.py to train a network on class 1,2 and tested on class 3<br>

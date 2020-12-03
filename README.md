Below are the few steps to run the model.

Steps:
*Download zip named mini_project and extract it . 
* Install some essential packages using:
	- `pip3 install numpy`
	- `pip3 install pandas`
	- `pip3 install opencv-python`
	- `pip3 install tensorflow`
	- `pip3 install keras`
* Go to the directory of project: `cd phocnet_keras`
* Now, 'extract here' the dataset present in `word` & `xml` folders.
Note : "We have used only approx 1500 images of dataset(for training and testing) 
		as complete IAM dataset would take hours to train the model"
* We are now ready to execute the model. Execute: `python3 train.py`

*Accuracy acheived is about 91% on training and ~67 % on testing . 

## Reference
```
@inproceedings{Sudholt2017-EWS,
   booktitle = {Proc. Int. Conf. on Document Analysis and Recognition},
   author = {Sudholt, Sebastian and Fink, Gernot A.},
   title = {{Evaluating Word String Embeddings and Loss Functions for CNN-based Word Spotting}},
   year = {2017}
}
```

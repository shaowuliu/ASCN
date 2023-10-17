This is the code of the paper "ACSN: Attention Capsule Sampling Network for Diagnosing COVID-19 based on Chest CT Scans"

python environment:

	python == 3.6
	h5py == 2.10.0
	hdf5 == 1.10.6
	keras ==  2.2.4
	numpy == 1.19.2
	pandas ==  1.1.5
	scikit-image == 0.17.2
	scikit-learn ==  0.22.1
	torch == 1.10.2 
 
model parameter:
	This weights-2class-v1-71.h5 is the pre-training parameter of the model in the feature extraction stage, and this two623_108_noweight_model.h5 is the pre-training parameter of the weighted extraction and fusion sampling part.

train.ipynb
	train.ipynb is the training process of weighted extraction code and fusion sampling code in this paper. This process is mainly to extract the patient's features and slice them for training, and finally get the effective parameters of the model.


test.ipynb :
	test.ipynb  is the code of the final model, which also includes the test code. It is mainly to input all the slices of a patient to get the test results of the patient.

	old and my-new  are the code for reference and the final modified code, respectively.

The report should contain the following:

Overview of the analysis:
The purpose of this an analysis is to build a deep learning model to predict wether the charity organizations funded by Alphabet Soup will be succesfull or not based on the input features given in the .csv file.

Results:

- Data Preprocessing

	- What variable(s) are the target(s) for your model?
		- The target variable for the model is the 'IS_SUCCESSFUL' column in the .csv file, which indicates if the charity organization was succesfull in its efforts. clasified ina binary factoe (1 if successful ans 0 if not)

	- What variable(s) are the features for your model?
		- The considered featured variables for the modelare all other columns excepting the 'IS_SUCCESSFUL' column and the 'EIN' and 'NAME' columns that were dropped as part of the preprocessing of the data
	- What variable(s) should be removed from the input data because they are neither targets nor features?
		- 'EIN' and 'NAME' columns were removed as be considered non-beneficial for the analysis and modeling process.
		
		
- Compiling, Training, and Evaluating the Model

How many neurons, layers, and activation functions did you select for your neural network model, and why?
	My model consists of two hidden layers with 64 and 32 neurons, repectively, followed by an output layer with a single neuron. I have completed three different tests trying diferent activation finctions, like sigmoid, tanh and relu. 
	- Were you able to achieve the target model performance?
		- No, my best accuracy was near 73% using diferent combinations of the activation methods, considering a non-linearity on the data. the model was trained for 100 epochs with an adam optimizer and a binary cros-entropy loss function.
	- What steps did you take in your attempts to increase model performance?
		- I used fifferent combinations of the activation methods, however those were unsuccesfull.

Summary:
	- Overall, my algorith achieved a moderate level of accuracy in predicting the success of charity organizations. There is more work and things to learn to harnes more preformace out of the neural network models to provide a valuable insight and enhance the predictive capabilities of the model.
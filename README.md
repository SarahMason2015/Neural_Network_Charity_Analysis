**<h1> Alphabet Soup Charity</h1>**
<h2> Overview of Analysis</h2>
<p>Alphabet Soup is a NPO that provides funding for organizations to protect the environment, improve wellbeing and help the world. This analysis should ensure the foundations money will be used effectively. A deep learning neural network will help to predict which organizations should receive donations. 
  
<h2> Results</h2> 

<p>Data Preprocessing
  
  -	The data provided shows a column for 'IS_SUCCESSFUL,' and will be the targeted data point for these predictions.
  -	Features - AFFILIATION, CLASSIFCATION, ORGANIZATION, APPLICATION_TYPE, USE_CASE, ASK_AMT, SPECIAL_CONSIDERATIONS, INCOME_AMT, and STATUS are features for this model.
  -	The columns for "NAME" and "EIN" have no direct effect on the success/falure rate, and have been excluded from processing.
  
p>Compiling, Training, and Evaluating the Model
-	80 units, single layer. 10 epochs. 54% accuracy
-	40 units in layer one, 20 unites in layer 2. 30 epochs. 55% accuracy
-	45 units, single layer. 15 epochs. 55% accuracy.
-	Unfortunately, no. I faily splendedly. 

<h2> Summary</h2>
<p> I did not recieve the desired outcome. Other models would probably deliver better results. Random Forest would most likely produce more desireable results. 


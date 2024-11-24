# deep_learning_challange

Overview: deep learning model which helps the nonprofit foundation Alphabet Soup to design tool that can help it select the applicants for funding with the best chance of success in their ventures

Results:
    varibles used for target were "IS_SUCCESSFUL" candidates:
    varibles used for feature were "CLASSIFACTION_OTHER" and the "application types other" to see if the lower amounts of unique values can predit success

    Columns not used were the demograhpics of the applicants that needed were dropped durning the filtering 
    of the data such as "EIN" and "NAME"


Training: 3 layers with 8 units in first, 5 in the second layer, and 1 in the outer layer and all containing "relu"
as my acitvation function. I chose this beccuase I beleive 3 should be a good amount of layers to achieve a good 
accuarcy score within the model, and i didnt want to change the activcation functions or the number neurons,accarcy score 
was above 75 within 10 epochs suggests that the model might be overfitted
with a low amount of loss. I tried use more layers with more interations to see it makes any changes.

summary: overall the results was an .98 near a perfect score and a different model by 
adding more feature columns into the dataset with more units could have a better chance of the model not being overfitted, 
and produce more accuacte data withn the model.

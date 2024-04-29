# Diabetes-Prediction
problématique: 
on veut detecter les personnes diabetiques


*Exloratory Data Analysis 

*DataPreprocessing
	essayer avec Decision tree pour faire le datapreprocessing , feature engeneering en mettant le random_state=0 pour assurer la 	repetabilité !! 
	puis j'ai essayé le Random Forest car il lutte contre l'overfitting 


*Model optimisation:

	Liste de modeles 
	Optimisation GridSearch + randomizedsearch
	compromis precision /recall :au lieu de faire "model.predict()" on va sacrifier un peu de precision pour avoir plus de recall :
	def model_final (model,X,threshold):
  	    return model.decision_function(X) >threshold

*Predictive System

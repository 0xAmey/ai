These notes are mostly just some important points w/o much context.

#### Week 1
  I'm starting from d2l.ai as it's the most comprehensive resource I could find but I'm sure I'll branch out into reading though other sources on the way.
  
  - [Introduction](https://d2l.ai/chapter_introduction/index.html)
	- You can think of the parameters as knobs that we can turn, manipulating the behavior of the program. Fixing the parameters, we call the program a model.
	- The set of all distinct programs (input-output mappings) that we can produce just by manipulating the parameters is called a family of models.
	- And the meta-program that uses our dataset to choose the parameters is called a learning algorithm.
	- where we try to predict a designated unknown label based on known inputs given a dataset consisting of examples for which the labels are known, is called supervised learning
	- some core components that will follow us around, no matter what kind of machine learning problem we take on:
		1.  The _data_ that we can learn from.
			- Generally, we are concerned with a collection of examples. In order to work with data usefully, we typically need to come up with a suitable numerical representation. Each _example_ (or _data point_, _data instance_, _sample_) typically consists of a set of attributes called _features_ (sometimes called _covariates_ or _inputs_), based on which the model must make its predictions. In supervised learning problems, our goal is to predict the value of a special attribute, called the _label_ (or _target_), that is not part of the model’s input.
		2.  A _model_ of how to transform the data.
			- By _model_, we denote the computational machinery for ingesting data of one type, and spitting out predictions of a possibly different type.
		3.  An _objective function_ that quantifies how well (or badly) the model is doing.
		4.  An _algorithm_ to adjust the model’s parameters to optimize the objective function.
	- Kinds of Machine Learning problems
		- Supervised Learning
			- Regression (ex–predicting arbitrary numbers)
			- Classification
			- Tagging
			- Search
			- Recommender Systems
			- Sequence Learning
				- Tagging and Parsing
				- Speech Recognition
				- Text to Speech
				- Translation
		- Unsupervised and Self-Supervised Learning
			- ...

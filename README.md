# TechGraphic Novels
These are the ML concepts I think make strong graphic novels. Each has a clear visual metaphor, a natural conflict to build a story around, and a common beginner misunderstanding the story can fix. They’re in a suggested order, so each one builds on the last, and Maya and Lino could carry through as recurring characters.

## Foundations (natural sequels to linear regression)

#	Concept	Story hook	Why it suits a comic
1.	Overfitting vs. underfitting	Lino draws a wiggly line through every dot, then fails badly on new days.	Probably the most important idea in ML, and it’s very visual: straight, curvy and crazy-wiggly lines side by side.
2.	Train / validation / test split	Practice exam vs. the real exam, with a villain who peeks at the answer key (data leakage).	Cheating makes a natural plot, and leakage is a trap even experts fall into.
3.	Logistic regression / classification	“Will a customer buy, yes or no?” The sigmoid works like a dimmer switch.	It’s a direct sequel to linear regression and introduces probability and decision boundaries.
4.	Precision, recall and the confusion matrix	A smoke alarm that goes off at toast vs. one that sleeps through a fire.	Beginners find this confusing, and the false-alarm vs. missed-fire tradeoff has real stakes.

## Classic algorithms (strong visual metaphors)

#	Concept	Story hook	Why it suits a comic
1.	Decision trees	A game of 20 Questions to identify a mystery fruit.	Each branch can be a panel, so the structure is the comic layout.
2.	Random forests / ensembles	A village council of trees votes, and the crowd beats any single expert.	“Wisdom of crowds” makes a satisfying story payoff.
3.	k-Nearest Neighbors	A new kid in town is judged by the 3 closest houses.	It’s spatial and intuitive, and it shows how the choice of k changes the answer.
4.	k-Means clustering	Sorting a giant pile of unlabeled candy into groups, with centroids walking to the middle of each group.	It introduces unsupervised learning, and the centroids moving makes good animation in panels.
5.	PCA / dimensionality reduction	Finding the best angle to cast a shadow of a teapot.	It’s an abstract idea with a near-perfect physical metaphor.
6.	Regularization	Lino’s knobs get a “budget,” so he can’t turn them all the way up.	It pairs naturally with the overfitting story.

## Deep learning and modern AI: Concept	Story hook	Why it suits a comic
1. Neural networks + backpropagation	A factory assembly line where blame for a bad product is passed backward to each worker.	Backprop is notoriously hard to explain, and this metaphor fixes that.
2. Convolutional neural networks	A detective with a flashlight scanning a photo for edges, then shapes, then faces.	It’s visual by nature, since it’s about how machines see.
3. Word embeddings	Words live on a city map, and “king − man + woman” leads you to “queen.”	A map is a perfect comic setting.
4. Attention / Transformers	A dinner party where every word decides whom to listen to.	It’s very current, very confusing to most people, and great for crowd scenes.
5. Large language models	Lino plays a game of “guess the next word,” billions of times.	Everyone uses LLMs, and almost no one knows how they work.
6. Diffusion models	A sculptor who removes noise step by step to reveal a statue.	The visuals are striking and make good page turns.
7. Reinforcement learning	Training a robot dog with treats, and the explore-vs-exploit dilemma.	It has trial-and-error humor built in.

## Trust and responsibility: Concept	Story hook	Why it suits a comic
1. Explainable AI (SHAP)	Teammates split credit fairly for a won game, which is how Shapley values work.	It’s underexplained to beginners and increasingly important in medicine and law.
2. Bias in data and fairness	The model learns from a lopsided notebook and makes unfair predictions.	It has real moral stakes, and characters can disagree, which is good drama.

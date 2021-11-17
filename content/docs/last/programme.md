---
weight: 1
bookFlatSection: true
title: "Programme"
---

The workshop will take place on Tuesday 29th November, between 0900h CET and 1300h CET. To join the event, please register and follow the instructions you find on https://aixia2021.disco.unimib.it/ .

**Times are CET**

09:00—09:05: Welcome

09:05—09:50: _Sara Magliacane_, Causality-inspired ML: what can causality do for ML? The domain adaptation case. **Keynote**

09:50—10:05: _Andrea Duggento, Maria Guerrisi and Nicola Toschi_, Nonlinear Granger causality from random recurrent neural networks

10:05—10:20: _X. San Liang_, Normalized causality analysis and causal graph reconstruction based on a rigorous formalism of information flow

10:20—10:35: _Rafael Cabañas, Alessandro Antonucci and Marco Zaffalon_, Bounding Unidentifiable Causal Queries by Credal Nets

10:35—10:50: _Celine Beji, Florian Yger and Jamal Atif_, Non parametric estimation of causal populations in a counterfactual scenario

10:50—11:00: **Break**

11:00—11:45: _Lorenzo Magliani_, Naturalizing Causality. **Keynote**

11:45—12:00: _Gabriele Sottocornola, Fabio Stella and Markus Zanker_, Counterfactual Contextual Multi-Armed Bandit to Diagnose Post-Harvest Diseases of Apple

12:00—12:15: _Ruta Liepina, Adam Wyner and Giovanni Sartor_, Recent Work on Causal Reasoning in Law

12:15—12:30: _Marco Lippi, Stefano Mariani, Matteo Martinelli and Franco Zambonelli_, The Role of Causality in Autonomous Development

# Keynotes

## Sara Magliacane. Causality-inspired ML: what can causality do for ML? The domain adaptation case

### Abstract
Applying machine learning to real-world cases often requires methods that are trustworthy and robust w.r.t. heterogeneity, missing not at random or corrupt data, selection bias, non i.i.d. data etc. and that can generalize across different domains. Moreover, many tasks are inherently trying to answer causal questions and gather actionable insights, a task for which correlations are usually not enough. Several of these issues are addressed in the rich causal inference literature. On the other hand, often classical causal inference methods require either a complete knowledge of a causal graph or enough experimental data (interventions) to estimate it accurately.

Recently, a new line of research has focused on causality-inspired machine learning, i.e. on the application ideas from causal inference to machine learning methods without necessarily knowing or even trying to estimate the complete causal graph. In this talk, I will present an example of this line of research in the unsupervised domain adaptation case, in which we have labelled data in a set of source domains and unlabelled data in a target domain ("zero-shot"), for which we want to predict the labels. In particular, given certain assumptions, our approach is able to select a set of provably "stable" features (a separating set), for which the generalization error can be bound, even in case of arbitrarily large distribution shifts. As opposed to other works, it also exploits the information in the unlabelled target data, allowing for some unseen shifts w.r.t. to the source domains. While using ideas from causal inference, our method never aims at reconstructing the causal graph or even the Markov equivalence class, showing that causal inference ideas can help machine learning even in this more relaxed setting.

### Links
* https://arxiv.org/abs/1611.10351
* https://arxiv.org/abs/1707.06422

### Bio
Sara Magliacane is an assistant professor in the Informatics Institute at the University of Amsterdam and a Research Scientist at the MIT-IBM Watson AI Lab. She received her PhD at the VU Amsterdam on logics for causal inference under uncertainty in 2017, focusing on learning causal relations jointly from different experimental settings, especially in the case of latent confounders and small samples. After a year in IBM Research NY as a postdoc, she joined the MIT-IBM Watson AI Lab in 2019 as a Research Scientist, where she has been working on methods to design experiments that would allow one to learn causal relations in a sample-efficient and intervention-efficient way. Her current focus is on causality-inspired machine learning, i.e. applications of causal inference to machine learning and especially transfer learning, and formally safe reinforcement learning.

## Lorenzo Magnani. Naturalizing Causality  

### Abstract
Since I am adopting a naturalized perspective, I cede no opening space to skepticism about causality which, if true, would erode masses of what everybody thinks that everybody knows. The polar opposite would be a kind of what John Woods calls epistemicism, according to which the right working assumption is that what everyone think that everyone knows is actually so in the main. My working assumption is instead that we are all natural beings resident in the natural order of things and subjects of the causality embedded in nature and artifacts. We can certainly say that causes are not exceptional phenomena, but that rather are highly contextualized polyadic dynamic affairs: I think the only philosophical guess we can dare is that singular occurrences of causalities are made possible by the individuating capacities of a context. Are we able to individuate them?

With the mathematicization of science and the success of Newtonian theory causality lost its traditional importance. Indeed, dynamical laws rendered as differential equations can be exploited to compute the state of the world at one time as a function of its state at another. In turn, quantum mechanics introduced indeterminism. As Russell said, in the paper On the notion of cause (1914), the notion of cause is so puzzling (a folk concept, we can say) that should be eliminated from exact science and replaced with that of global laws of dynamical evolution. On the contrary, it is the philosopher of science Nancy Cartwright that, in Causal laws and effective strategies (1979), contended that causal knowledge is crucial and necessary in practical reasoning. I will try to answer the following philosophical question: how causal notions enter into the description of Nature? Given the fact we are in general not able to recuperate the causal information from the global dynamics, precise formal frameworks have been created (for example by Judea Pearl): Structural Causal Models (SCMs), as causal networks. A SCM represents a complex system as a modular assemblage of stable, reliable, and independent constituents called “mechanisms”. We need these networks, since there are many ways of putting together mechanisms to get the same evolution at the global level, and we cannot in general recuperate the causal information from the global dynamics (cf. Jenann Ismael’s analysis of causality). We are not only epistemically concerned with prediction starting from information about initial conditions, we are also engineeringly interested to act in the world. In sum, causal knowledge is “practically” fundamental because beings like us are not mere observers of nature but agents that act, intervene, and manipulate in casual networks that need to be individuated and made explicit. 

### Links
https://link.springer.com/book/10.1007/978-3-030-81447-2

### Bio
Lorenzo Magnani, philosopher, epistemologist, and cognitive scientist, is a professor of Philosophy of Science at the University of Pavia, Italy, and the director of its Computational Philosophy Laboratory He has been a visiting researcher at Carnegie Mellon University, McGill University, the University of Waterloo and Georgia Institute of Technology, and a Visiting Professor at Georgia Institute of Technology, City University of New York, and at Sun Yat-sen University, China. In the event of the 50th anniversary of the re-building of the Philosophy Department of Sun Yat-sen University in 2010, an award was given to him to acknowledge his contributions to the areas of philosophy, philosophy of science, logic, and cognitive science. A Doctor Honoris Causa degree was awarded to by the Senate of the Ştefan cel Mare University, Suceava, Romania. In 2015 Lorenzo Magnani has been appointed member of the International Academy for the Philosophy of the Sciences (AIPS). He currently directs international research programs in the EU, USA, and China. His book Abduction, Reason, and Science (New York, 2001) has become a well-respected work in the field of human cognition. The book Morality in a Technological World (Cambridge, 2007) develops a philosophical and cognitive theory of the relationships between ethics and technology in a naturalistic perspective. The book Abductive Cognition. The Epistemological and Eco-Cognitive Dimensions of Hypothetical Reasoning and the last monograph Understanding Violence. The Intertwining of Morality, Religion, and Violence: A Philosophical Stance have been published by Springer, in 2009 and 2011. A new monograph has been published by Springer in 2017, The Abductive Structure of Scientific Creativity. An Essay on the Ecology of Cognition, together with the Springer Handbook of Model-Based Science (edited with Tommaso Bertolotti). The last book, Eco-Cognitive Computationalism. Cognitive Domestication of Ignorant Entities depict, published by Springer, offers an entirely new dynamic perspective on the nature of computation. He edited books in Chinese, 18 special issues of international academic journals, and 20 collective books, some of them deriving from international conferences. Since 1998, initially in collaboration with Nancy J. Nersessian and Paul Thagard, he created and promoted the MBR Conferences on Model-Based Reasoning. Since 2011 he is the editor of the Book Series Studies in Applied Philosophy, Epistemology and Rational Ethics (SAPERE), Springer, Heidelberg/Berlin. 

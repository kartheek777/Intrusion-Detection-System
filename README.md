# Intrusion-Detection-System

Project Title: Intrusion Detection System


ABSTRACT
With the impending era of internet, the network security has become the key foundation for lot of financial and business web applications. Intrusion detection is one of the looms to resolve the problem of network security. Imperfectness of intrusion detection systems (IDS) has given an opportunity for data mining to make several important contributions to the field of intrusion detection. In recent years, many researchers are using data mining techniques for building IDS. Here, we propose a new approach by utilizing data mining techniques such as neuro-fuzzy and radial basis support vector machine (SVM) for helping IDS to attain higher detection rate. The proposed technique has four major steps: primarily, k-means clustering is used to generate different training subsets. Then, based on the obtained training subsets, different neuro-fuzzy models are trained. Subsequently, a vector for SVM classification is formed and in the end, classification using radial SVM is performed to detect intrusion has happened or not. To illustrate the applicability and capability of the new approach, the results of experiments on KDD CUP 1999 dataset is demonstrated. 


SYSTEM ANALYSIS

EXISTING SYSTEM:
Nodes that cannot communicate directly depend on their neighbours in order to forward their messages to the appropriate destination. Applications of mobile ad hoc networks have increased requirements in order to ensure high quality of service for the provided services. Security in such infrastructure-less networks has been proven to be a challenging task. Many security threats arise against mobile ad hoc networks, as they are inherently vulnerable due to the way the build and preserve connectivity characteristics. The open medium presents the network with the first and most serious vulnerability. Unlike wired networks where an aggressor in order to launch an attack has to gain access to a wired infrastructure, firewalls and gateways, in ad hoc networks there is no clear line of defence. Every node is vulnerable and the good performance of the network depends on every node or at least on every node participating in a path from the source to a given destination

DISADVANTAGES OF EXISTING SYSTEM:
a.	The insecure open medium combined with poor physical protection presents another disadvantage. 
b.	Each node is able to roam independently running the risk to be easily compromised by a malicious attacker. 
c.	Furthermore, when more sophisticated attacks take place nodes can be easily exploited.
d.	In addition, wireless ad hoc networks lack a centralized monitoring and management point.  

PROPOSED SYSTEM:
We present the whole framework of the new approach. Then we discuss the four main modules, i.e., k-means clustering module, neuro-fizzzy training module, SVM training vector module, and radial-SVM classification module. The proposed intrusion detection technique initially clusters the given training data set by using k-means clustering technique into k-clusters, where 'k' is the number of desired clusters. In the next step, neuro-fizzzy training is used to train 'k' neural networks, where each of the data in a particular cluster is trained with the respective neural network associated with each of the cluster. Subsequently, vector for SVM classification is generated. This vector consists of attribute values obtained by passing each of the data through all of the trained neuro-fuzzy classifiers, and an additional attribute which has membership value of each of the data. As a last step, classification is performed by using radial SVM to detect intrusion has happened or not.

ADVANTAGES OF THE PROPOSED SYSTEM:
•	Our proposed technique comes up with a solution where the number of attributes defining each of the data is reduced to a small number through a sequence of steps. This process ultimately results in making the intrusion detection more efficient and also yields a less complex system with a better result.

LITERATURE SURVEY

1)  Anomaly Detection based on Machine Learning: Dimensionality Reduction using PCA and Classification using SVM 

AUTHORS:  Annie George 
Anomaly detection has emerged as an important technique in many application areas mainly for network security. Anomaly detection based on machine learning algorithms considered as the classification problem on the network data has been presented here. Dimensionality reduction and classification algorithms are explored and evaluated using KDD99 dataset for network IDS. Principal Component Analysis for dimensionality reduction and Support Vector Machine for classification have been considered for the application on network data and the results are analysed. The result shows the decrease in execution time for the classification as we reduce the dimension of the input data and also the precision and recall parameter values of the classification algorithm shows that the SVM with PCA method is more accurate as the number of misclassification decreases.










2)  A data mining framework for building intrusion detection model 

AUTHORS:  W.K. Lee, S.J.Stolfo 

There is often the need to update an installed intrusion detection system (IDS) due to new attack methods or upgraded computing environments. Since many current IDSs are constructed by manual encoding of expert knowledge, changes to IDSs are expensive and slow. We describe a data mining framework for adaptively building Intrusion Detection (ID) models. The central idea is to utilize auditing programs to extract an extensive set of features that describe each network connection or host session, and apply data mining programs to learn rules that accurately capture the behavior of intrusions and normal activities. These rules can then be used for misuse detection and anomaly detection. New detection models are incorporated into an existing IDS through a meta-learning (or co-operative learning) process, which produces a meta detection model that combines evidence from multiple models. We discuss the strengths of our data mining programs, namely, classification, meta-learning, association rules, and frequent episodes. We report on the results of applying these programs to the extensively gathered network audit data for the 1998 DARPA Intrusion Detection Evaluation Program







3)  A Review of Anomaly based Intrusion Detection Systems 

AUTHORS:  V. Jyothsna, V. V. Rama Prasad, K. Munivara Prasad 

With the advent of anomaly-based intrusion detection systems, many approaches and techniques have been developed to track novel attacks on the systems. High detection rate of 98% at a low alarm rate of 1% can be achieved by using these techniques. Though anomaly-based approaches are efficient, signature-based detection is preferred for mainstream implementation of intrusion detection systems. As a variety of anomaly detection techniques were suggested, it is difficult to compare the strengths, weaknesses of these methods. The reason why industries don’t favor the anomaly-based intrusion detection methods can be well understood by validating the efficiencies of the all the methods. To investigate this issue, the current state of the experiment practice in the field of anomaly-based intrusion detection is reviewed and survey recent studies in this. This paper contains summarization study and identification of the drawbacks of formerly surveyed works.










4)  Research of Intrusion Detection based on Principal Components Analysis 

AUTHORS:  CHEN Bo, Ma Wu 

The effective way of improving the efficiency of intrusion detection is to reduce the heavy data process workload. In this paper, the dimensionality reduction use of technology in the classic dimensionality reduction algorithm principal component to analysis large-scale data source for reduced-made features of the original data be retained and improved the efficiency of intrusion detection. And use BP neural network training the data after dimensionality reduction, will be effective in normal and abnormal data distinction, and achieved good results.
















5) Solving multiclass learning problems via error-correcting output codes 

AUTHORS: T. G.Dietterich, G.Bakiri 

Multiclass learning problems involve finding a definition for an unknown function f(x) whose range is a discrete set containing k > 2 values (i.e., k "classes"). The definition is acquired by studying collections of training examples of the form (xi, f(xi)). Existing approaches to multiclass learning problems include direct application of multiclass algorithms such as the decision-tree algorithms C4.5 and CART, application of binary concept learning algorithms to learn individual binary functions for each of the k classes, and application of binary concept learning algorithms with distributed output representations. This paper compares these three approaches to a new technique in which error-correcting codes are employed as a distributed output representation. We show that these output representations improve the generalization performance of both C4.5 and backpropagation on a wide range of multiclass learning tasks. We also demonstrate that this approach is robust with respect to changes in the size of the training sample, the assignment of distributed representations to particular classes, and the application of overfitting avoidance techniques such as decision-tree pruning. Finally, we show that--like the other methods--the error-correcting code technique can provide reliable class probability estimates. Taken together, these results demonstrate that error-correcting output codes provide a general-purpose method for improving the performance of inductive learning programs on multiclass problems.

IMPLEMENTATION
MODULES:
1.	K-means Clustering Module
2.	Neuro-Fuzzy Training Module
3.	SVM Vector Generation Module
4.	Radial SVM Classifier Module



MODULE DESCRIPTION:
K-means Clustering Module
The clustering algorithms are used to group unlabeled data. In our proposed technique, we are intended to group our input data set into different clusters based on types of intrusions. Since our input data set consists of the normal data and four different types of attacks, training data set is grouped into 5 clusters using k-means clustering techniques. Examining and learning the behavior and characteristics of the single data point within a cluster can give hints and clue on all other data points in the same cluster. This is because of the fact that all data points inside a cluster differ only by a small amount and usually follow a more or less similar structure. Hence, the data and then classifying is a simpler method and is less time consuming. 
Neuro-Fuzzy Training Module
K-means clustering results in the formation of  ‘K’ clusters where each cluster will be  a type of intrusion or the normal data. For every cluster, we have Neuro-fuzzy classifiers associated with it, i.e., there will be 5 number of Neuro fuzzy classifiers is trained with the data in the respective cluster. Neuro-fuzzy makes use of back propagation learning to find out the input membership function parameters and least mean square method to find out the consequent parameters. 
The first hidden layer maps the input variable correspondingly to each membership function. In the second hidden layer, T-norm operator is used to compute the antecedents of the rules. The rules strengths are normalized in the third hidden layer and subsequently in the fourth hidden layer the consequents of the rules are found out. 
SVM Vector Generation Module
Classification of the data point considering all its attributed is a very difficult task and takes much time for the processing, hence decreasing the number of attributes related with each other of the data point is of paramount importance. The main purpose of the proposed technique is to decrease the number of attributes associated with each data, so that classification can be made in a simpler and easier way. Neuro-fuzzy classifier is employed to efficiently decrease the number of attributes. 
Radial SVM Classifier Module
This classifier is used as it produces better results for binary classification when compared to the other classifiers. But use of linear SVM has the disadvantages of getting less accuracy result, over fitting results and robust to noise. These short comings are effectively suppressed by the use of the radial SVM where nonlinear kernel functions are used and the resulting maximum margin hyper plane  fits in a transformed feature space. In our proposed technique, nonlinear kernel functions are used and the resulting margin hyper plane fits in a transformed feature space. When the kernel used is a Gaussian radial basis function, the corresponding  feature space is a Hilbert space of infinite dimensions. 


DATA FLOW DIAGRAM:

1.	The DFD is also called as bubble chart. It is a simple graphical formalism that can be used to represent a system in terms of input data to the system, various processing carried out on this data, and the output data is generated by this system.
2.	The data flow diagram (DFD) is one of the most important modeling tools. It is used to model the system components. These components are the system process, the data used by the process, an external entity that interacts with the system and the information flows in the system.
3.	DFD shows how the information moves through the system and how it is modified by a series of transformations. It is a graphical technique that depicts information flow and the transformations that are applied as data moves from input to output.
4.	DFD is also known as bubble chart. A DFD may be used to represent a system at any level of abstraction. DFD may be partitioned into levels that represent increasing information flow and functional detail
								

UML :

UML stands for Unified Modeling Language. UML is a standardized general-purpose modeling language in the field of object-oriented software engineering. The standard is managed, and was created by, the Object Management Group. 
The goal is for UML to become a common language for creating models of object oriented computer software. In its current form UML is comprised of two major components: a Meta-model and a notation. In the future, some form of method or process may also be added to; or associated with, UML.
	The Unified Modeling Language is a standard language for specifying, Visualization, Constructing and documenting the artifacts of software system, as well as for business modeling and other non-software systems. 
The UML represents a collection of best engineering practices that have proven successful in the modeling of large and complex systems.
 The UML is a very important part of developing objects oriented software and the software development process. The UML uses mostly graphical notations to express the design of software projects.

GOALS:
	The Primary goals in the design of the UML are as follows:
1.	Provide users a ready-to-use, expressive visual modeling Language so that they can develop and exchange meaningful models.
2.	Provide extendibility and specialization mechanisms to extend the core concepts.
3.	Be independent of particular programming languages and development process.
4.	Provide a formal basis for understanding the modeling language.
5.	Encourage the growth of OO tools market.
6.	Support higher level development concepts such as collaborations, frameworks, patterns and components.
7.	Integrate best practices.


USE CASE DIAGRAM:
A use case diagram in the Unified Modeling Language (UML) is a type of behavioral diagram defined by and created from a Use-case analysis. Its purpose is to present a graphical overview of the functionality provided by a system in terms of actors, their goals (represented as use cases), and any dependencies between those use cases. The main purpose of a use case diagram is to show what system functions are performed for which actor. Roles of the actors in the system can be depicted.




CLASS DIAGRAM:
In software engineering, a class diagram in the Unified Modeling Language (UML) is a type of static structure diagram that describes the structure of a system by showing the system's classes, their attributes, operations (or methods), and the relationships among the classes. It explains which class contains information.



SEQUENCE DIAGRAM:
A sequence diagram in Unified Modeling Language (UML) is a kind of interaction diagram that shows how processes operate with one another and in what order. It is a construct of a Message Sequence Chart. Sequence diagrams are sometimes called event diagrams, event scenarios, and timing diagrams.


ACTIVITY DIAGRAM:
Activity diagrams are graphical representations of workflows of stepwise activities and actions with support for choice, iteration and concurrency. In the Unified Modeling Language, activity diagrams can be used to describe the business and operational step-by-step workflows of components in a system. An activity diagram shows the overall flow of control.





Team:

Team members	
Roles And     Skills	
Contributions

1.Naresh    Koppuravuri
 (# 999990482)	
Testing And Reporting
	
Data testing; Final testing, Reviewing and Reporting

2. Mohan Babu Chirumamilla (#999990532)	
Coding for development modules.	
Development of entire analysis code.














Deliverables And Check Points:


Checkpoint date	Expected Deliverable	Responsible team member(s)	Checkpoint results
02/22/2016	Development of modules 	Naresh koppuravuri,
mohan babu chirumamilla.	Developing the module.
03/08/2016	Implementation	Naresh koppuravuri,mohan babu chirumamilla	Implementing module.
			


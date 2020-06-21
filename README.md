<img src="MLHPCS.png">

## Corona UPDATE
As our hosting confernce [ISC canceld](https://www.isc-hpc.com/) this years meeting, we will move on and turn our workshop into an online event within the framework of the planed ISC online event: 

## Abstract
Over the last few years, Machine Learning (and in particular Deep Learning) (ML / DL) has become an important research topic in the High Performance Computing (HPC) community. Bringing new users and data intensive applications on HPC systems, ML / DL is increasingly affecting the design and operation of compute infrastructures. On the other hand, the ML / DL community is just getting started to utilize the performance of HPC, leaving many opportunities for better parallelization and scalability. The intent of this workshop is to bring together researchers and practitioners to discuss three key topics in the context of High Performance Computing and Machine Learning / Deep Learning: parallelization and scaling of ML / DL algorithms, ML / DL applications on HPC systems, and HPC systems design and optimization for ML / DL workloads.  

### Date: in conjunction with the [ISC 2020](https://www.isc-hpc.com/) online event 
* recordings of the talks will be available statting 6/20 on this site


### Topics / Scope
The aim of the workshop is to provide a platform for technical discussions and the presentation of work in progress, as well as, unsolved problems, which is complementary to the “Machine Learning Day” in the main conference program.

* Unsolved problems in ML / DL on HPC systems
* Scalable ML / DL algorithms
* Parallelization techniques 
* Libraries for ML / DL
* Tools + workflows for ML / DL on HPC systems
* Optimized HPC systems design and setup for efficient ML / DL 
* ML / DL applications on HPC Systems 

### Paper
MLHPCS paper will be published in the Springer LNCS post Conference Proceedings of the ISC.

## Invited Talks
### Deploying machine learning algorithms at Petaflop scale on secure HPC production systems with containers
by David Brayford form LRZ
{% include invited_talk_1.html  %}
#### Abstract
*comming soon*

#### [Slides](slides/DavidBrayfordLRZ.pdf)

#### About the Speaker
David Brayford is a Senior HPC & AI scientist working on the deployment of AI software at petascale on secure HPC system. Previously worked in scientific and numerical computing as well as high performance computing for several years including both commercial and academic setting. Extensive experience in 3D computer graphics including device driver development, physics based photorealistic rendering, scientific and medical visualization. Dr Brayford received his PhD from The University of Manchester in computer science in 2006. A short list of employers include: PixelFusion/ClearSpeed, the University of Utah, Scientific and Imaging Institute (SCI), BioFire Technology, GE Healthcare and The Leibniz Supercomputing Center (LRZ). 

###  Get Together - HPC, Big Data, and Machine Learning
by Sunna Torge form TU Dresden
{% include invited_talk_2.html  %}
#### Abstract
The developments in the last years have shown the necessity to bring the research areas HPC, Big Data, and Machine Learning closer together. Often, this was simply driven by the curiosity and visions of researchers. However, it also happened that people are working on related problems, but do not know of each other.
In order to support this moving together of the HPC, the Big Data, and the Machine Learning research communities, there are many different initiatives all over the world.
In my talk, I want to give you an impression of the activities at the Technical University Dresden in common with the University of Leipzig to push on the interchange between the research areas, enlarge the sight on common research problems, and support the interlocking between methodological and applicational research fields. A selection of ongoing Machine Learning projects are presented, which are undertaken in this scientific environments and benefit from the close integration of the HPC infrastructure, the application science, and the methodolgical expertise.

#### [Slides](slides/gettoGether.pdf)

#### About the Speaker
Sunna Torge holds a diploma degree in mathematics (Mathematical Logic) from University of Freiburg and PhD in computer science (Automated Deduction) from University of Munich, where she had a PhD and a Postdoctorial scholarship within the graduate school of Language, Information, and Logic. Sunna Torge has been working in the man-machine interface group at Sony Research (Europe) GmbH and held a professorship for theoretical computer science at the Applied University of Furtwangen. Since 2016 she is a member of the German national competence center for Big Data and Artificial Intelligence “ScaDS.AI” and a Machine Learning teacher at Technical University Dresden.  

### Distributed Deep Learning: Challenges & Opportunities 
by Peter Labus form Fraunhofer ITWM
{% include invited_talk_3.html  %}
#### Abstract
In this talk, I will give an overview about the opportunities HPC can provide to enhance Deep Learning research.
In particular, I will talk about distribution strategies for the training of Deep Neural Networks and challenges
one faces when trying to implement them. I will conclude my talk by giving an outline of how we tackle these challenges
within our own distributed Deep Learning framework Tarantella and show some recent benchmark results.

#### [Slides](slides/distributed_deep_learning.pdf)

#### About the Speaker
Peter Labus studied theoretical physics in Berlin, Vienna and Munich. He received a Ph.D. in theoretical particle physics from the International School of Advanced Studies (SISSA) Trieste, Italy, from which he also received a Master's degree in High Performance Computing.
In 2018, he joined the Competence Center for High Performance Computing of Fraunhofer ITWM as a research scientist. As the lead developer of the Tarantella framework, he is particularly interested in scalable distributed Deep Learning. Since 2019 he is the head of the large scale machine learning team.

## Paper Presentations

### SmartPred: Unsupervised Hard Disk Failure Detection  
presented by Philipp Rombach form the Institute for Machine Learning and Analytics (IMLA) at Offenburg University, Germany
{% include talk_1.html  %}
#### Abstract
Due to the rapidly increasing storage consumption worldwide, as well as the expectation of continuous availability of information, the complexity of administration in today's data centers is growing permanently. Integrated techniques for monitoring hard disks can increase the reliability of storage systems. However, these techniques often lack intelligent data analysis to perform predictive maintenance. To solve this problem, machine learning algorithms can be used to detect potential failures in advance and prevent them. In this paper, an unsupervised model for predicting hard disk failures based on Isolation Forest is proposed. Consequently, a method is presented that can deal with the highly imbalanced datasets, as the experiment on the Backblaze benchmark dataset demonstrates.

#### [Slides](slides/SmartPred_Unsupervised_Hard_Disk_Failure_Detection_Presentation.pdf)

#### [Paper pre-print](paper/)

#### About the Speaker
Philipp just finished his Masters degree in Enterprise and IT Security at Offenburg Univesity. The presented work is part of his master thesis. He is now working as a security data analyst at Sick AG.  

### Ensembles of Networks Produced from Neural Architecture Search 
presented by Emily Herron form the University of Tennessee.
{% include talk_2.html  %}
#### Abstract
Neural architecture search (NAS) is a popular topic at the intersection of deep learning and high performance computing. NAS focuses on optimizing the architecture of neural networks along with their hyperparameters in order to produce networks with superior performance. Much of the focus has been on how to produce a single best network to solve a machine learning problem, but as NAS methods produce many networks that work very well, this affords the opportunity to ensemble these networks to produce an improved result. Additionally, the diversity of network structures produced by NAS drives a natural bias towards diversity of predictions produced by the individual networks. This results in an improved ensemble over simply creating an ensemble that contains duplicates of the best network architecture retrained to have unique weights.

#### [Slides](slides/NAS.pdf)

#### [Paper pre-print](paper/)

#### About the Speaker
Emily Herron is a third year PhD Student in the Bredesen Center Data Science and Engineering Program at the University of Tennessee. This is a joint program between the University of Tennessee and Oak Ridge National Laboratory. She holds a B.S. in Computational Science from Mercer University. Her research utilizes high performance computing, with a focus on evolutionary algorithms and neural architecture search.

###  GOPHER, an HPC framework for large scale graph exploration and inference
by Xavier Teruel form BSC
{% include talk_3.html  %}
#### Abstract
Biological ontologies, such as the Human Phenotype Ontology (HPO) and the Gene Ontology (GO), are extensively used in biomedical research to investigate the complex relationship that exists between the phenome and the genome. The interpretation of the encoded information requires methods that efficiently interoperate between multiple ontologies providing molecular details of disease-related features. To this aim, we present GenOtype PHenotype ExplOrer (GOPHER), a framework to infer associations between HPO and GO terms harnessing machine learning and large-scale parallelism and scalability in High-Performance Computing. The method enables to map genotypic features to phenotypic features thus providing a valid tool for bridging functional and pathological annotations. GOPHER can improve the interpretation of molecular processes involved in pathological conditions, displaying a vast range of applications in biomedicine.


#### [Slides](slides/MLHPCS20_GopherSlides.pdf)

#### [Paper pre-print](paper/)

#### About the Speaker
Xavier Teruel received the Computer Engineering degree and the Master on Computer Architecture, Network and Systems at Technical University of Catalonia (UPC) in 2006 and 2008, respectively.
Since 2006 Xavier is working as a researcher within the group of Parallel Programming Models in the Computer Science department at the Barcelona Supercomputing Center (BSC). He has participated in several research projects in the framework of the European Union as well as in the OpenMP Language Committee since version 3.0.
He spent three years, from 2007 to 2009, collaborating with the IBM XL compiler team in the IBM Markham Laboratory in Toronto, Canada. From 2010 to 2012 he also worked as a part-time lecturer in the Computer Architecture Department at the UPC.
His research interests include the areas of operating systems, programming languages, compilers, runtime systems and applications for high-performance computing and multiprocessor systems. He has published several papers in international workshops, conferences and journals in these topics.


## Contact
info@mlhpcs.org

## Organizing Committee
* Juan J. Durillo (LRZ, Munich)
* Dennis Hoppe (HLRS, Stuttgart)
* Jenia Jitsev (JSC, Jülich)
* Janis Keuper (IMLA / Fraunhofer ITWM)
* Sunna Torge (ZIH, Dresden)




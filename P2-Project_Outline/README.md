# Project Outline
For this assignment, you will submit a high-level outline of your project. This can, and likely will, change over time. In particular, your mentor will provide direction and feedback to help sharpen your ideas. So don't worry if you feel unsure about some aspects of the outline or if you have to change some things later.

## Assignment Description
[Project Outline Assignment](https://education.launchcode.org/liftoff/modules/assignments/project-outline)

## Submission Instructions

### Overview
Enzymes are proteins that act as the catalysts of all biological systems. Chemical models of their behavior is crucial for the development of many fields within biomedicine and bioengineering. Specifically, quantum mechanical (QM) models provide the most accurate and precise results known in chemistry and physics. However, QM methods are computationally expensive and requires immense amounts of readily available computer memory, processor speed and storage space. Since enzymes can be composed of hundreds of thousands atoms in total, scientists can only use a QM model on a few of the amino acids (AKA residues) within the protein. One of the biggest problems in the development of QM active site modeling is selecting a specific method. There are a large list of possible methods that can be used for this process. However, this is has led to a dilemma within the field of enzyme modelling: the diversity of models has led to issues with irreproducibility and disagreement in the scientific community. Unfortunately, the most common mean of communication in scientific is through peer-reviewed publication. Although peer-reviewed journals are the standard by which scientists have curated and shared discoveries, it is very inefficient and unreliable when it comes to sharing data and comparing computational methods.

The aim of this app is to make it so scientists can easily share, discuss and show their methods, systems and results. The site will provide a list of possible catalytic site  methods that the user can use on their protein of interest. Furthermore, they will be able to discuss their results and upload potential models. Hopefully with these two key components, a foundation can be laid in which scientist can develop and agree upon better catalytic selection methods that are both reproducible and accurate.

### Features
User Login: Users are required to sign up and login in order to use app.
Build Models: Users can build models by selecting method and uploading a protein database file (PDB) to the site. The user can submit the model as job and see the results.
Search: User can search previous or currently running jobs on server. So they can easily keep track of what they have done.
Forum: Users can add to or start threads of their own and show their data to some capacity.
About/Contact: Allow users to email the administrators of the app to help the app for future development

### Technologies
- Python
- Django
- Pandas
- Scikit-learn/Tensorflow eventually ...
- Something to replace sqlite files since they aren't appropriate for servers

### What I'll Have to Learn
- Work with Django more proficiently.
- Launch on real server using Django
- Deploy larger scale database that can handle PDB-like data structures

### Project Tracker
https://trello.com/b/CONDerw6/liftoff-project
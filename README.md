# "Can Network Analysis Techniques help to Predict Design Dependencies? An Initial Study"

Repository corresponding to the ICSA paper "Can Network Analysis Techniques help to Predict Design Dependencies? An Initial Study". 
Available at https://arxiv.org/abs/1808.02776

The degree of dependencies among the modules of a software system is a key attribute to characterize its design structure and its ability to evolve over time. Several design problems are often correlated with undesired dependencies among modules. Being able to anticipate those problems is important for developers, so they can plan early for maintenance and refactoring efforts. However, existing tools are limited to detecting undesired dependencies once they appeared in the system. In this work, we investigate whether module dependencies can be predicted (before they actually appear). Since the module structure can be regarded as a network, i.e, a dependency graph, we leverage on network features to analyze the dynamics of such a structure. In particular, we apply link prediction techniques for this task. We conducted an evaluation on two Java projects across several versions, using link prediction and machine learning techniques, and assessed their performance for identifying new dependencies from a project version to the next one. The results, although preliminary, show that the link prediction approach is feasible for package dependencies. Also, this work opens opportunities for further development of software-specific strategies for dependency prediction.

This repository presents the reproducibility kit corresponding to the two software systems used for performing the experimental evaluation: SubscriberDB and Apache Derby.

For each system, it is available:
* Source code
* .jar file
* Dependency graphs in format *.odem
* Process Content-based similarities

.odem files were created using [CDA (Class Dependency Analyzer)](http://www.dependency-analyzer.org/)

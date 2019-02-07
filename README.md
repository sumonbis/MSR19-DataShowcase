# MSR19-DataShowcase
The popularity of Python programming language has surged in recent years due to its increasing usage in Data Science. The availability of Python repositories in Github presents an opportunity for mining software repository research, e.g., suggesting the best practices in developing Data Science applications, identifying bug-patterns, recommending code enhancements etc. To enable this research, we have created a new dataset that includes 1558 mature Github projects that are developing Python software for Data Science tasks. By analyzing the metadata and code, we have included the projects in our dataset which use a diverse set of machine learning libraries and managed by a variety of users and organizations. The dataset is made publicly available through Boa (http://boa.cs.iastate.edu/) infrastructure both as a collection of raw projects as well as in a processed form that could be used for performing large scale analysis using Boa language. We also present an initial application to demonstrate the potential of the dataset that could be leveraged by the community.

The data generation compiled code is available here: https://github.com/sumonbis/MSR19-DataShowcase/releases/tag/v1.1

For running the above data generation program follow instruction: 

The open source code for Github repository collection, data generation and Boa compiler are available in the pydatagen branch of Boa compiler: https://github.com/boalang/compiler/tree/pydatagen

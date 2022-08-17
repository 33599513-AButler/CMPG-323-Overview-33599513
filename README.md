# CMPG-323-Production-33599513

University work for CMPG 323

Branching strategy:

The Branching strategy used in the projects will consist of
three seperate branches. A main branch that contains the most
up to date working code, a development branch that will
contain code that will be evaluated in terms of performance
and its ability to functioning properly before being pushed
to main and the features and fixes branch for the addition 
of normative enhancements and fixes to poblems encountered
in the development branch testing environment.

<img src="33599513 branching strategy.jpg" width="600"/>

The desire to not use a hotfix branch or overly complicate
and create new branches simply for fixing single issues
serves to simplify version control.

Credential management:

In order to manage credentials, I will be using config files where
available or alternatively hashing methods and the gitignore
command to prevent committing sensitive information. 
For web application this may not be directly managed on the client
side and as such I will ensure to use current best practice to 
secure the provided credentials and prevent either hashing
funtions or other such information from being uploaded on the
repository. As the current metrics of what functionality is
required and how is not currently well understood, the strategy
of securing such information will be revisited on an individual
basis.

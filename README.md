# CMPG-323-Production-33599513

University work for CMPG 323

Method for handling projects:

Each project will have its owbn repository associated with it.
The standard layout will consist of a Main branch, a development
branch, and a features and fixes branch. HTe Main will host the 
presumably fully functional code, the development branch will
host the last good known working development and the features
and fixes branch will host the current iterable project which
is the working directory for implementing new features and
solving discovered bugs from the development branch.

The main branch will not be developed on, the development,
and features and fixes branches will be worked on locally
while development is ongoing. In this sense the Main is to
explicitly publish passing and finalised code. The fixes
and features branch will host the majority of development
tasks and will be backed up routinely with apparently 
working code being pushed to the development branch where
attempt to break it will be made.

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
For web applications this may not be directly managed on the client
side and as such I will ensure to use current best practice to 
secure the provided credentials and prevent either hashing
funtions or other such information from being uploaded on the
repository. As the current metrics of what functionality is
required and how is not currently well understood personally, 
the strategy of securing such information will be revisited
on an individual project basis.

Completion of Project 1, project submitted.
Completed Github training and read through provided documentation.

Completion of Project 2, project submitted.
Completed Azure training and read through provided documentation.

Project 3 submitted.
Read through available resources, difficulty attempting to integrate full-fledged abstractions and classes.

Project 4 submitted.
Completed Ui Path training.

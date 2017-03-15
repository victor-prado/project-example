Commands
---------------

First of all we need to have installed the virtualenv.

Inside the project directory.
To create a new virtual enviroment
    
    $ virtualenv <directory> 

To get in a virtual enviroment

	$ source <diretory>/bin/activate
	
To install a new dependence with pip

	$ pip install <dependence>
	
To see all the dependences intalled

	$ pip freeze
	
We can make a requirements.txt file by doing this

	$ pip freeze > requirements.txt
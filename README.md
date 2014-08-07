django1.6-bootstrap
===================

Boilerplate for a new django project

This will help you to start a new django project with Twitter' Bootstrap and Postgresql as DBM.

Before you start, you'll need to install de minimun requirements:

- virtualenv 
- postgresql (if in Mac Os X, install via brew)
- python (2.7.x)
- bower

**Getting Started**

Once you have the minimum requirements, create a new virtualenv for your project. Eg.:


        $> virtualenv boilerplate

Clone this repository:
        
        $> git clone https://github.com/vellonce/django1.6-bootstrap.git
    
Activate your newly created virtual env

        $> source <path to venv>/bin/activate/

cd into the cloned repo and run:
    
        pip install -r requirements.txt
    
Edit your settings.py and local settings to match your preferred templates/staticfiles/mediafiles dirs, and to change other essential info, like the database connection settings, and project name.

cd into your STATIC\_FILES\_ROOT folder and run:
      
      $> bower install bootstrap
      
And you are done! Happy coding!

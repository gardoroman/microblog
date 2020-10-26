## Required packages  
pip install flask  
pip install python-dotenv  
pip install flask-wtf  
pip install flask-sqlalchemy  
pip install flask-migrate  
pip install flask-login

## Errors Encountered
error: _Instance of 'SQLAlchemy has no 'Column' member(no-member)_  
solution: pip install pylint-flask (Helps with linting errors.) and update **.vscode** settings   
source: https://stackoverflow.com/questions/53975234/instance-of-sqlalchemy-has-no-column-member-no-member  
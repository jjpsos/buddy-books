# buddy-books

Installation Hints:  

which python3.3  -> /usr/local/bin/python3.3  
virtualenv -p /usr/local/bin/python3.3 venv  
cd venv  
source bin/activate  
git clone https://github.com/jjpsos/buddy-books.git  
cd buddy-books   
pip install -r requirements.txt   
createdb accountant   
python manage.py makemigrations/migrate    
python manage.py createsuperuser  
python manage.py runserver 0.0.0.0:8000	

Keeping code organized with Git:

git add <file>	
git commit  -m "description"    
git push  

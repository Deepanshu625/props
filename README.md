# props

Steps to run the project
* clone the project from git to your local system using this command
  ```
  git clone https://github.com/Deepanshu625/props.git
  ```
* Open project in terminal and go to the folder /read_excel/props/ by and install the requiremenent file.
  ```
  cd read_excel/props/
  pip install -Ur requirements.txt
  ```
* Update the API key present in props/views file with your key

* Run the django app
  ```
  python manage.py runserver
  ```
* Now, start your browser and open this link  
  ```
  http://127.0.0.1:8000/props/upload/
  ```
* Choose the excel file on which you want to test the app. For refrence, a sample excel file is given in the code also.

* Click on upload and you will get an updated excel file.

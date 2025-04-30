#

<p align="center">
  <h1 align="center">
    Django Project Mysite
  </h1>
  <p align="center">Django Project</p>
</p>

## Demo
![Screenshot 2025-04-30 211456](https://github.com/user-attachments/assets/fd525be0-bb71-4838-a21d-8c20fd8e4e2f)
<hr>

![Screenshot 2025-04-30 211550](https://github.com/user-attachments/assets/e1bdd7d0-9841-49de-9926-991d83ed48de)

<hr>
![Screenshot 2025-04-30 211615](https://github.com/user-attachments/assets/f77abeb7-3867-4aba-9561-54c050f05b51)

![Screenshot 2025-04-30 211604](https://github.com/user-attachments/assets/eaf8a023-d544-491f-8187-d27575f9698d)

<hr>


## Download & Setup Instructions :

After downloading the project, make sure to create a virtual enviroment and  install [project's requirements.](https://github.com/mohammadmatin2000/mysite.git)

Clone the project. This will download the GitHub respository files onto your local machine.

```Shell
https://github.com/mohammadmatin2000/mysite.git
```
installing virtual enviroment and activating:
```Shell
pip install virtualenv
```
Windows setup:
```Shell
#creating the enviroment
python -m venv venv

#activating the enviroment
venv\Scripts\activate

#deactivating enviroment
deactivate
```
Linux and Mac setup:
```Shell
#creating the enviroment
python -m venv venv

#activating the enviroment
source venv/bin/activate

#deactivating enviroment
deactivate
```

then installing the requirements:

```Shell
pip install -r requirements.txt
```
### Running the Project
in order to run the project you need to use either ways below

default and development settings
```Shell
python manage.py runserver 
#or
python manage.py runserver 0.0.0.0:8000 --settings=mysite.setting.dev
```
production settings
```Shell
python manage.py runserver 0.0.0.0:8000 --settings=mysite.setting.prod
```
<strong>Note:</strong> if you want to change the settings permanently to prod you can modify the settings in enviroment varibale inside the manage.py and need to use dokcer or install the mysql directly on your machine
### Project Model Schema :
this is the model schema have been used in this project:
![drawSQL-export-2021-08-23_23_26](https://user-images.githubusercontent.com/29748439/130503854-cefc63a6-1466-4164-825a-9f313d521059.png)


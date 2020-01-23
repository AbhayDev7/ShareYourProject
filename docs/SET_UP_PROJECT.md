To set up the project on your system, you can follow the steps mentioned below:
- Fork the repository to your GitHub account.
- Clone your fork to your system and ```cd``` into the ```share-your-project``` folder.
```
$ git clone https://github.com/<your-username>/share-your-project.git
$ cd shareYourProject
```
After following the above steps, you should be inside the folder where ```manage.py``` is present.
- Set up the remote to the main repository.
```
$ git remote add upstream https://github.com/091karan/share-your-project.git
```

- Assuming, you already have ```Python3``` and ```pip3`` installed on your system, we will now set up the virtual environment. To set up the virtual environment, follow the steps below:
    - Install virtual environment using pip3.
    ```
    $ pip3 install virtualenv
    ```
    - Make sure you are in the directory where ```manage.py``` is present. Create a virtual environment for your project.
    ```
    $ virtualenv venv
    ```
    - Now, activate the virtual environment.
    ```
    $ source venv/bin/activate
    ```
    or (for windows)
    ```
    $ venv\Scripts\activate.bat
    ```
    - Finally, use the following command to install the requirements for the project (specified in the requirements.txt file):
    ```
    $ pip3 install -r requirements.txt
    ```
    To list all the installed pip packages use the command below:
    ```
    $ pip3 list
    ```
    - Now, you can run the project using the following command:
    ```
    $ python manage.py runserver
    ```
Congratulations! You have successfully set up the project on your system. 😃

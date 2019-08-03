# FSND_4.4_Iterative-Development
This is learning by coding for Udacity Full Stack Web Development Nanodegree - 4. Servers, Authorization, and CRUD - 4. Iterative Development. This project will sum up all the learning from 4.1~4.3 courses using Flask.

## How to run
You need Python(ver.3), Linux-based virtual machine environment(Vagrant and VirtualBox).
  1. To make the virtual machine(VM) online, use the commands "vagrant up". Then log on it with "vagrant ssh". </br>
    To download Vagrant : https://www.vagrantup.com/downloads.html</br>
    To download VirtualBox : https://www.virtualbox.org/wiki/Downloads
  2. To install SQL Alchemy, please visit this website : https://www.sqlalchemy.org/
  3. Please make a shared directory on vagrant environment. (Ref. https://www.howtogeek.com/189974/how-to-share-your-computers-files-with-a-virtual-machine/)
  4. Please download from the github. Addtionally, following files are needed.</br>
    "lotsofmenus.py" : https://github.com/lobrown/Full-Stack-Foundations/blob/master/Lesson_1/lotsofmenus.py
  5. Under the VM environment, locate the directory which has all the files and folders we downloaded. Use the command "python database_setup.py" to create database, then run "python lotsofmenus.py" to populate the database. After the commands, "restaurantmenu.db" file will be created.
  6. Please run the code with "python finalproject.py". And to stop the server, please enter "exit" or press Ctrl+C. Command for turning off the VM is "vagrant halt".
  7. Open the browser and type the address: http://localhost:5000/restaurants.


## Program's Design
This app will show you the list of restaurant from data. Users can check menu items for each restaurants. Plus, users can create, edit and delete either restaurants and menu items. Each of the function will be assigned by URLs. You can also extract JSON format of the Restaurant and MenuItem data.

# CMPG323 OVERVIEW <32134452>
The overview of Agile and Scrum Project (Project 1), the main repository

The branching that used is the Gitflow branching, which uses two main branches to record the projects's history, throughout the course of the semester. The main branch is an intergration branch for features (uses features branches multiple primary branches).

in each project there has to be a git.ignore file, because a git.ignore file will help with ignoring files and lines that the owner does not want in the repository (could be files of a certain type, eg files ending in .py, which are python files). Git.ignore files are used to ignore blank lines in the files inside the repository, they are also there to ignore patterns, like line 1 above has # and it will be ignored when reading the README file. They only work inside of their directory.  

The storage of credentials 
if the credentials and sensitive information is saved in the cache, the cache only keeps the credentials in the memory for a certain amount of time . The credentials and sensitive information are not stored on the disk of the device, and they are removed/ deleted from the cache after about 10 - 15 minutes.
if the credentials and sensitive information are in store mode then they are saved on the disk and they will not be removed / deleted until the owner changes the credentials themselves on the GitHost.


# CMPG323-PROJECT4-32134452
TEST AND AUTOMATION 
![HOME](https://user-images.githubusercontent.com/61378355/198089073-ca8e71d6-9f7d-473a-a50b-ae599b24fdd7.PNG)
This is the home page of the webapp, the arrows indicate: Home button - will return you to the home page, where you can refresh the webapp
Register button: if the user is a new user, they are required to register their email and their password. They will be redirected to the following page

![REGISTER](https://user-images.githubusercontent.com/61378355/198118518-f73fd176-03d7-4a7b-ac4f-fa653d92a909.PNG)
on this page the user will just enter their email address, as well as the password of their choice and confirm that password. After the registration page, they will be redirected to the login page.

![LOGIN](https://user-images.githubusercontent.com/61378355/198089081-b02fd7bd-9257-4a05-a73b-0fbca7b0741a.PNG)
they will then be redirected to this page, and again this page can be accessed through the home page and just click on the login button.
on this page they enter their the details that they used to register to the webapp, they also have an option to click on the remember me check box, so that the next time the webapp will be able to retrieve the stored details. If they pressed the login button unpurposely, then they can click on "Register as a new user",and they will be redirected to the previous page.
However if you click on Login button then they will be redirected to the following page, where they will choose which attribute they wish to edit, but it is wiser to start in the order that they are placed 

![HOME- DEVICES](https://user-images.githubusercontent.com/61378355/198122620-f9942519-8d3c-4561-bdfe-f19a9e4cc755.PNG)
IN THE PAGE ABOVE, THAT COMES AFTER THE LOGIN, THE USER IS REQUIRED TO CLICK ON ANY OF THE BUTTTONS TO ENTER THE DETAILS, THEY CAN CHOOSE ZONES, CATEGORIES, DEVICES.
IF ZONES IS CLICKED, THEN THE USER WILL BE REDIRECTED TO THE FOLLOWING:

![ZONES EXCEL](https://user-images.githubusercontent.com/61378355/198089799-d09aaaad-2e8a-461e-a8bd-e53e8662691c.png)
this is where the Uipath is going to get the details of the zone, and type/ transfer them to the webapp database.

![ZONES CREATE](https://user-images.githubusercontent.com/61378355/198089087-acb43cb7-0343-4882-b7c2-1bdd568e7a81.PNG)
 On this page the user can click on the + button to add/ create a new zone, they will be redirected to a page to enter the zone.

![ZONES CREATE](https://user-images.githubusercontent.com/61378355/198113181-7b7c5118-87d7-42ac-b66b-dabc83aa9d78.png)
After typing (but because we are using automation, there will be no need for typing as the automation will do everything for the user, the automation will get information from the above excel file, the zone name and the zone description they can click on create, to create a new zone. After clicking the create button they will be redirected to the following page which shows the deatils of the zone that has just been entered.

![ZONES DETAILS](https://user-images.githubusercontent.com/61378355/198116182-a525f769-e303-4a04-ac75-9c73c802a0eb.PNG)
On this page, the details that have just been entered/ loaded to the database of the webapp will be displayed. Then they will be given the options to: edit what they have just entered, to delete, or to go back to the list.
![ZONES LIST](https://user-images.githubusercontent.com/61378355/198113339-23b86a69-55fa-4d09-b296-2776c103951c.png)
will display all of the saved zones on the database.

![CATEGORY EXCEL](https://user-images.githubusercontent.com/61378355/198115984-707494ca-47d4-45c6-a18d-e1263355ef3a.png)
this is where the Uipath is going to get the details of the Categories, and type/ transfer them to the webapp database.

![CATEGORIES](https://user-images.githubusercontent.com/61378355/198113460-b9ab5c58-318d-4622-84e8-6e85f22acb33.PNG)
 On this page the user can click on the + button to add/ create a new Category, they will be redirected to a page to enter the Category.

![CATEGORIES CREATE](https://user-images.githubusercontent.com/61378355/198115748-8717be33-8884-4d8f-bce0-29fc7969271b.png)
On this page the user can click on the + button to add/ create a new category, after typing (but because we are using automation, there will be no need for typing as the automation will do everything for the user, the automation will get information from the above excel file, the Category name and the Category description they can click on create, to create a new Category. After clicking the create button they will be redirected to the following page which shows the deatils of the zone that has just been entered.

![CATEGORIES DETAILS](https://user-images.githubusercontent.com/61378355/198116088-e6a4dfb2-4752-405d-a2d3-07289cf9decf.PNG)
On this page, the details that have just been entered/ loaded to the database of the webapp will be displayed. Then they will be given the options to: edit what they have just entered, to delete, or to go back to the list.

![CATEGORIES LIST](https://user-images.githubusercontent.com/61378355/198115914-08edde5e-651c-42f2-aa32-1e17dd7cd2c2.png)
will display all of the saved categories on the database.

![DEVICES EXCEL](https://user-images.githubusercontent.com/61378355/198116573-439fe675-78ff-4f80-9f7c-f27482d59c21.png)
this is where the Uipath is going to get the details of the Devices, and type/ transfer them to the webapp database.

![DEVICES](https://user-images.githubusercontent.com/61378355/198116470-0264c02e-aac1-4c3c-b588-6fc8794e970b.PNG)
 On this page the user can click on the + button to add/ create a new Device, they will be redirected to a page to enter the Device.

![DEVICES CREATE](https://user-images.githubusercontent.com/61378355/198116540-230e3c68-f4ad-4973-b9ad-5f0983a01337.png)
On this page the user can click on the + button to add/ create a new devices, after typing (but because we are using automation, there will be no need for typing as the automation will do everything for the user, the automation will get information from the above excel file, the Device name, Category name, Zone name, Status, and the IsActive status they can click on create, to create a new Device. After clicking the create button they will be redirected to the following page which shows the deatils of the Device that has just been entered.

![DEVICE DETAILS](https://user-images.githubusercontent.com/61378355/198116655-c5ea2be4-030d-4b7a-9036-fa3537bd0f8c.png)
On this page, the details that have just been entered/ loaded to the database of the webapp will be displayed. Then they will be given the options to: edit what they have just entered, to delete, or to go back to the list.

BUT SINCE WE WILL BE USING AUTOMATION, ALL OF THE ABOVE WILL BE DONE AUTOMATICALLY 

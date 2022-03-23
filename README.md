# Android-Bottom-Nav-Data-Binding-Template
A template Android Studio project with a bottom navigation and databinding already setup.

The template contains 3 fragments which are connected by a bottom navigation bar.
 ![Screens](https://user-images.githubusercontent.com/34044928/159600010-840b7fd5-763d-4468-be35-4c1f2f2f20ab.png)

The main activity hosts the fragments.
![Host Fragment](https://user-images.githubusercontent.com/34044928/159600311-3263f04b-0bc1-4ab2-94b3-5c7068e98f6d.png)

The bottom navigation bar can be changed by editing the menu.xml
![Menu](https://user-images.githubusercontent.com/34044928/159600582-5658ffa9-0aa6-453c-9a19-7e3ebfd5530d.png)


## Remember
If you are using this template, remember to change the package name and the application ID.
 
### Changing Package Name 
To change the package name, right click on the package folder and select Refactor > Rename
 
![Rename Package](https://user-images.githubusercontent.com/34044928/159603298-ba97e5aa-bc7e-4496-bfb4-b83a9537e564.png)
 
Make sure to select Rename Package
 
Provide a new name for your package and press Refactor
  
![Package Name](https://user-images.githubusercontent.com/34044928/159603431-372bb9f0-1a72-47e2-aa59-1a82907432ce.png)
  
Select Do Refactor in the lower left corner
 
![Do Refactor](https://user-images.githubusercontent.com/34044928/159603555-63f98649-e2f3-4064-8a70-0b20a60c4e9e.png)

### Changing application ID
To change the application ID, open your module build.gradle file
  
Change your applicationID to match your package name under defaultConfig

![ApplicationID](https://user-images.githubusercontent.com/34044928/159603816-7a35c981-c3b5-4fbc-a3b2-93878750dfbe.png)
 
Finally, select Build > Clean Project then Build > Rebuild Project
 
## Git
If you are planning in using this project with Github, remember to set your new origin, otherwise you will be trying to push to this repo.
  
Git > Manage Remotes



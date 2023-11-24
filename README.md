# Roll-It-App

Roll it Provides an interaction in a group of people through the simple game of a dice, in which you have a way to earn points oh to accept a while, is an occasional game for meetings between friends for fun.

Contributions are welcome!

To start off, this repo (along with others in the family). As such, after cloning dependencies _should_ be installed via `yarn`, not via npm, the latter will result in broken dependencies.

To get started -

1. Opening an Ubuntu temrinal
  - Create the followind directory Roll-It-App.
  - Create the virtual environment with the following command:
  ```
  python3 -m venv .venv
  ```
2. Clone the repository frm GitHub with the following command
```
git clone
```
3. Run of next command:
  -Activate the virtual environment with the following commnad:
   ```
    source .venv/bin/activate
   ```
  - Install django in the virtual environment with the following command:
    ```
    pip install django
    ```
  - Start the project with the following command:
    ```
    django-admin startproject mysite
    ``` 
  - Copy the directory's documents inside Roll-It-App with the following command:
    ```
    cp -r mysite/ Roll-It-App/
    ```
  - Move the settled configurations inside Roll-It-App by getting in the file and moving the with the next 2 commands
    ```
    cd Roll-It-App
    cp -r mysite/* 
    ```
  - Verify that all the documents and configuration have been copied to the directory with the command
    ```
    ls -a ../mysite
    ```
    4.	Now press Ctrl + C to cancel the process of verification.
    5.	Finally just commit the changes to the online repository by using the 3 base commands to commit them:
    ```
    git add
    git commit -m "initial commit"
    git push
    ```
    

## Required Dependencies
* **Undetected chrome driver** - We are using undetected chromedriver to prevent browsers from being detected by bots.
* To prevent our browser being detected we have two possible approaches-
    * Make a different user agent each time.
    * Use an undetected chrome driver so that bot cannot identify the user agent every time.
* We have followed the second approach.
* **Pickle library** - We are using this library for storing website cookies.
* **Time library** - For giving sleep time so that our browser waits, whenever required.
* **Datetime library** - For datetime manipulations.
* **Pandas** - Data manipulation.
* **Boto3** - To establish connection between aws and python.
* **Apscheduler** - For setting up Scheduler
* **os and glob2** -For handling files of local directory
* **yaml module**-for handling .yml file data.
* **re module** 
 

## Credentials 
* All credentials have been stored in .yml files. 
* We are loading all credentials by using .yml files.
* If number user is being increased then add their respective credentials in .yml file.

## Saving cookies
* We are saving every user cookies in form of pickle file and reuse it for multiple login.
* Each time if new user logged in try to save their cookies in pickle file for this we need to run command **python saving_cookies** and then we reuse it for multiple logins.

### Note: 
* The .yml file is excluded from Repo, and will be provided separately.
* Use updated chrome version browser as undetected browser works with latest version.

   
# Robot-Framework-Intro

---

## Requiremnt
1. python/pip
````ps1
# checkUp
pip --version

python --version
````

2. git
````ps1
# checkUp
git --version
````

3. robot framework

````ps1
# --proxy http://<hostname:port> : optional
pip install robotframework

# checkUp
pip show robotframework 
````

4. libs
````ps1
# appium for mobile
pip install robotframework-appiumlibrary

# pabot
pip install robotframework-pabot

# selenium for web
pip install robotframework-seleniumlibrary
````

5. edge webDriver
* [home](https://developer.microsoft.com/en-us/microsoft-edge/tools/webdriver?form=MA13LH)
* [ddl-142](https://msedgedriver.microsoft.com/142.0.3595.94/edgedriver_win64.zip)
* update path :
````ps1
$env:path += ";c:\users\paul\edgedriver"

# checkUp
get-command msedgedriver |
fl commandType,name,version,source
````

---

## Test
````ps1
robot login.robot
````

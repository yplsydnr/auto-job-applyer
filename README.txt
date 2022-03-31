# auto-job-applyer
find and apply to all "easy-apply" jobs on Linkedin (please note, this is not working yet)


#install Selenium

pip install selenium

#create webdriver.exe file

from selenium import webdriver
from selenium.webdriver.chrome.service import Service
from webdriver_manager.chrome import ChromeDriverManager
driver = webdriver.Chrome(service=Service(ChromeDriverManager().install()))

#now there should be a webdriver.exe file which will be used in the overall function

path = "C:\Users\Randy\.wdm\drivers\chromedriver\win32\99.0.4844.51\chromedriver.exe"
driver = webdriver.Chrome(path)

#note the username and password are saved on a file outside of the directory
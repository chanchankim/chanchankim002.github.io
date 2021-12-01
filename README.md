# chankim.github.io

#hi.py

from selenium import webdriver

from helium import *

import time

import os

for i in range(1,2):

	driver = start_chrome()
	time.sleep(2)
	driver.execute_script("alert('Hi!你好!');")
	time.sleep(3)
	kill_browser()

	os.system("pause")


#from helium import *

#start_chrome('google.com')

#write('helium selenium github')

#press(ENTER)

#click('mherrmann/helium')

#go_to('github.com/login')

#write('username', into='Username')

#write('password', into='Password')

#click('Sign in')

#kill_browser()

















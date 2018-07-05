# LoginBot

## Code:

```

from selenium import webdriver


driver = webdriver.Chrome()
driver.get("url")
userName = driver.find_element_by_id('usernameId')
userName.send_keys("username")
password = driver.find_element_by_id(passworId')
password.send_keys("password")
password.submit()

```

## Links:

1. https://www.python.org/downloads/
2. http://chromedriver.chromium.org/downloads
3. http://selenium-python.readthedocs.io/api.html

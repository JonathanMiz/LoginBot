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

1. [Python download] {https://www.python.org/downloads/}
2. [Chrome driver download] {http://chromedriver.chromium.org/downloads}
3. [Webdriver api]{http://selenium-python.readthedocs.io/api.html}
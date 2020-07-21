# Project_web_shop-SELENIUM_IDE

Hello,

On the website "http://automationpractice.com/index.php" I performed 4 automatic tests with Selenium IDE in the Chrome browser concerning:
1) Sign up
2) Log in
3) Placing an order
4) Navigating the menu along with adding and removing items from the basket

In tests, I also used functions like:
- random numbers generator (return 'mate' + Math.floor(Math.random()*111111111111111111111) + "@gmail.com")
- store xpath count
- echo
- mouse over
- wait for element visible
- wait for element not present
- assert element present
- assert element not present
- assert text

An interesting experience was that there was an error during the next test. The defect was that after doing my first test, the site didn't log me out before starting my next test.
To prevent this defect, I used the "assert element not present" function. This feature would stop the page until the "Sign out" button disappeared. Which allowed the next test to start the test without a logged in user.

In addition, I put a test recording here (I recommend unpacking the file before watching)

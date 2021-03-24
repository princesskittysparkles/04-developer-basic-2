# 04-developer-basic-2
Continue Down the Developers Path

This file contains instructions for you to follow. You will be executing these instructions in the repo you created last time and on your linux workstation.

### Part 1

0. Create a new branch in your password generator repo called "feature-add/other-half-of-battle" and switch to that branch. 

1. Create a file called test_password.py. Write at least 3 tests using pytest. All tests should be passing.( [Hint](https://github.com/lamar-frankie/03-developer-basic-1/blob/guardrails/test_password.py)... Just in case you need it 😉)

```python
pip3 install pytest
pytest -xv test_password.py
```


2. Scan your password generator with the [Bandit](https://pypi.org/project/bandit/) Python Module.


3. Lint your code with the [Black](https://pypi.org/project/black/) Python Module.


4. Scan your dependencies for problems with the [dependency check](https://pypi.org/project/dependency-check/) module.


5. Update your dependency file (requirements.txt) to reflect all the modules your app needs, including the ones we used in this exercise.


6. Build your app with the [pyinstaller module](https://pypi.org/project/pyinstaller/) and the --clean flag. 

7. Commit your chages and push to github.

8. Create a pull request to move the changes from the "feature-add/the-other-50-percent" to your "no-guardrails" branch and assign it to a fellow classmate. 

### Part 2

Answer the following

0. What is the most important and least important part of the "other half of the battle"?

1. Why do artifact repositories exist? Isn't that just an extra unecessary step?

### Part 3

0. Respond to any pull requests assigned to you by your fellow classmates and give feedback. 

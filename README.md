User Story:

1)
- As a User       
- In order to make an withdrawal      
- The ATM needs to have funds

2)
- As a User               
- In order to know if my withdrawal was successful or unsuccessful      
- I want to receive a message with my withdrawal details

3)
- As an ATM operator          
- In order for the right person to make a withdrawal            
- I want each person to have an separate account

4)
- As a ATM operator           
- In order ensure that an Acccount holder can only withdraw funds that he has    balance for           
- I want to allow a withdrawal only if there are sufficient funds in the account

5)
- As a ATM operator
- In order for our customers to withdraw funds
- I need make sure that we only allow withdrawals if there is sufficient funds available

6)
- As a Customer              
- In order to keep my funds secure             
- I want a secure Pin code & an expiry date on my card that allows only me access to my funds

7)
- As a ATM operator
- In order to allow access active customers
- I want to allow withdrawal only from active customers 

TODO

Seth:
1) Create startup files (README, gitignore, Gemfiles & rspec framework)
2) Create Github Repo
3) Add Github Repo as remote and push changes
4) Pong changes to Dash

Dash
1) Modify README file
2) Create the atm_spec file and write the first test to run in rspec (test that the ATM has funds)
3) Create a lib folder for files to test
4) Create an atm.rb file with class ATM
5) Run the first test

Seth
1) Update README.md
2) Create second test for withdraw in atm_spec
3) Create method for second test in atm
4) Push successful tests/files up to remote repo

Dash:

1) Update README.md
2) Create third test for account
3) Push test up to repo (failing, needs method)

Seth:
1) Update README.md
2) Add extra withdraw functionality
**NOTE: in order to use Date.today, must add require 'date' at top of file
3) Test new account feature, push to repo

Dash:
1) Running the rspec again. All tests pass
2) Update README
3) Refactoring the withdraw method in order to make it readable for a common eye
4) Running rspec test. Succeded!
5) Pushing the updates to github repo

Seth:
1) Update README
2) Add an insufficient funds return to withdraw method
3) Test and push to repo

Dash:
1) Update the User Story regarding ATM funds
2) Update the README  file
3) Writing additional functionalities for the atm within the withdraw method 
4) Running the rspec tests successfully 
5) Pushing everything up to the github repo

Seth:
1) Update User Story regarding PIN Code & Expiry Date
2) Update README file w/ TODO
3) Add PIN Code tests and functionality to withdraw method
4) Run rspec to make sure PIN works
5) Add & Commit Changes, push to repo

Dash:
1) Update README file
2) Modify the withdraw method by adding a correct-pin checking method
3) Creating a private method for incorrect pin input

Seth:
1) Update README  file
2) Implement expiration date functionality and tests
**NOTE: IT IS NOT 04/2017!!! (fix date in tutorial)
3) Run tests, verify working ATM
4) Push to remote repo

Dash:
1) Update User Story with active account/customer narrative
2) Add disabled account functionability
3) Run rspec tests successfully
4) Update README file

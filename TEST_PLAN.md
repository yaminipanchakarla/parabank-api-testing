# ParaBank Test Plan

## 1. What we test

-	Register and Log In
-	Accounts Overview and Open New Account
- Transfer funds and Find Transactions
- Bill payment Service and Request loan
- Update Contact info


## 2. What we don't test

-	We don't test real time transactions
-	We don't test multiple users
- We don't test hacking systems
- We are not testing the online mobile app
  
## 3. How we test

-	We will use Postman API for testing
- I will personally use the ParaBank website for the testing


## 4. Riskiest areas

- Risk High - Log in
- RisK High - Open New Account
- Risk Medium - Account Overview
- Risk High - Transfer funds
- Risk High - Bill payment service
- Risk Low - Find Transactions
- Risk Medium - Update Profile
- Risk Medium - Request Loan


## 5. Test data

- User John & password demo
- For test data I will use the account #13344
- The site is shared so balances can be reset without warning 

## 6. When we start and when we stop

- The site is up and john can be logged in 
- Every test case we planned is tested completely , and every bug is logged

## 7. Bug severity

- Minor:something looks wrong, but nothing breaks
    
- Major:a main feature doesn’t work, but money is safe.
    
- Critical:money is lost, wrong, or goes to the wrong place, or nobody can log in.


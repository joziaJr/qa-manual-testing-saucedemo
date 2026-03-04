# Login Feature Test Scenario

System: SauceDemo  
Feature: Login

## Positive Scenarios

TS-01  
User logs in with valid username and password.

TS-02  
User is redirected to inventory page after successful login.

## Negative Scenarios

TS-03  
User tries to login with incorrect password.

TS-04  
User tries to login with empty username.

TS-05  
User tries to login with empty password.

TS-06  
User tries to login with both fields empty.

## Security / Access Control

TS-07  
User who is not logged in tries to access inventory page directly.

# Shopping Cart

## Overview
Please write code delivering the acceptance criterias (AC) that follow. 

It is designed to be a straightforward coding exercise, and it should take you no more than 90 minutes.

## What we are looking for:

**Code Design:** At Equal Experts we are keen to understand how you design your code. We do not expect a command line, web or any other type of application.

**Tests:** At Equal Experts we value unit testing, your solution should have tests with sufficient test coverage. 

**Simplicity:** At Equal Experts we value simplicity as an architectural virtue. Your solutions should reflect the difficulty of the assigned task, and should not be overly complex. Layers of abstraction, patterns, or architectural features that aren’t called for should not be included.

**Self-explanatory code:** The code must speak for itself. Long comments explaining the solution is a sign of complexity. 


## The problem statment - Acceptance Criterias

Create a shopping cart, add products to it, calculate the total price and sales tax for the items contained in the cart. 


### AC 1 : Add products.

Given:
*	An empty shopping cart
*	And a product, _Dove Soap_ with a unit price of _39.99_

When:
*	The user adds 5 _Dove Soaps_ to the shopping cart
*	And then adds another 3 _Dove Soaps_ to the shopping cart

Then:
*	The shopping cart should contain 8 Dove Soaps each with a unit price of _39.99_
*	And the shopping cart's total price should equal _319.92_
* All totals should be rounded up to 2 decimal places, i.e. 0.565 should result in 0.57 but 0.5649 should result in 0.56. You can [follow this link](http://www.clivemaxfield.com/diycalculator/sp-round.shtml#A3) if you want more details.


### AC 2 : Calculate tax rate with multiple items if applicable

Given:
*	An empty shopping cart
*	And a product, _Dove Soap_ with a unit price of _39.99_
*	And another product, _Axe Deo_ with a unit price of _99.99_
* And a sales tax rate of 12.5%

When:
*	The user adds 2 _Dove Soaps_ to the shopping cart
*	And then adds 2 _Axe Deos_ to the shopping cart

Then:
*	The shopping cart should contain 2 Dove Soaps each with a unit price of _39.99_
*	And the shopping cart should contain 2 Axe Deos each with a unit price of _99.99_
* And the total sales tax amount for the shopping cart should equal _35.00_
*	And the shopping cart's total price should equal _314.96_
*	All totals should be rounded up to 2 decimal places as described in AC 1. 


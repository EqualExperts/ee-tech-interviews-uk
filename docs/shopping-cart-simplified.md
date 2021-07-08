# Shopping Cart

Please make sure you read this document in its entirety.

## Overview
Please write code delivering the requirements of the steps that follow. The requirements don't mention a command line, web or any other type of application, and we are not looking for one. Do write code that you would be happy delivering to a paying client, keeping in mind the simplicity comments below.

You should not find this test to be particularly difficult. It is designed to be a straightforward coding exercise, and it should take you no more than 90 minutes.

## What we are looking for:

**Test Coverage:** The solution should have excellent unit tests and test coverage.

**Simplicity:** We value simplicity as an architectural virtue and a development practice. Solutions should reflect the difficulty of the assigned task, and should not be overly complex. Layers of abstraction, patterns, or architectural features that aren’t called for should not be included.

**Self-explanatory code:** The solution you produce must speak for itself. Multiple paragraphs explaining the solution are a sign that it isn’t straightforward enough to understand purely by reading code, and are not appropriate.


## The problem

As you work through the acceptance criterias, you'll create code to allow a user to add products to a shopping cart,  calculate the total price and then the sales tax for the items contained in the cart. As mentioned previously, we are not looking for a command line or a web application, so please just use your tests to drive the code (e.g. class libraries).

***Please Note***: All totals should be rounded up to 2 decimal places, i.e. 0.565 should result in 0.57 but 0.5649 should result in 0.56.  This is baisically the same rounding you learned at school, but you can [follow this link](http://www.clivemaxfield.com/diycalculator/sp-round.shtml#A3) if you really want more details.

### Add products to the shopping cart.

Given:
*	An empty shopping cart
*	And a product, _Dove Soap_ with a unit price of _39.99_

When:
*	The user adds 5 _Dove Soaps_ to the shopping cart
*	And then adds another 3 _Dove Soaps_ to the shopping cart

Then:
*	The shopping cart should contain 8 Dove Soaps each with a unit price of _39.99_
*	And the shopping cart's total price should equal _319.92_


### Calculate the tax rate of the shopping cart with multiple items if applicable

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
*   And the total sales tax amount for the shopping cart should equal _35.00_
*	And the shopping cart's total price should equal _314.96_

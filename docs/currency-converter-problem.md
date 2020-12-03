# Currency Converter

Please make sure you read this document in its entirety.

## Overview

This is a simple coding exercise to implement functionality as a unit that could be incorporated into another project.

Please write code delivering the requirements that follow.  Write code that you would be happy delivering to a paying client, keeping in mind the simplicity comments below.

You should not find this test to be particularly difficult. It is designed to be a straightforward coding exercise and it should take you no more than 90 minutes.  One thing we are interested in is to see which compromises you make to stay in this sort of timeframe.  It’s more important that we can see how the development would continue than for every feature to be present.

## What we are looking for:

**Test Coverage:** The solution should be developed “test-first”, and should have excellent unit tests and test coverage.

**Simplicity:** We value simplicity as an architectural virtue and a development practice. Solutions should reflect the difficulty of the assigned task, and should not be overly complex. Layers of abstraction, patterns, or architectural features that aren’t called for should not be included.

**Self-explanatory code:** The solution you produce must speak for itself. Multiple paragraphs explaining the solution are a sign that it isn’t straightforward enough to understand purely by reading code, and are not appropriate.

## Deliverable

**Include a readme:** Please include a readme file in the root of the project which states any requirements and commands needed to run the code. Assume the reviewer is unfamiliar with your choice of framework and/or build tools and maybe using a different IDE.

**This version number:** As mentioned above, please include the version number `{{site.github.build_revision}}` in a README file with your submission so we know what version of the instructions you've been given.

## The problem

## Context
Given the following Exchange rates from USD

| Currency code | Exchange rate |
| ------------- | ------------- |
| EUR | 0.87815 |
| GBP | 0.78569 |
| CAD | 1.31715 |
| INR | 69.3492 |
| MXN | 19.2316 |
| AUD | 1.43534 |
| CNY | 6.88191 |
| MYR | 4.13785 |
| COP | 3203.18 |

## Steps
* Implement an End Point which can return the exchange rate from Euro to Dollars
* Extend your solution to convert US dollars to British Pounds
* Extend your solution to convert Euro to British Pounds
* Extend your solution to add 13.12 Euro to 99 British Pounds and return 185.64 CAD

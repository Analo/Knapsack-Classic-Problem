# Knapsack Classic Problem


In this exercise, let's try to solve a classic problem. Although, I do not condone this behaviour, I really would like to get an answer to this quesion.
Some backstory, Bob is a thief. After months of careful planning, he finally manages to crack the security systems of a high-class bank...errr, apartment, I meant apartment.
In front of him are many items, each with a value (v) and weight (w). Bob, of course, wants to maximize the total value he can get; he would gladly take all of the items if he could. However, to his horror, he realizes that the knapsack he carries with him can only hold so much weight (W).
Given a knapsack with a specific carrying capacity (W), help Bob determine the maximum value he can get
from the items in the house. Note that Bob can take only one of each item.
All values given will be strictly positive. Items will be represented as a list of pairs, wi and vi, where the first element wi is the weight of the i th item and vi is the value for that item.
For example:

Items: [ { "weight": 5, "value": 10 }, { "weight": 4, "value": 40 }, { "weight": 6, "value": 30 }, { "weight": 4, "value": 50 } ]
Knapsack Limit: 10

For the above, the first item has weight 5 and value 10, the second item has weight 4 and value 40, and so on.
In this example, Bob should take the second and fourth item to maximize his value, which, in this case, is 90. He cannot get more than 90 as his knapsack has a weight limit of 10.
Help us help Bob solve this classic problem and maybe get away with a bountiful loot(again, we don't condone this, but we are really curious).

                                                 <<< END OF QUESTION >>>
------------------------------------------------------------------------------------------------------------------------------------

## Solution

This problem was solved using Dynamic Programming. 

### Setting Up the Environment

Step1: Install python on your machine depending on the Operating System you are using. https://www.python.org/downloads/
                  --Used Version: 3.7.7 ---

Step2: Install Pytest. https://docs.pytest.org/en/latest/getting-started.html
                   --Used Version: 5.4.1 ---


Step3: Download/clone this repository on your local environment

### Running the test.

To run the tests, run `pytest knapsack_test.py


Alternatively, you can tell Python to run the pytest module:
`python -m pytest knapsack_test.py`


 



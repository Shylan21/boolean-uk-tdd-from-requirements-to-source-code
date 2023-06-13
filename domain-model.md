// Add your domain model below


Nouns & Verbs
Pay, Items, Basket, Receipt, Total, Quantity, Name, Cost, Habits

METHOD:
totalCostBasket(payAtCheckout, getReceipt, getTotal)

INPUT: 
payAtCheckout(@numbers[]), getReceipt([@number, @string]), getTotal(@number)

SCENARIOS: 
If items are added to cart => OUTPUT: @number
If items are not => OUTPUT: none

- Receipt => @item [@quantities, @name, @cost]




TestData is a SwiftData Project
There is a single Model called "Item": timestamp (Date), quantity (Int), year (Int, derived value) and viewed (Bool, set false until the new record has been opened).
Very simple, the nuance/requirement is: a button on the bottom bar to increment through the years (2025 is max and 2021 is min).
      In addition, there's a value of the sum of all quantities for the given year on the bottom bar.
CHALLENGE: I have not been able to see the value of "sumOfQuantity" updated consistently.
      On deletion of record (Item), this value is NOT updated
      On inital startup, this value is NOT calculated
WHAT AM I DOING WRONG to not update this state variable (in ContentView)?

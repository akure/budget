<!-- order: 5 -->

# Events

The budget module emits the following events.

## BeginBlocker

### Budget Collection Result for Each Budget on This Block

| Type             | Attribute Key       | Attribute Value      |
| ---------------- | ------------------- | -------------------- |
| budget_collected | name                | {budgetName}         |
| budget_collected | destination_address | {destinationAddress} |
| budget_collected | source_address      | {sourceAddress}      |
| budget_collected | rate                | {budgetRate}         |
| budget_collected | amount              | {collectedAmount}    |

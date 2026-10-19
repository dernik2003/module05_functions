# debug_log.md
# Author: Nikita Lemeshenko

## Bug 1
Error type: KeyError: 'amount'
File + line: week8_buggy.py, line 13
What the error means: Python couldn't find the amount key.
What I told the duck: The function goes through each record and adds the amount to the total.
What I tried: I added a DEBUG print to check each record.
How I fixed it: I changed 'amout' to 'amount' in the first record.

## Bug 2
Error type: TypeError
File + line: week8_buggy.py, line 18
What the error means: Python cannot compare an integer with a string.
How I fixed it: I removed the quotes around 1000 to make it an integer.

## After Fixing Both Bugs
Final output:
Total: $5150.00 across 3 records
True

Did pytest pass? Yes, all 5 Week 8 tests passed.

## AI Literacy Reflection
Did I use AI? Yes (GPT 6.0 Sol)
If yes -- exact prompt I used: Check the errors in the given code.
What AI explained: AI analyzed the code and provided errors. I found the errors myself and 
checked if I was not missing more errors from AI's response.
What I changed myself: I edited the dictionary key and changed the comparison to use an integer. Ran the tests.
Can I explain every fixed line? Yes

## What I learned
I learned that DEBUG prints can help identify problems and that Python cannot compare incompatible data types.
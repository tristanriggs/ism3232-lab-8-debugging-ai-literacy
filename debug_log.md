debug_log.md template
# debug_log.md
# Author: Tristan Riggs

## Bug 1
Error type: KeyError: 'amount
File + line: week8_buggy.py, line 12
What the error means: Python could not find the key 'amount' in a dictionary
What I told the duck: The function loops through each record and tries to add its amoount to the total.
What I tried: I used DEBUG print to check each record and see what python was actually reading.  
How I fixed it: changed amout to amount

## Bug 2
Error type: TypeError
File + line: week8_buggy.py, line 16
What the error means:Python cannot compare an number with a text using >
How I fixed it: Removed the quotation marks around 1000 on line 16.

## After Fixing Both Bugs
Final output: $5150.00 across 3 records
True
Did pytest pass? Yes

## AI Literacy Reflection
Did I use AI? Yes
If yes -- exact prompt I used: Can you help me understand my Python errors in my lab and can you explain the steps to fix them?
What AI explained: How to identify errors, why the errors were making it not work, and how to fix the rrors.
What I changed myself: Corrected the errors for each bug and added DEBUG print
Can I explain every fixed line? Yes 

## What I learned
I learned how to read Python error messages and use them to find problems in my python code. I learned that even the smallest mistakes like spelling can hinder the whole code to where it wont work. 
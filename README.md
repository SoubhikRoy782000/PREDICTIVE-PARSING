# PREDICTIVE-PARSING

Aim -

To implement Predictive Parsing.

Algorithm –

Step 1 – Initialize the required variables.
Step 2 – Get the number of coordinates and productions from the user.
Step 3 – Perform the following
for (each production A → α in G) {
for (each terminal a in FIRST(α))
add A → α to M[A, a];
if (ε is in FIRST(α))
for (each symbol b in FOLLOW(A))
add A → α to M[A, b];
Step 4 – Print the resulting stack.
Step 5 – Print if the grammar is accepted or not.

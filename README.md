# Flipstreak

This is a coin-flipping game where the probability of winning depends on two values:

- `streak`: goal number of Heads in a row.
- `lives`: number of Tails you can flip before you lose. 

For example, if `streak=2` and `lives=2`, then the sequence `Heads, Tails, Heads, Tails` is a _losing_ sequence, because it loses both lives before it finishes the streak. However, with the same parameters, the sequence `Heads, Tails, Heads, Heads` is a _winning_ sequence, because it has a streak of 2 in a row before all the lives are gone.

## How it was written

I didn't write the code for this game.

The file `prompt.txt` contains the prompt that I gave to GPT-4. The initial commit contains the generated code (first try).
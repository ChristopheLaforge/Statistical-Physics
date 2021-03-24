# Statistical-Physics

This is a piece of code to generate non-overlapping random walk (SAW for Self-avoiding walk) in a squared lattice in 2 dimensions.
The code is not finished. 
The code grows a SAW. This is not the only possible approach (the famous pivot algorithm bend an initial trivial walk instead of growing it).
The implemented solutions prevent the walk to enter into zones where it is going to be trapped, even if the zone is big enough to accomodate the expected length.
Statistically, by removing the possibility for the path to be blocked in its growth, I biais the distribution for a finite walk. It is therefore not suitable to
represent the distribution of finite self-avoiding walks.

## To-do list

Fix the issue with long-chain
Include some unit tests to my code.
Replace the StepIncrement with a max function
Transform the SAW into a picture for illustration.
Embedded into a proper class and not just a set of independent functions.

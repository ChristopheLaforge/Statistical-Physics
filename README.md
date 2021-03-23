# Statistical-Physics

This is a piece of code to generate non-overlapping random walk in a squared lattice in 2 dimensions.
The code is not finished. I realised that I did not take into account the case where the walk is going around the origin.
In that particular case, I need to take into account the number of quadrant that was covered by the walk to select the appropriate next direction.
Statistically, by removing the possibility for the path to be blocked in its growth, I biais the distribution for a finite walk. It is therefore not suitable to
represent the distribution of finite self-avoiding walks.

I also include some unit tests to my code.

Finally, it should be embedded into a proper class and not just independent functions. I will do this later on.

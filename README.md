# Twitter Likes Analysis
**Twitter Data Analysis: Generating 1 million realistic tweets (date, likes, category) using log-normal distribution, then analyzing and plotting the Data.**

The main challenge of this mini project was to figure out a way to make the distribution of different aomunts of likes received realistic. Knowing that the majority of tweets only get a few 10s of likes, it is not meaningful to generate a dataset, where all different likes received (from 0 to 5000) are equally distributed and have the same probabilites. This is a long-tail event to the right. A log-normal distribution with the mean being on the lower (left) side is the best approach.

## Theme Park Prices

Repository for blog posts on these park prices




Major commits:

- 2018-10-07: Initial commit with data from the Magic Kingdom at Walt Disney World. I got the data from this [site](http://allears.net/walt-disney-world/wdw-planning/wdw-ticket-increase-guide/) and cross referenced it [here](https://www.travelandleisure.com/trip-ideas/disney-vacations/disney-world-ticket-costs-over-time).
- 2018-10-08: Updated dates to ISO-8601 format. Added code to account for inflation. Wrote loop to calculate inflation adjustment and made plot with updated prices.
- 2018-10-10: First draft pushed, complete with `ANCOVA` and other statistical fun. 
- 2018-10-17: Cleaned up the code and caught a `join` artifact that duplicated rows in the dataset (removed it). Adjusted text at the suggestion of Len Testa (thank you) and added the original cost of a ticket adjusted for inflation.
- 2018-10-19: Incorporated Len's further comments. Added Tukey's HSD test for the CEOs `ANCOVA`. Results same as using `aov` on `lm`.

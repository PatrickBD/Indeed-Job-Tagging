# Indeed-Job-Tagging
Machine learning algorithm made to determine job tags based on job posts. This was made for the Indeed Machine Learning CodeSprint on Hacker Rank. It got 29th place, which was enoungh to win the T-shirt prize. It gives job posts tags based off their raw descriptions by looking for keywords. Just exicuting the test.rb with the test/train files in the same folder will create a tags.tsv with the answers. It has an F1-Score of 0.685. The CodeSprint was only open for a short time so this code was created in a short window. The final code runs well but not as flexabile as ideal. The only package used was "csv".

# Update
I revisted the data for this CodeSprint to see how I would do with my new NLP skills. The revist uses Bidirrectional GRU and CNN layers to get the validation F1-Score to 0.7365, which would have put it in the top ten. That is far enough to satisify my curiosity.

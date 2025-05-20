Ryan Kung

1. I would fit my automated tests wthin a Github action that runs whenever code is pushed. This way I can push changes and get feedback more frequently by offloading work
to a CI server instead of waiting for tests to finish running locally.

2. No. Since we're checking the output of a single function and not user actions, we can use unit testing instead.

3. Navigation mode captures the page on a single load whereas snapshot mode captures the page at the current state it is in.

4. We can compress the images further to save bytes, add a meta viewport tag, and add a lang attribute to the html tag.
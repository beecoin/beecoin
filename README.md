Beecoin (BEE)
==================
Beecoin (Bee) - a fork of Litecoin version with fast block time.
Like Litecoin it uses scrypt as a proof of work scheme.

- 30 second block target
- Difficulty retargets every block
1-100,000: 0-200,000 BeeCoin Reward
100,001-200,000: 0-100,000 BeeCoin Reward
200,001-300,000: 0-50,000 BeeCoin Reward
300,001-400,000: 0-20,000 BeeCoin Reward
400,001-500,000: 0-10,000 BeeCoin Reward
500,001-600,000: 0-5,000 BeeCoin Reward
600,000+:1,000 BeeCoin Reward

Super random blocks
1/1,250 chance (about twice a day): 0-500,000 BeeCoin Reward
1/2,500 chance (about once a day): 0-1000,000 BeeCoin Reward

- Total coins will be only 24 Billion
- The default ports are 33322 (connect) and 22233 (json rpc).

Development process
Developers work in their own trees, then submit pull requests when they think their feature or bug fix is ready.

The patch will be accepted if there is broad consensus that it is a good thing. Developers should expect to rework and resubmit patches if they don't match the project's coding conventions (see coding.txt) or are controversial.

The master branch is regularly built and tested, but is not guaranteed to be completely stable. Tags are regularly created to indicate new official, stable release versions of SherlockCoin.

Feature branches are created when there are major new features being worked on by several people.

From time to time a pull request will become outdated. If this occurs, and the pull is no longer automatically mergeable; a comment on the pull will be used to issue a warning of closure. The pull will be closed 15 days after the warning if action is not taken by the author. Pull requests closed in this manner will have their corresponding issue labeled 'stagnant'.

Issues with no commits will be given a similar warning, and closed after 15 days from their last activity. Issues closed in this manner will be labeled 'stale'.

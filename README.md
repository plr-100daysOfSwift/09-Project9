# 09-Project9
Project 9

In this technique project we return to [project 7](https://github.com/plr-100daysOfSwift/07-Project7/tree/day-39) to solve a critical problem using one of the most important Apple frameworks available: Grand Central Dispatch, or GCD.

    By downloading data from the internet in viewDidLoad() our app will lock up until all the data has been transferred. There are solutions to this, but to avoid complexity they won't be covered until project 9.

## Challenge

1. Modify project 1 so that loading the list of NSSL images from our bundle happens in the background. Make sure you call reloadData() on the table view once loading has finished!
2. Modify project 8 so that loading and parsing a level takes place in the background. Once you’re done, make sure you update the UI on the main thread!
3. Modify project 7 so that your filtering code takes place in the background. This filtering code was added in one of the challenges for the project, so hopefully you didn’t skip it!

* [Challenge 1](https://github.com/plr-100daysOfSwift/01-StormViewer/tree/challenge-9-1)
* [Challenge 2](https://github.com/plr-100daysOfSwift/08-Project8/tree/challenge-9-2)

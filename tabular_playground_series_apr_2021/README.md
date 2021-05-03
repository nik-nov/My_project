# Goal

Your task is to predict whether or not a passenger survived the sinking of the Synthanic (a synthetic, much larger dataset based on the actual Titanic dataset). For each PasengerId row in the test set, you must predict a 0 or 1 value for the Survived target.

Your score is the percentage of passengers you correctly predict. This is known as accuracy.

You should submit a csv file with exactly 100,000 rows plus a header row. Your submission will show an error if you have extra columns or extra rows.

The file should have exactly 2 columns:

    PassengerId (sorted in any order)
    Survived (contains your binary predictions: 1 for survived, 0 for deceased)

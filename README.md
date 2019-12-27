# Chess

I am trying to create a terminal-based chess game using a pandas DataFrame.

## Instructions

Capital letters are the white pieces and lowercase letters are the black pieces.

N/n is a Knight. K/k is a King.

Moves are entered in the following format: the piece type, the file it's at, the rank it's at, the file to move to, the rank to move to.

For example, 'Nb1c3' moves the Knight at b1 to c3.

## Challenges

### Displaying a DataFrame with Custom Objects

The DataFrame consists of chess piece objects. So when I printed the DataFrame, it showed things like this: `<__main.Rook at 0x7b1e10e63310>`.

To make it display characters, I included a `__str__()` method in each class.

### DataFrame Styling

I wanted to distinguish between pieces by making the text red. It is [possible to do so](https://pandas.python.org/pandas-docs/stable/user_guide/style.html) if the DataFrame contains numbers, but my DataFrame contains objects, which seems to be preventing it from working.

I ended up using uppercase and lowercase characters instead.

## Resources
https://stackoverflow.com/questions/24816237/ipython-notebook-clear-cell-output-in-code
https://stackoverflow.com/questions/24005221/ipython-notebook-early-exit-from-cell


# Chess

I am trying to create a terminal-based chess game using a pandas DataFrame.

## Challenges

1) Displaying a DataFrame with Custom Objects

The DataFrame consists of chess piece objects. So when I print the DataFrame, it shows things like this: `<__main.Rook at 0x7b1e10e63310>`.

To make it display a character, I included a `__str__()` method in each class.

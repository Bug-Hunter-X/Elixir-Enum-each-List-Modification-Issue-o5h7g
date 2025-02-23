# Elixir Enum.each List Modification

This example demonstrates a common error in Elixir when attempting to modify a list while iterating over it using `Enum.each`.  The code intends to remove the element `3` from the list, but due to the immutable nature of Elixir data structures, it fails to do so correctly. The solution provides a corrected approach.
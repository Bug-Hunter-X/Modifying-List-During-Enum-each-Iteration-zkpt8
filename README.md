# Modifying List During Enum.each Iteration in Elixir

This example demonstrates a common pitfall in Elixir when attempting to modify a list while iterating over it using `Enum.each`.  Directly modifying the list within the `Enum.each` callback does not update the list being iterated over.  The correct approach involves creating a new list or using a different iteration method.
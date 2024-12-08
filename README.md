# Subtle Enum.reduce Bug in Elixir

This repository demonstrates a subtle bug that can occur when using `Enum.reduce` in Elixir with conditional accumulation. The issue arises from a misunderstanding of how pattern matching works within the anonymous function passed to `Enum.reduce`. The main file `bug.exs` contains the buggy code.  The solution is presented in `bugSolution.exs`.

This bug highlights the importance of careful consideration when employing functional programming constructs, particularly pattern matching and conditional logic.  The solution showcases a more robust and idiomatic approach in Elixir.

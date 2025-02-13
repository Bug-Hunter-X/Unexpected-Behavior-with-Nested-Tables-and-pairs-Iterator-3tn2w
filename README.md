# Lua Nested Table Iteration Issue

This repository demonstrates a subtle bug related to the order of iteration in Lua's `pairs` function when dealing with nested tables. The `pairs` iterator does not guarantee a specific order, which can lead to unexpected behavior if the table is modified during iteration.

The `bug.lua` file contains code that exhibits this issue.  The `bugSolution.lua` file provides a corrected version that uses a different approach to ensure all modifications are correctly reflected.  See the detailed description in each file for a more in-depth explanation of the problem and its solution.

## Setup

No special setup is required.  You can run the Lua scripts directly using a Lua interpreter.
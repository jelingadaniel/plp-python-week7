
# Shopping List Manager

This assignment practices Python lists, loops, membership checks, and string comparisons.

## Files

- `list_warmup.py` — Demonstrates list indexing, append, remove, and len.
- `shopping_list.py` — Provides an interactive shopping list manager to add, remove, and display items.
- `list_report.py` — Prints a numbered list, counts item names longer than four characters, and finds the longest name.
- `screenshots/` — Contains screenshots showing the output of each Python program.

## Why check `in` before calling `.remove()`?

Checking whether an item exists before removing it makes the program safer because `.remove()` raises a `ValueError` if the item is not in the list. Using `in` lets the program check first and display a helpful message when the item is missing. This prevents the program from crashing during normal use.
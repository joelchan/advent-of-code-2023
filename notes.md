## day 1

part 1 was easy
part 2 was tricky - i was getting the weird edge case where the line had only 1 number, and it was at the very first character - my code wasn't picking it up bc my `range()` arg for `stop` was `-len(line)` so it stopped *before* it got to the beginning of the string. took me some print statements to catch it not getting to the beginning of the line, then easy fix.
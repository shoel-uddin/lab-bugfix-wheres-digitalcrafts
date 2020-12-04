# Where's DigitalCrafts?

This program displays the states which have cities named "Atlanta", "Houston", "Tampa".

# Bugs to fix

- [x] After lots of debugging, code stopped running. `node index.js` does nothing
    -When looking at the code and running it nothing ran, so went back to check if anything was being called.
    -Noticed the 'main' function being called was commented out.
    -Uncommented the 'main()' then it ran.
- [x] Started crashing after adding "tampa" search
    -While console.log in terminal it showed a reference error.
    -Looking at the code, in line 21, there was no 'db' to use the function from the 'db' file.  
- [x] Prints "Atlanta" locations twice (instead of Houston)
    -Going through the code for Houston, on line 15 it was looping through the Atlnta function and not Houston Function.

For each bug you fix, add documentation to this README about how you fixed it (include before/after code samples).

# For the more curious:

`db.js` includes more functions that you can try out. In `index.js`, try to `console.log()` the results of the following function calls:

- `getByAbbreviation('ak')`
- `searchByName('dakota')`
  - Why does this only return results for North Dakota (and not South Dakota)?

# README.md

Test 01

- fix(pencil): stop graphite breaking when too much pressure applied
- feat(pencil): add 'graphiteWidth' option
- perf(pencil): remove graphiteWidth option
BREAKING CHANGE: The graphiteWidth option has been removed.
The default graphite width of 10mm is always used for performance reasons.

# Feature
- chore: a # feature/a
- chore: b (Finish PR with fix and no squash) # feature/ab
- fix: abc (Finish PR without fix and no squash) #feature/abc // This has generated version but shouldnt
- fix: abcd (Finish PR without fix and clear body, no squash) #feature/abcd // This has generated version but shouldnt
- fix: abcde (Finish PR without fix but with squash) #feature/abcde // Didnt call Action but should
- fix: abcdef (Finish PR with fix and squash) #feature/abcdef // Didnt call Action but should
- fix: abcdefg (Finish PR with fix, squash and customize squash message) #feature/abcdefg // Works fine
- fix: abcdefg2 (Same, but change the default commit message for squash merging) // I'll try without npm plugin


# Test
- Without NPM plugin

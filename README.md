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
- fix: abcde (Finish PR without fix but with squash)

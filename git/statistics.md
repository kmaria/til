# Gather Some Metrics from Git

Top Commits by Author
```
git shortlog --since="{day after previous release 00:00}" --until="{day of current release 23:59}" -s -n
```

Commit Count from last Release
```
git log --since={day after previous release 00:00} --until={day of current release 23:59} {branch} | wc -l
```

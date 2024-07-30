---
permalink: /points/
comments: true
---

{% capture notice-3 %}	
One season of ~15 matches is just not enough to determine the best HCR2 team.  So I came up with a simple method that takes into account placings from previous seasons.  This should provide a more stable and accurate ranking.  Teams do change over time, so I felt that placings in previous seasons should be less relevant as time passes by (this is not applied for the calendar year total where each prior month in the year is given the same number of points as the most recent season.)
- **Most recent season**: 1st=12 points, 2nd=11 points, 3rd=10 points, … 12th = 1 point
- **Previous season**: 1st=11 points, 2nd=10 points, 3rd=9points, … 11th = 1 point
- **Two seasons ago**: 1st=10 points, 2nd=9 points, 3rd=8points, … 10th = 1 point
I.e. reducing by 1 point the value of each placement for every previous season.  Accordingly, seasons played more than a year ago will not count.
	
In table format: Points awarded according to final placement in previous seasons, where 0 was the final ranks in the last full season,  -1 is one season before, etc. 
```
Season ┃  1  2  3  4  5  6  7  8  9 10 11 12
━━━━━━━╋━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
   0   ┃ 12 11 10  9  8  7  6  5  4  3  2  1
  -1   ┃ 11 10  9  8  7  6  5  4  3  2  1
  -2   ┃ 10  9  8  7  6  5  4  3  2  1
  -3   ┃  9  8  7  6  5  4  3  2  1
  -4   ┃  8  7  6  5  4  3  2  1
  -5   ┃  7  6  5  4  3  2  1
  -6   ┃  6  5  4  3  2  1
  -7   ┃  5  4  3  2  1
  -8   ┃  4  3  2  1
  -9   ┃  3  2  1
  -10  ┃  2  1
  -11  ┃  1
```
{% endcapture %}

<div class="notice">{{ notice-3 | markdownify }}</div>


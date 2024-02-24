---
permalink: /
toc: false
toc_sticky: true
classes: wide
scores: https://cdn.discordapp.com/attachments/858851529058418765/1210579500392259624/IMG_4117.jpg?ex=65eb1304&is=65d89e04&hm=0e3da1914f55acc9fd7a2826e4a170ec31e1c4e5b29bc4ff927e4783422e0027&
tutorial: <iframe width="560" height="315" src="https://www.youtube.com/embed/HgOosV2kqp0?si=1xepszy3P4bc8dO_&amp;start=180" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>    
setup: https://cdn.discordapp.com/attachments/851566907920089128/1210805922151141416/image0.jpg?ex=65ebe5e3&is=65d970e3&hm=ca0ca233d64571dd4bc28808b6779b2ab87f8709e42f98ff5c2f03719882685d&
sidebar:
  nav: "docs"
---
![](/assets/images/Cool Text - Info 452912870276435.png)  

<!--
![](https://cdn.discordapp.com/attachments/806343355264401478/848994894865104896/cooltext385495335534000.png)  

<details  markdown="block">
  <summary>
    Table of contents
  </summary>
  {: .text-delta }
1. TOC
{:toc} 
</details> -->  



<details  markdown="block" open>
  <summary> 
   February Keys
  </summary>

![](https://cdn.discordapp.com/attachments/850232435579813938/1204175951789817926/image.webp)


</details>  

## Events  

<details  markdown="block" open>
  <summary> 
   Scores
  </summary>
![]({{ page.scores }})  
</details>  


<details  markdown="block" open>
  <summary> 
   Setups
  </summary>
![]({{ page.setup }})  

</details>

<details  markdown="block" open>
  <summary> 
   Tutorial
  </summary>

{{ page.tutorial }}
&nbsp;
</details>


<details  markdown="block" open>
  <summary> 
   Top 10 Teams Ranked after Season 33
  </summary>

![](https://cdn.discordapp.com/attachments/858336498159714324/1202857165166215228/IMG_3940.png)
**Dada Top 10 Ranking (Season 33)**  
- SÜPREME extends their supremacy despite coming 2nd to NORTH for January  
- EMPIRE leapfrog PL National into 3rd  
- Similarly NORTH overtake Project GER for 5th  
- UNIVERSE breaks into the Top 10 for 9th  
<details markdown="block" >  
  <summary>  
      Points Calculation  
  </summary>  
  
{% capture notice-3 %}	
One season of ~15 matches is just not enough to determine the best HCR2 team.  So I came up with a simple method that takes into account placings from previous seasons.  This should provide a more stable and accurate ranking.  Teams do change over time, so I felt that placings in previous seasons should be less relevant as time passes by.
- ## **Most recent season**: 1st=12 points, 2nd=11 points, 3rd=10 points, … 12th = 1 point
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

 </details>  
&nbsp;  
</details> 
[More Info… ](/more/)

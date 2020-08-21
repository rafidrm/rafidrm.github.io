---
layout: page
title: 2017 NHL Expansion Draft Optimizer 
description: The Vegas Golden Knights entered the NHL in the 2017-2018 season. On June 21, 2017, the team drafted 30 players, one from each of the 30 current NHL teams, subject to a set of drafting and protection rules that all teams must follow. We developed a web app to simulate the drafting and protection problems in real-time given a set of management preferences such as maximizing the on-ice performance or financial flexibiltiy for teams. 
---





<div class="col">
    <img class="col three center" src="{{ site.baseurl }}/assets/img/uoft-students.jpg" alt="" title="Photo taken from the Toronto Star"/>
</div>
<div class="col three caption">
    Source: The Toronto Star.  
</div>


{% comment %}
[Click here to go to the website.](http://nhlexpansiondraft.com)
{% endcomment %}


[Click here to see our coverage in The Toronto Star.](https://www.thestar.com/sports/hockey/2017/06/13/u-of-t-engineers-an-expansion-roster-for-vegas-with-the-click-of-a-button.html)


## Overview

The Vegas Golden Knights are the newest team to enter the NHL and will play in their inaugural season in 2017-2018. On June 21, 2017, the team draft 30 players, one from each of the 30 current NHL teams. Each of the existing teams is allowed to protect a certain number of players from being drafted. The NHL has stipulated that both the existing teams and Las Vegas have to follow a set of rules determining which and how many players they are allowed to protect or draft, which you can find more about here. Existing teams must submit a list of protected players by June 17, 2017. This gives Las Vegas three days to decide who to draft to their roster.



## Our Motivation

We developed a web application that leverages the power of optimization to search over the astronomical number of possible protection and selection possibilities and make roster decisions that optimize either on-ice performance, financial flexibility or a combination of the two. Our goal was to enable anybody (read George McPhee) to generate optimized rosters in a matter of seconds with just a single click. Because the optimization engine that drives this tool is so efficient, it is easy to explore many different what if scenarios and play armchair GM for your favorite team.



<div class="col">
    <img class="col three center" src="{{ site.baseurl }}/assets/img/NHL-Optimizer_500.gif" alt="" title="Optimizer"/>
</div>
<div class="col three caption">
    Using our optimization model, the site determines who the Golden Knights should pick from the NHL’s 30 teams to maximize the value of the roster, taking into consideration the draft rules. 
</div>


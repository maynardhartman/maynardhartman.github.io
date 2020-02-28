---
layout: post
title:      "Head Banger (cont.)"
date:       2020-02-28 22:59:21 +0000
permalink:  head_banger_cont
---

Part two(2) of the disaster.  Well actually it wasn't all that much of a disaster.  I was 
given some  homework after the review, it was to; refactor certain areas of the CLI
project to include finding all movies (oh yeah, for my project I chose to use a commercial
API that is an unofficial  database of Netflix's movies),  that were inclusive of a set
of parameters. i.e., >4.0 but < 7.0 and return an array with said conditions met. 
So I began to refactor with these formulae in mind. It was decided that the best place
for such a method would be in the Movies.rb class where it was obviously a concern
of that domain.  I chose to use *#each* since I only needed to iterate through the 
movie objects, shovel them into an array when they qualified as meeting the search
criteria.  Then returning that array.  The challenge was that if forgot that each value
in the rating parameter pointed to,  was a string.  So,  after testing I factored
that block and added *#to_f*. Simple.  I tested again and volia, it worked. And was very
happy.  Now I play catchup.  I'll be sure to let you all know how that progesses. Right 
here same time , same place.

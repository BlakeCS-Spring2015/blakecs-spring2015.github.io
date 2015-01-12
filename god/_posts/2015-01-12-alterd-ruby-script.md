---
layout: post
title: "Altered ruby script"
date: 2015-01-12 14:37:11
author: god
---

It worked!

The site isn't broken, and it seems to have fixed the problem. Added this bit of code to make a _posts directory if one doesn't already exist.


<!-- arbitrary comment -->

    if not File::directory?( "../#{shortname}/_posts" )
    
      puts "You don't have a _posts folder"
      
      Dir.mkdir("../#{shortname}/_posts")
      
      puts "Made _posts directory in #{shortname}"
      
    end

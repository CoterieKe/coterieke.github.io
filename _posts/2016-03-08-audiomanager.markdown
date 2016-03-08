---
layout: post
title:  "The Html5 AudioManager!"
date:   2016-03-08 17:12:50 +0300
tags: audiomanager javascript html5
location: Nairobi, Kenya
---
This is an exciting project I started in order to learn more about how to manipulate web audio.

I had previously worked using SoundManager and was curious if it was possible to come up with a similar implementation that runs purely on javascript including extraction of frequency data. At first it was extremely difficult bacsue most example regarding loading of audio files used ajax calls to load the files, which made it impossible to play large files before the browser had received the whole thing.

With time and a lot of searching a path was found involving the use of the Audio node. Apparently the information about it is available but it's not that easy to find.

MY first experiment was successful but I accidentally deleted all the files when attempting to add them to a repo.
--force is not your friend.

So now we're here. With an audioplayer capable of playing most audio formats and extracting frequency information. The functionality available is still very basic but I plan to expand it in future and implement all the events available and build something close to SoundManager, or better.

Backward compatibility is still an issue, but I'm traying to avoid any compatibity fixes involving the use of Flash.

So here we go. 

The demo page can be found here [Audiomanager Demo](/project/audiomanager)
---
layout: post
title: How PoW really works.
date: 2023-05-14 02:01
category: crypto
---

Well recently I was looking at some really basic pow implementations and since I was bored I decided to make a lil program at https://github.com/IdotMaster1/simple-pow/. All pow really does is just increasing a number called a nonce till you reach a target. In my implementation you have to have 4 zeros in the beginning. The program calculates the hash, then adds a "!" (which the nonce will be after) and then add the current nonce (it loops till it will reach the the "beginning zeros"). It calculates the hash and checks it, no 4 beginning zeros? Then start again. Continue and continue till you reach the target which is the beginning 4 zeros. Really, saying it's basic is an UNDERstatment as it doesnt even have any difficulty stuff (It makes it easier/harder depending if it's higher or lower). 

--

Other news: I set up an explorer for Bunkercoin at https://bkcexplorer.bunker.mt, hope you like it!
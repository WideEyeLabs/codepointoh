---
layout: post
title: "Hexidecimals, Binary, and other Radices"
date: 2013-02-13 16:49
comments: true
categories: 
---


  Would you believe that 0xDF9A2C, 110111111001101000101100 and 14653996 are all the same number? Two weeks ago I would have said 'Sure, but why the heck should I even care?'. While they all do represent the same number, where they differ is their radix. This is more commonly referred to as number's base.  When you see price tags, speed limits, and apartment numbers they are all in base 10. You may be wondering what exactly that implies. Base 10 means that we use ten unique characters to represent a number. Numbers we deal with on a daily basis are only made up of the characters 0 1 2 3 4 5 6 7 8 and 9.  Every number that you can count to is representable using this base 10 system. You may be wondering at this point if there are other radices (bases).  In fact there are. None of them are as commonplace as base 10 but they each definitely have their place. First lets take a look at binary, which is considered base 2.
<!-- more -->
### Binary

  Ever heard the saying 'There are 10 types of people in the world: Those who understand binary, and those who don't.' This funny saying specifically shows how quickly people assume the numbers they see are base 10 and not another base. Had they wrote 10<sub>2</sub>, some people might have caught on earlier that this wasn't a regular number. Following the previous statement I made about representing a number in base 10, we can do exactly the same with base 2. But this time, we can only use two unique characters. These just so happen to be 0 and 1. It almost seems impossible.  How can you possibly represent a number like 1256 with only two characters? With a bit of math, I'll do my best to explain this herculean task. 

  Lets start out with some simple math. I hope we can all agree that 2<sup>1</sup> = 2. And if you're really mathematically inclined, you'll already know that 2<sup>0</sup> = 1. If you didn't already know that's ok.  If we follow this pattern for a bit, we can actually build up a nice little chart with the following numbers:
  
<center>
<style>
	td, th {
		border: 1px solid black;
	}  
</style>
<table>
	<thead>
		<tr>
			<th style="width: 50px; text-align: center;"> &nbsp; &nbsp;2<sup>0</sup> </th>
			<th style="width: 50px; text-align: center;"> &nbsp;&nbsp;2<sup>1</sup> </th>
			<th style="width: 50px; text-align: center;"> &nbsp;&nbsp;2<sup>2</sup> </th>
			<th style="width: 50px; text-align: center;"> &nbsp;&nbsp;2<sup>3</sup> </th>
			<th style="width: 50px; text-align: center;"> &nbsp;&nbsp;2<sup>4</sup> </th>
			<th style="width: 50px; text-align: center;"> &nbsp;&nbsp;2<sup>5</sup> </th>
			<th style="width: 50px; text-align: center;"> &nbsp;&nbsp;2<sup>6</sup> </th>
			<th style="width: 50px; text-align: center;"> &nbsp;&nbsp;2<sup>7</sup> </th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td style="text-align: center;"> 1 </td>
			<td style="text-align: center;"> 2 </td>
			<td style="text-align: center;"> 4 </td>
			<td style="text-align: center;"> 8 </td>
			<td style="text-align: center;"> 16 </td>
			<td style="text-align: center;"> 32 </td>
			<td style="text-align: center;"> 64 </td>
			<td style="text-align: center;"> 128 </td>
		</tr>
	</tbody>
</table>
</center>
# AHRSYS
trading platform

AHRSYS is GUI or UI that pertains to a list [compiled by user] of traded symbols or symbols that require 
further analytics and fine-tuning. AHR calls this list the Opportunity Finder (OF). 
However, such list can be associated with a portfolio management[i] and/or 
performing analytical studies on particular financial instruments (symbols). 

https://www.patreon.com/posts/ahrsys-branded-19530791

... 
[generic? to stir the interest in open source, genetic is to get it done] regarding AHRSYS and how ClangOpenSourceLib can 
become the main charting engine. 

The focus is low latency internals and I could vision [in principle] two distinct modules, 
- the order execution and 
- data plotting (charting). 

I also see for low latency reasons considering two session of ClangOpenSourceLib running, 
- one that drives the list, 
- the other that drives the chartLib.

Data tailoring of analytics or better said “the chart design manager” is an auxiliary tool, 
not necessary attached to live-trading/[day trading].  When tailoring charts the task 
should not impair live trading and my recommendation is to use another machine for performance reason.

I said things in the past that one should be aware of: 
- (a) The AHRSYS is market performance scanner; 
- (b) The code is modular; 
- (c) the list is not the core element but it starts with a Computer Performance Tracker, 
  since the list is and will become resource hungry 
  [expect running more than one list with a pair of ClangOpenSourceLib] 
  [informing the user and error control to stop loading];
  
  - (d) Order Execution is a priority as a process -- not the data plotting module 
 [TCP/IP low latency datafeed-splitter]; 
 
 - (e) only for commercial reasons we will need to attach “the tailoring shop”; 
 - (f) portable to reach OSX, (hum windows) and Unix like OS/s; 
 - (g) time is a factor and how soon we can trade with is up to you; 
 - (h) options for chartLIB and OFdriver to use other programming languages 
 to interpolate with AHRSYS should be kept in prospective.
 
The new jargons on the market such as A.I., automated trading, algos, viros, neural, 
machine learning, etc., not the point but to expect occurring in custom programming. 

As far as I am concerned, most if not all branded platforms offer a tailoring shop. 
They might get inspired to expressions used [I know sarcasm], as such 
“what do you know, I may even trade today”.

-AHRSYS and ClangOpenSourceLib --also suggest a donation that I can afford. 
I would like to trade with such system to further contribute but as it is, I am limited.


AHR 20180623 @news_ahr 

*This document stays updated at https://github.com/bondibox/community-node/blob/master/sr_application/application.md*

> Please send an application form containing the above information to the sr@tron.network  




**`• Official Website`**  
[http://tron.communitynode.org/](http://tron.communitynode.org/)  
&  
[https://github.com/bondibox/community-node/](https://github.com/bondibox/community-node/)  




**`• Company information:`**  
The Community Node organization is an application of open source collaboration in the blockchain space. We seek to extend the Super Representative's role in the distributed network into a quasi-decentralized system by passing our role through to our community members. The organization will have a staff of executives and technical personnel, but it will be guided by our community members through collaboration and the referendum process. By sharing our IT strategies, it is our hope to strengthen the entire blockchain industry and advance the determination of best practices. 


c/o Jason Neely  
PO Box 39029  
Washington DC  
20016



**`• Social Media Following`**  
Our movement is still young and we are actively trying to bring in new members.  

Community Node on Telegram: [TRON Community Node & Super Representative](https://t.me/joinchat/IN2p-BFXGu8vByHn3qLyBg)  
Community Node on Twitter:  [@community_node](https://twitter.com/community_node)   
Our network administrator is active on Reddit [r/tronix]((http://reddit.com/r/tronix)) where he has become a go-to authority on the main net.



**`• Community Support Plan for 2018`**  
We have created a staging network which is a replica of the Tron network and which will allow the community to practice with wallets and to beta test the behavior of newly created dapps. [It is already working in alpha](https://twitter.com/bondibox/status/991872321559261184) with 1 witness and 2 seed nodes.  We will continue the expansion of our test net to include solidity nodes and web wallets.

We will create a How To demonstration for a simple dapp game that flips a coin and pays tokens when guessed correctly. Users can upload this dapp to the staging network to experience the same functionality as the Tron main net.

We have entered into a strategic partnership with the Sesame Seeds SR Group to provide community support on a broader level than either of us is able to provide on our own. Together we are operating a [TRON Help Group](https://t.me/joinchat/IN2p-BK-bWl1zSbN7L5zEQ) at Telegram to answer questions related to the Tron main net. 

We have contributed to the Tron Wiki and have pushed one set of changes.  

In keeping with our open source ideology, we will also be pooling our collective knowledge and establishing best practices for the rest of the SR community, and we will publish that information in a fork of the Official Tron documentation.





**`• Community promotion efforts`**   
We are holding a contest for the best main net java dapp, prize is 10,240 TRX payable from our node's first day of block rewards. Good for 10 dapp uploads on the Tron main net.



**`• Livestream`**  
https://www.periscope.tv/w/1ynKOAqXeEwJR  
Archived at YouTube:  
https://www.youtube.com/watch?v=PW0mWR9tVkw  







**`• List of key staff and their photos`**  
*CTO*				[Jason Neely](./jason_neely.jpg)    
*WAN Strategist*	[Greg](./photos/xxxxx)    
*dapp Education*		Colradi  





**`• Provide Background qualifications of key staff`**  
Chief Technical Officer / Founder  
> Jason Neely has maintained a *nix server almost constantly since 1998 when he installed RedHat and QTSS on his iMac. Soon after, he began work as an Apple Retail Representative, then went on to be a Tier 2 technician for Darwin Networks where he became Cisco certified. After the dot com bust he worked on the U.S. Congressional campaign of Andrew Horne, first as a volunteer who maintained the website and broadcasted emails, eventually writing copy and working directly with the communications team in a salaried position. From there, he formed Campaign Kickstart, a grassroots incubator, and developed an advocacy program for the Louisville Affordable Housing Trust Fund's Open the Door campaign (the legislature passed!). For the past 10 years he has been studying OOP and considers himself to be one of the last few Ruby on Rails enthusiasts.  


WAN Strategist  
> Greg is a SysAdmin for a leading Aerospace Manufacturer with over 90,000 users located around the globe. Over the past 12 years Greg has worked his way up the IT ladder learning many different products, software, and systems along the way. He currently holds a Bachelor in Networks and Communication and is near to completing his Technology focused MBA. Greg is an avid believer in the Tron Network Project and is excited to witness and be involved with its creation.

Application Education    
>  Colradi is a computer engineer in love with blockchain. He worked as an IT consultant and Java teacher for (too) many years in Madrid. Now he enjoys the inner peace of the mediterranean ocean, near Barcelona, and spends his days involved in a neverending Javascript project.




**`• Testable nodes`**  
[Full sync was reached](./number_one.png) on April 27 with 300+ blocks produced.




**`• Location of Server:`**   
Linode Cloud Hosting  
Atlanta Data Center  


**`• Server type:`**  
Cloud Based VM  



**`• Budget Expenditure and Technical Plan before June 26, 2018`**  
Domain Registration CommunityNode.org	 $15  
Super Representative Application Fee	 100,000 TRX  
May 1 - May 28 alpha configuration		 $20  
May 29 - June 21 beta configuration		 $120  
June 22 - June 26 Production Level I 	 $160  
									------------------  
Total expenses May 1 - June 26 = $315 + 100,000 TRX

The recommended configuration is to use Amazon AWS with 25 Gbps network i/o but we have found a hosting service with a OC768 incoming network connection, offering 40 Gbps in and 10 Gbps out. We believe that the incoming network connection will be critical for the Super Representative nodes, and the outbound connection will be used more with the Full Nodes. Therefore despite its shortcomings we believe there exists the potential for this service to be superlative to the de facto standard.

Even though the largest configuration available at this host is 16 core / 200 GB ram, we are confident our initial setup will accommodate the estimated 2,000 TPS of the main net since our alpha configuration was able to produce blocks with 200 transactions during the test net operation. 

We will compare this against AWS and will use whichever service performs better.

Data storage will use 2 TB encrypted SSD hot pluggable drive, expandable to 10 TB.

**`• Plans for hardware expansion`**  
Our witness node will start off with two identical server instances behind a HAProxy load balancer. This will provide us with redundancy and measurable performance of each node. We will deploy Full nodes on AWS which has a higher outbound network connection than our main node will employ.

Based on our usage metrics we may advance our timeline for clustering our main node server in a replicated docker & kubernetes system, which we hope to accomplish by December 31, 2018.




**`• Budget expenses`**  
June 27 - June 30 Production level II $4,140  
July 1 - July 31 Production level III $50,000  
August 1 - December 31 Production level IV Estimate pending  

Promotional contest 10,240 trx









### ***`DETAILED HARDWARE CONFIGURATIONS`***  


#### ALPHA TEST CONFIGURATION  
Debian GNU/Linux 9.1 (stretch) 4.15.12-x86_64  
2500 MHz Intel(R) Celeron(R) M processor  
4	 	GB RAM    
2 		CPU Cores    
46 		GB SSD Storage    
40 		Gbps Network In    
1 		Gbps Network Out    
2256	SWAP  



#### BETA TEST CONFIGURATION  
2500 MHz Intel(R) Celeron(R) M processor  
24	 	GB RAM  
8	 	CPU Cores  
384 	GB SSD Storage  
40 		Gbps Network In  
2	 	Gbps Network Out  



#### PRODUCTION LEVEL I CONFIGURATION  
2500 MHz Intel(R) Celeron(R) M processor  
200 	GB RAM    
16 		CPU Cores        
2+		TB SSD Storage  
2		GB Swap  
40 		Gbps Network In    
10 		Gbps Network Out    






#### PRODUCTION LEVEL II  

-- PRIMARY INSTANCE --  
2500 MHz Intel(R) Celeron(R) M processor  
200 	GB RAM    
16 		CPU Cores    
2+		TB SSD Storage  
2		GB Swap  
40 		Gbps Network In    
10 		Gbps Network Out    


-- FAILOVER INSTANCE --  
2500 MHz Intel(R) Celeron(R) M processor  
200 	GB RAM    
16 		CPU Cores    
340 	GB SSD Storage    
2		GB Swap  
40 		Gbps Network In    
10 		Gbps Network Out    








#### PRODUCTION LEVEL III
-- PRIMARY INSTANCE --  
AWS 	x1.16xlarge  
64 		cores  
1 		TB RAM  
1		TB SSD(EBS)  
25		Gbps Network  

-- FAILOVER INSTANCE --  
2500 MHz Intel(R) Celeron(R) M processor  
200 	GB RAM    
16 		CPU Cores    
2+		TB SSD Storage    
40 		Gbps Network In    
10 		Gbps Network Out    







#### PRODUCTION LEVEL IV
Kubernetes • Hadoop * Docker replicated network  

TBD  



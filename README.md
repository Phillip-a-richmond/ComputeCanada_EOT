# Compute Canada Education, Outreach & Training Tutorial Site

Welcome to the Compute Canada Education, Outreach and Training Tutorial Site! Here you can find links to independent tutorial sessions, multi-day workshops, and other educational content.


## Short read mapping and visualization on HPC

+ *WHEN* 9:00AM-12:00PM (PDT), Tuesday June 12th, 2018
+ *WHERE* 
+ *WHO*  
+ *WHAT* Short-read mapping and visualization, primer for multiple different pipelines on Compute Canada Cedar system.
+ *WHY* 

### Before the Course Starts
For all Mac users, please attempt to login to cedar using the terminal application on your computer:

Spotlight —> Terminal —> then type:   
ssh username@cedar.computecanada.ca  
Enter your password (it won’t look like you’re typing anything but it is registering it)  
Then hit Enter.  

For PC Users, please download MobaXTerm. 
The link is [here](http://mobaxterm.mobatek.net/download.html):  
<http://mobaxterm.mobatek.net/download.html>  
Click on the free home version.  

Then open it up, and login to the cedar server in the same way:  
ssh username@cedar.computecanada.ca  
Enter your password (it won’t look like you’re typing anything but it is registering it)  
Then hit Enter.  

Example:  
ssh wc-guest07@cedar.computecanada.ca
(types in password)  
(hits enter)  
Done!  

### Important Links. 

+ [Etherpad]() 
+ [Slides](https://docs.google.com/presentation/d/1O2BewoJgp-m3aEKYm8XnVlPJBEnBaWeO_UJ0yKhz8Lw/edit#slide=id.g3bdbd3a49d_0_112)
+ [Github Gist]()
+ [Problem Set]()
+ [Vidyo Broadcast]()
+ [Session Recording]()

### Itinerary
9-9:30 (Lecture) - Into to Short read mapping and different data types: ChIP-seq (TF, H3K27?), DNA-seq, (GRO-seq)* 
9:30-10:15 (Follow-along) - Read mapping of different data files using salloc (BWAmem, samtools) and SLURM 
10:15-10:45 (Independent) - Coffee & Problem Set 1 (Choose files from directory, make edits to scripts so they work, map and convert to bam)
10:45-11:15 (Follow-along) - Download processed data from Cedar to local machine (OR Mount Cedar** Something to discuss)
11:15-11:30 (Lecture) - Next steps you could take with this data, including pointing to job scripts that can handle peak calling (bedtools —> HOMER) or variant calling (Picard —> GATK)
11:30-12:00 (Independent) - Problem set 2 (Play with some of the other downstream processing steps on the data you started with)

NOTES:

Extra Problemset Examples:
ChIP-seq: How many peaks are there for __ TF?
How many peaks are there in 

_____

## Introduction to Linux Command Line

+ *WHEN*: 10:00AM-12:00PM (PDT), Tuesday September 26th, 2017.    
+ *WHERE*:  Hosted virtually via ComputeCanada Vidyo.  
+ *WHO*:  Academic researchers in Canada.     
+ *WHAT*: Introduction to Linux Command Line Basics. 
+ *WHY*:  Because utilizing high performance compute resources for research projects in the 21st century is important.  

### Before The Course Starts
For all Mac users, please attempt to login to orcinus using the terminal application on your computer.

Spotlight —> Terminal —> then type:   
ssh username@orcinus.westgrid.ca  
Enter your password (it won’t look like you’re typing anything but it is registering it)  
Then hit Enter.  

For PC Users, please download MobaXTerm if you would like to follow along.  
The link is [here](http://mobaxterm.mobatek.net/download.html):  
<http://mobaxterm.mobatek.net/download.html>  
Click on the free home version.  

Then open it up, and login to the orcinus server in the same way:  
ssh username@orcinus.westgrid.ca  
Enter your password (it won’t look like you’re typing anything but it is registering it)  
Then hit Enter.  

Example:  
ssh wc-guest07@orcinus.westgrid.ca  
(types in password)  
(hits enter)  
Done!  


### Important Links
+ [Etherpad](https://etherpad.openstack.org/p/EOT_Tutorial_IntroToLinuxCommandLine) 
+ [Slides](https://docs.google.com/presentation/d/10NFhAUhJKRm5HTPmHxhxWVEVFEIn3zfFw9-qpnuo1EY/edit?usp=sharing)
+ [Github Gist](https://gist.github.com/Phillip-a-richmond/a22f4e967c1fd56235f77fbe1c7936f8)
+ [Problem Set](https://github.com/Phillip-a-richmond/ComputeCanada_EOT/blob/master/IntroToLinuxProblemSet.txt)
+ [Vidyo Broadcast]()
+ [Session Recording]()


_____

## Introduction to Genomic Analysis

This is a full 7-day workshop series, with documentation found here:

https://phillip-a-richmond.github.io/Introduction-to-Genomic-Analysis/















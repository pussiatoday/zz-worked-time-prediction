**Was suspended long ago, is to be archived. Before archiving the repo, I’m going to rename it from `zz-worked-time-prediction` to `worked-time-prediction`, because I’m as of now dropping this ISO-3166-1-alpha-2-based naming scheme for my personal repos. It shouldn’t hurt anyone, as I don’t believe anyone had it referenced or cloned before, including myself.**

https://rayyan-social.qcri.org/main-forum/how-do-you-calculate-the-time-spent-on-screening/

How do you calculate the time spent on screening?  
     Last Post   RSS 
Rayyan Admin
  Rayyan Admin
Eminent Member
 
Joined:2 years  ago Posts: 33
20/06/2017 10:12 am   
There is no running counter that runs when you open Rayyan. The calculation is based on the timestamps of the decisions/labels you put. For example, when you click on "Include" at time 0, then another "Exclude" after 2 seconds, the duration between both actions is accumulated to denote that you have been working for 2 seconds. If however, you left the review for more than 10 minutes then do the third action, Rayyan will detect that you have been idle all that time and will increment the number of sessions you have worked on but not the total duration. The fourth action after 5 seconds will accumulate only 5 seconds to the duration. Moreover, Rayyan will put an extra minute for each session assuming that you have spent some time looking at the review before making the action. In this example I have just explained total sessions will be 2 and total duration will be 2 + 5 = 7 seconds + 2 minutes. As you can see, the time spent is an estimate only which we think is the most representative of the actual time based on our experiments.


pjelnov liked  ReplyQuote
pjelnov
  pjelnov
New Member
Joined:2 months  ago Posts: 1
07/11/2018 12:08 am   
Warm greetings to the Rayyan team,

You have been doing incredible work. The project is not only helpful in conducting systematic reviews—with the offline screening app, it really is one of a kind, and the free-to-use status is truly golden.

Concerning the issue above, the screening time estimation feature is a valuable one, indeed, for the time management potential it carries. Though as far as I know, it has not previously been elaborated on in detail neither in the Syst Rev (2016) 5:210 article, nor throughout Rayyan Social. Specifically, are the data on the experiments you mentioned available for review?

Kind regards,

Pavel Zhelnov, MD


 ReplyQuote

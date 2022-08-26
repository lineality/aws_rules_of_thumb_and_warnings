aws_rules_of_thumb_and_warnings github v1

## AWS Rules of thumb & warnings on AWS instructions and documentations:
- Break everything down in to small concrete steps and test progress one small step at a time, and document and version and save everything with as much clarity as is possible in the extreme. 
- AWS services and interfaces change quickly enough that many tutorials and documentation pages are unrecognizably different from what you see and do.
- Expect to spend a week making your own documentation and process from scratch because one simply will not be available, even for basic routine tasks.
- Expect, require yourself, to explore at least a dozen different walkthroughs and explanations from different sources. 
- Treat 'instances' and builds as disposable. Rebuild them rather than modify them; just like python environments. 
- Be wary of short-fast explanation articles and videos. My personal documentation for using vanilla docker with AWS is 26 pages long and does not even start talking about custom-base docker (which you often will need). Huge parts of projects that you need to plan for are completely left out of edu-tainment articles for fun-fast-coding. 
- Development in AWS simply cannot be rushed, and fatal snags can emerge at the very very very last second making a project unworkable (every single step taking months to develop works perfectly but the user cannot connect for no known reason, all the functions work in testing but they are somehow incompatible with API-gateway at the last minute). Some things are very fast, but others are not. A task might take 5 minutes, or might take 5 weeks, and with AWS it is very difficult to predict how long it will take. 
- Often the final process is very simple yet it is not documented anywhere that is available to you when you start. Only by trying 25 different stack-overflow articles and mixing their approaches together can you find what works. 
- Name what you create in AWS as extremely carefully as possible AWS_service_purpse/goal_your_initials_datestamp. 
- Turn off services and delete anything you don't need as soon as you can. 

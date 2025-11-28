# QA within an AI-driven organization
Testing has been slowly changing for a long time now and AI will cause a shift once again. 
To illustrate that we will start with a history lesson: 
A long time ago development projects were setup using the waterfall method.

| Phase           | Description                |
|-----------------|---------------------------|
| Requirements    | Gather and analyze needs  |
| Design          | Plan system architecture  |
| Implementation  | Develop the solution      |
| Verification    | Test and validate         |
| Maintenance     | Support and improve       |

Testing was done just before release and when issues were found and requirements needed to change because of it, it would quickly become costly and very slow to fix. These projects could take years to specify, develop and test. 

Currently most software development happens in an agile way. The agility differs highly between companies but most try to shorten the release cycles. This means instead of a big release every year it moved to multiple releases within the year with smaller features and quicker feedback. This meant that QA had to adapt, the time they have to test has been shortened from months to a couple of days/hours. This meant a shift left towards test automation to be able to work on your tests before the implementation of the software was finished. 

Now we are at a turning point where the development might be done by AI and could speed up once again. This would mean the time to market will shorten again. How will QA be able to keep up with the theoretical development speed an AI can have? What will be the role of QA and how can we prevent QA from being the bottleneck for deployments. 

If AI will take over (part of) development, QA will need to pivot as well.
We either need to accept AI is taking over, let AI generate our testcases and our testcode but verify what it generated and make sure everything is covered. 
Or we can shift even further left. If AI will interpret our requirements and generate the software based on that, we should make sure the requirements that we are feeding the system are correct. 

For a long time there has been a divide within QA between test automation and manual testers. Managers thought they could automate everything and testers wouldn't be needed after that. I've personally not seen a project where fewer testers were needed after automating the tests. As maintenance, evaluating results and adding new tests for new features is a constant.



Curriculum
SE Foundations
Average: 120.79%
0x01. Fix my code
Background Context
Fix my code is a new type of project, where we’ll jump into an existing code base and fix it!

Sometime you will know the language, sometime not.

Please download the repository 0x01-Fix_My_Code_Challenge and use it as initial files for all solutions.

You should not recode everything, just fix it!

This project is NOT mandatory at all. It is 100% optional. Doing any part of this project will add a project grade of over 100% to your average. Your score won’t get hurt if you don’t do it, but if your current average is greater than your score on this project, your average might go down. Have fun!

Requirements
General
Allowed editors: vi, vim, emacs
All your files will be compiled on Ubuntu 14.04 LTS
All your files should end with a new line
A README.md file, at the root of the folder of the project is mandatory
More Info
Manual QA Review
It is your responsibility to request a review for this project from a peer before the project’s deadline. If no peers have been reviewed, you should request a review from a TA or staff member.

Tasks
0. Server status
#advanced
I just started a new Flask project and the first thing I’m putting in place is a route for the status of my API (super important for a load balancer implementation).

But I don’t know why it’s not working…

Could you look at it and fix it please?

My code is here

$ python -m api.v1.app 
 * Running on http://0.0.0.0:5000/ (Press CTRL+C to quit)
....
$ curl -XGET http://0.0.0.0:5000/api/v1/status
{
  "error": "Not found"
}
$
Repo:

GitHub repository: Fix_My_Code_Challenge
Directory: 0x01-challenge
File: status_server/
 
1. My square
#advanced
I love geometry!

Look my square, it’s perfect? No? Should I change something?

Repo:

GitHub repository: Fix_My_Code_Challenge
Directory: 0x01-challenge
File: square.py
 
2. Step 2: User model
#advanced

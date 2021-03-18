# Github--Classroom

Some random notes about using Github Classroom.

These are some resources that will help you understand how you can use Github Classroom to facilitate teaching.

My own journey started at this site:
https://education.github.community/t/my-guides-to-using-github-classroom-for-teachers-and-students/15717

From there, I was led to the author's guides to Github, which can be found here for teachers:
https://github.com/jfiksel/github-classroom-for-teachers

and here for students:
https://github.com/jfiksel/github-classroom-for-students

The idea is that Classroom makes it easy for students to set up 'clones' of your repositories such that their clones are private to everyone except you and that student, as is required by U.S. law.

The advice there is to set up a master 'organization' (group of users) and repository for each course you teach, and then fork from that 
to create a new instance of the course each subsequent year. I actually find it easier to simply fork each repository from the previous year's
version each new year, so I do that rather than creating a 'master' repo.

## Other random notes as I think of them:

* I send the invitations to the repositories for a given week via Blackboard (putting the message on the "Announcements" page on Blackboard for those who might miss the email).
* If you set all your directories up to be 'public', students will be able to view and fork from them regardless of whether or not they formally join the organzation for the course.
* When students create their repos, by accepting the invitations you send them, they will have the following properties:
  + You will be able to access those repos to read the material for grading purposes, for example, even though the repos are 'private'.
  + Every time they create an issue, to say they have added answers to an assignment, for example, Github will send you a message to let you know.
  + Github will also inform you of other messages they submit (e.g. commit messages) provided they include your Github ID in that message (e.g., "@pmarjora")
* Inevitably, in the first few weeks one or two students will clone the repo themselves (which they can do because it is public) rather than using the inviation you send them. This will work, in the sense that they will get a copy of your repo that looks identical to the one they would have got had they accepted your invitation, _but_ you will not be able to access that repo (unless they make it public), nor will you be informed when _they_ update the repo (even if they do make it public). If a student says they have submitted something but you cannot see it, this is the likely cause.
* A minor drawback of Github Classroom is the number of repositories that you will end up having in the course organzation for that year. If you have _n_ students and _m_ repositories over the semester, this process will create _n x m_ new repos in your organization. (I end up with several hundred repos each year in PM520.) Github allows for no easy folder structure within the repo, so the easiest work around for that when you are trying to find one of your own folders is to name repos carefullly and use the search function (restrict the search to "public" repos if you only want to see your repos). 


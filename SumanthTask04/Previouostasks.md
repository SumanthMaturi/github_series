**Task-1**
**1.**Git is an distributed version control software which helps us to manage our source code related works. Also git is used to handle combining of different sourcecodes from different members in coding society.
Where, Github is a website / an Web Service at which an user may have individual account on that web server where it actually  works as an social network  for projects that are managed through Git.
**02.**we can say that it is the largest repository in the world which is well known for its valuable space that it provides for data to be stored. It allows to store unlimited public codes as repositories where we can also create organisations .Also github is mainly known for its features as it provides some trademarking features such as
i) repository
ii) commit
iii) commit hash
**03.**
We need to be updated daily i.eee,we have to be more relavant to updations rather than believing in past done work .an version control system enables user to update his or her repositories which records any changes that are made to the respected file which can be called with specific versions
Git is considered as an version control system since in gut we can keep an track record of all our work and easily navigate among the many versions of file that we create. Also git allows an user toa ssign task to different user making it cluster clear who is responsible for which part of the analysis.
**04.**
I found some platforms same as github such as:
Source Forge, Apache Allura, Gitlab e. t. c.,
**05 .**
Many interviews ask for an github profe to see oyr projects and our work relatedd efficiency. A good agithub profile can impress an HR and is an valuable skill to have as an programmer, not only for maintaining an work place but also personally. Companies usually loves programmers that invest themselves for the community by vigourous practice finally learning can defnitely give us really a good job. Using git give us an wideexposure for our taking up projects or done projects or for our practice.
**TASK:02    :: Submission**                                                                                                                                                                                                                                              **QA.** How git workflow works?
**Ans-**
1. Working directory  is Workspace.
2. Index is stage
3. Local Repository is Head
4. Remote Repository
There is one central repository.
Each developer clones the repository they created,
works locally on the code,
Modifies and makes the changes as required
Commit the changes using command commit  with changes
and push it to the central repository
for other developers to pull and use in their work.
**QB.** What are the different stages of a git project as commit ,add?
**Ans-** Different stages of a git project:
     1.Untracked
     2.Staged
     3.Committed
**QC.** Is it possible to do a git commit before git add. if you have made any changes. Explain why?
**Ans-**  No, because according to the process
first, we have to add the file and then commit changes to it(any changes)
After making the changes we will add them using “git add .”
and then we can commit it using (commit -a).
**QD.** why is git diff used?
**Ans-** git diff is used mainly to track the difference between the changes made on a file time to time. This command shows all the
changes which are done to an particular file. Diff command takes two inputs and reflects the differences between them. These inputs don’t need to be filed only.
It can be branches, working trees, commits, and more.
**QE.** Can we leave a commit message as blank?
**Ans-** Yes , we can leave a commit message blank.
It is a valid request, commit can have no message at all.
Link to GitHub repository :https://github.com/SumanthMaturi/sumanthgitseries/tree/master
**TASK 03 :: SUBMISSION**
Once you completed all the tasks perfectly you need to do the following things to get marked as completed by our team
**1.** Share the link of the PR you have made, so you need to submit the link of two PR's.
Link1: https://github.com/codewayy/github_series/pull/137
Link2: https://github.com/SumanthMaturi/github_series/pull/1
**a.)** What is meant by the term fork and clone?
Fork:
To contribute in someone's else project or to make others project as your starting point,you will undergo an process called as forking.
Create a 'fork' produces another project as our personal copy.Forking is at the core of GitHub.
Clone:
Clone is copy of the target repository.
                    git-clone - "Clone a repository into a new directory"
**b.)** What are branches in Github?
A branch in Git is simply acts as a lightweight movable pointer to one of these commits.
The default branch name in Git is "master".
As you start making commit actions, you are given a master branch that points to the last commit you made.
Every time you commit, the master branch pointer moves forward automatically.
**c.)** What is PR?
(PR)Pull requests let you tell others about changes you've pushed to a branch in a repository on GitHub.
**d.)**Can we delete the master branch if not Why?
No.
Because github is looking at the master branch to provide the web content when you browse that repository.
 So we first have to make github look at our placeholder branch instead, then delete master.
**e.)**How can we delete a branch?
locally:-
s1:git checkout master
s2:git branch -d <branch>.
      For example: git branch -d level01/submission
The -d option will delete the branch only if it has already been pushed and merged with the remote branch.
 Use -D instead if you want to force the branch to be deleted, even if it hasn't been pushed or merged yet.The branch is now deleted locally.
Remotely:-
s1:git push <remote> --delete <branch>.
      For example: git push origin --delete level01/submission
The branch is now deleted remotely.
OR,
git push <remote> :<branch>
For eg: git push origin : level01/submission.


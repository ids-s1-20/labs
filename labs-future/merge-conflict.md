Workflow

This is the second week you're working in teams, so we're going to make things a little more interesting and let all of you make changes and push those changes to your team repository. Sometimes things will go swimmingly, and sometimes you'll run into merge conflicts. So our first task today is to walk you through a merge conflict!

Merge conflicts

When two collaborators make changes to a file and push the file to their repo, git merges these two files.

If these two files have conflicting content on the same line, git will produce a merge conflict.

Set up

Clone the repo for your next assignment in RStudio, and open the .Rmd file.

Assign the numbers 1, 2, 3, and 4 to each of the team members.

Let's cause a merge conflict!

Take turns in completing the exercise, only one member at a time.

Member 1: Change the team name to your actual team name, knit, commit, push.r emo::ji("stop_sign") Wait for instructions before moving on to the next step.

Member 2: Change the team name to some other word, knit, commit, push. You should get an error. Pull. Take a look at the document with the merge conflict. Clear the merge conflict by choosing the correct/preferred change. Commit, and push.r emo::ji("stop_sign") Wait for instructions before moving on to the next step.

Member 3: Add a label to the first code chunk, knit, commit, push. You should get an error. Pull. No merge conflicts should occur. Now push.r emo::ji("stop_sign") Wait for instructions before moving on to the next step.

Member 4: Add a different label to the first code chunk, knit, commit, push. You should get an error. Pull. Take a look at the document with the merge conflict. Clear the merge conflict by choosing the correct/preferred change. Commit, and push.r emo::ji("stop_sign") Wait for instructions before moving on to the next step.

All members: Pull, and observe the changes in your document.

Tips for collaborating via GitHub

Always pull first before you start working.

Commit, and push, often to minimize merge conflicts and/or to make merge conflicts easier to resolve.

If you find yourself in a situation that is difficult to resolve, ask questions asap, don't let it linger and get bigger.
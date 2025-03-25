                Add a row to the table and fill it in with your information  Add your row above this section! 
                 (1) "git add index.html" - Tell git to include index.html in the next revision of the repository 
                 (2) "git commit -m"[your name]"" - Tells git to save a version of the repository with your new changes 
                 (3) "git push" - Uploads the changes to the remote repository 
                 (4) Resolve the conflicts using Webstorm's GUI. When resolving conflicts, you need to think critically about what changes should be kept and what shouldn't
                 (5) Repeat steps 2 and 3 
                 (6) Go to GitHub and see your changes! 
                 Push it back to the git repository, resolving any merge conflicts 

                Steps to create a pull request (So that your code can be merged with the main branch or any branch)
                1.) Push your changes to your local branch
                2.) Go to the repository on Github, click branches, and click the three dots next to your branch
                3.) Select "Create Pull Request"
                4.) Add a description to your pull request
                5.) Submit the Pull Request
                6.) Someone on the team will review the code, fix any merge conflicts (via Webstorm or Github Merge Conflict Editor), and then either approve your changes or discard them
                7.) Done! See the steps below on pulling someone's accepted PR into your local branch
                
                Steps to pull in changes from main branch into your local branch....AKA someone merged their PR
                1) git fetch origin // this makes our git aware of all other branches 
                2) git checkout main
                3) git pull // pulls merged changes from updated main into your main
                4) git checkout BRANCHNAME
                5) git merge main // get changes from updated main branch into your branch

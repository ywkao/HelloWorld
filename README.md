# HelloWorld
This is a re-biginning project.

This is Yu-Wei. My habits includes reading, Aikido, and archery.
Trying to equip myself with the skills of using github. :)

Ohter to-learn stuffs includes,
- C++
- Python
- HackMD
- Latex
- Root

Also, foreign languages I am interested in are,
- Japanese
- French
- Russian

In addition, several countries I want to visit are,
- Japan
- Swiss
- Russia
- Turkey

GitHub workflow
1) git clone [url] [dir]
2) git branch [branch]
   git checkout -b [new_branch] [existed_branch]        # establish new one on top of the existed one.
   git checkout [branch]                                # move to the branch you want to work on.
3) git add [files]
4) git commit -m [messages]                             # add comments about the update.
5) git push origin [branch]                             # update to the remote (origin).
6) git checkout master && git merge master [branch]
   git push origin master
7) pull-request is better be done on webpage.
   If the master is updated from somewhere / by others,
   the local master branch should be updated.
   git checkout master
   git fetch                                            # Get the updated info of the latest master.
   git merge origin/master                              # merge the current branch with the master branch on origin.

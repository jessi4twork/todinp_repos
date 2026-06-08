#Following The Odin Project Foundation Course path, I am creating a recipe html file. Upon completion, this will show skills I have acquired based on my own understanding such as setting up a boilerplate, utilizing elements and attributes, using opening and closing tags when called for.

##Project Journal (recent first)

##June 8, 2026
- **Created:** all 3 recipe html files css versions

##June 3, 2026
- **Moved:** soup, pasta html recipes, and odin_recipes_main.html to recipes directory
- **Edited:** index.html file name to odin_recipes_main.html
- **Added:** nav on odin_recipes_main.html
- **Created:** odin_recipes_main.css

##May 20, 2026
- **Note:** Added kimchi_tofu_soup.html and one_pan_pasta.html

###May 18, 2026
- **Learned #1:** After `add` -> `commit` -> `push` workflow, it failed due to changes I made directly on github.
- **Fixed #1:** Need to remember using git `pull` first or stick with working on code on local machine to avoid divergent branches.
- **Learned #2:** Tried to access git push --help because git pull and push was not working. But couldn't get out of it.
- **Fixed #2:** Pressed "q" key to exit.
- **Learned #3:** Need to save my code in local machine while I `pull` edit I did directly in github.
- **Fixed #3:** Used git `stash` to temporarily hide my code in local machine.
- **Learned #3:** Previous steps did not work.
- **Fixed #3:** Did git `branch journal-backup` to help save the entry I am trying to commit in back up branch so I don't lose it. Then git `checkout main` to force the terminal to leave the detached state and return to my local main branch cause it kept going back to that in a loop. After that, git `reset --hard origin/main` to force my local main branch to match the online github history to clear out mismatch errors. And then, git `merge journal-backup` to bring back the entry from my backup branch. I was able to successfully do git `push origin main`.
- **Note:** Added eli_wonton.html

###May 14, 2026
- **Learned #1:** How to edit git `commit` message before doing git push.
- **Fixed #1:** Utilized git `commit --amend -m "New correct commit message."`
- **Learned #2:** How to remove file from staging area after doing git add but will not delete my code.
- **Fixed #2:** Used git restore --staged filename.html

###May 12, 2026
- **Learned:** Figured out the `add` -> `commit` -> `push` workflow.
- **Fixed:** Sent the "delivery truck" with actual packages this time!
- **Note:** Don't forget to check branch names next time.

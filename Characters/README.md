Image Sources

Jerry 
https://upload.wikimedia.org/wikipedia/en/f/f8/Jerry_Seinfeld_%28character%29.jpg

George
https://static.wikia.nocookie.net/seinfeld/images/7/76/George-costanza.jpg/revision/latest?cb=20110406222711

Elaine
https://akns-images.eonline.com/eol_images/Entire_Site/201963/rs_1024x759-190703115558-1024x759-seinfeld-gj-7-3-19.jpg?fit=around%7C776:576&output-quality=90&crop=776:576;center,top

Kramer
https://static1.srcdn.com/wordpress/wp-content/uploads/2022/05/Kramer-Seinfeld-How-Afford-Apartment.jpg


Sources for descriptions

https://seinfeld.fandom.com/wiki/Elaine_Benes

https://seinfeld.fandom.com/wiki/Cosmo_Kramer

https://seinfeld.fandom.com/wiki/Jerry_Seinfeld

https://seinfeld.fandom.com/wiki/George_Costanza

Notes>
Terminal after trying to push my branch and entire page:

The default interactive shell is now zsh.
To update your account to use zsh, please run `chsh -s /bin/zsh`.
For more details, please visit https://support.apple.com/kb/HT208050.
MacBook-Pro:seinfeld-website-group-2-project samanthastewart$ git add -A
MacBook-Pro:seinfeld-website-group-2-project samanthastewart$ git commit -m "character page"
[Characters 774ae5e] character page
 Committer: Samantha Stewart <samanthastewart@MacBook-Pro.local>
Your name and email address were configured automatically based
on your username and hostname. Please check that they are accurate.
You can suppress this message by setting them explicitly. Run the
following command and follow the instructions in your editor to edit
your configuration file:

    git config --global --edit

After doing this, you may fix the identity used for this commit with:

    git commit --amend --reset-author

 8 files changed, 215 insertions(+)
 create mode 100644 Characters/README.md
 create mode 100644 Characters/characters.html
 create mode 100644 Characters/images/elaine.jpeg
 create mode 100644 Characters/images/george.jpeg
 create mode 100644 Characters/images/jerry.jpeg
 create mode 100644 Characters/images/kramer.jpeg
 create mode 100644 Characters/images/seinfeld_logo-1.png
 create mode 100644 Characters/style.css
MacBook-Pro:seinfeld-website-group-2-project samanthastewart$ git push origin
fatal: The current branch Characters has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin Characters

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.

MacBook-Pro:seinfeld-website-group-2-project samanthastewart$ git push --set-upstream origin Characters
ERROR: Permission to m1crckt/seinfeld-website-group-2-project.git denied to samstew3.
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.
MacBook-Pro:seinfeld-website-group-2-project samanthastewart$ git branch
* Characters
  main
MacBook-Pro:seinfeld-website-group-2-project samanthastewart$ git add -A
MacBook-Pro:seinfeld-website-group-2-project samanthastewart$ git commit -m "character page"
On branch Characters
nothing to commit, working tree clean
MacBook-Pro:seinfeld-website-group-2-project samanthastewart$ git push origin Characters
ERROR: Permission to m1crckt/seinfeld-website-group-2-project.git denied to samstew3.
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.
MacBook-Pro:seinfeld-website-group-2-project samanthastewart$ git push --set-upstream origin Characters
ERROR: Permission to m1crckt/seinfeld-website-group-2-project.git denied to samstew3.
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.
MacBook-Pro:seinfeld-website-group-2-project samanthastewart$ git add -A
MacBook-Pro:seinfeld-website-group-2-project samanthastewart$ git commit -m "character pages"
[Characters 1f794b8] character pages
 Committer: Samantha Stewart <samanthastewart@MacBook-Pro.local>
Your name and email address were configured automatically based
on your username and hostname. Please check that they are accurate.
You can suppress this message by setting them explicitly. Run the
following command and follow the instructions in your editor to edit
your configuration file:

    git config --global --edit

After doing this, you may fix the identity used for this commit with:

    git commit --amend --reset-author

 2 files changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 .DS_Store
 create mode 100644 Characters/.DS_Store
MacBook-Pro:seinfeld-website-group-2-project samanthastewart$ git push origin Characters
ERROR: Permission to m1crckt/seinfeld-website-group-2-project.git denied to samstew3.
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.
MacBook-Pro:seinfeld-website-group-2-project samanthastewart$ git push --set-upstream origin Characters
Enumerating objects: 18, done.
Counting objects: 100% (18/18), done.
Delta compression using up to 10 threads
Compressing objects: 100% (17/17), done.
Writing objects: 100% (17/17), 116.67 KiB | 4.49 MiB/s, done.
Total 17 (delta 3), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (3/3), done.
remote: 
remote: Create a pull request for 'Characters' on GitHub by visiting:
remote:      https://github.com/samstew3/seinfeld-website-group-2-project/pull/new/Characters
remote: 
To github.com:samstew3/seinfeld-website-group-2-project.git
 * [new branch]      Characters -> Characters
branch 'Characters' set up to track 'origin/Characters'.
MacBook-Pro:seinfeld-website-group-2-project samanthastewart$ 

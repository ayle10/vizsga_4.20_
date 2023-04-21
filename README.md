git clone https://github.com/szabopeter92/git-vizsga.git
cd git-vizsga
touch README.md
touch .gitignore
*.txt
*.doc
*.docx
*.pdf
git branch console
git checkout console
git add .
git commit -m "Add console logging and background color transition"
git push origin console
window.onload = function() {
  console.log("Az oldal sikeresen betöltődött");
};
git branch
git status
git add app.js style.css
git commit -m "Az oldal sikeresen betöltődött, és a háttérszín átmenetes lett."
git commit -m "Új háttérszín hozzáadva"
git add .
git remote set-url origin https://github.com/ayle10/vizsga_4.20_.git
git push -u origin master

cyborg@DESKTOP-3MKIE5L MINGW64 ~/git-vizsga (console)
$ git commit -m "háttér megváltoztatva"
[console 824471c] háttér megváltoztatva
 2 files changed, 5 insertions(+), 1 deletion(-)

cyborg@DESKTOP-3MKIE5L MINGW64 ~/git-vizsga (console)
$ git add index.html style.csss app.js
fatal: pathspec 'style.csss' did not match any files

cyborg@DESKTOP-3MKIE5L MINGW64 ~/git-vizsga (console)
$ git add index.html style.css app.js

cyborg@DESKTOP-3MKIE5L MINGW64 ~/git-vizsga (console)
$ git commit -m "minden változtatás végbe ment"
On branch console
nothing to commit, working tree clean

cyborg@DESKTOP-3MKIE5L MINGW64 ~/git-vizsga (console)
$ git remote set-url origon "https://github.com/ayle10/vizsga_4.20_.git~"
error: No such remote 'origon'

cyborg@DESKTOP-3MKIE5L MINGW64 ~/git-vizsga (console)
$ git push
fatal: The current branch console has no upstream branch.        
To push the current branch and set the remote as upstream, use   

    git push --set-upstream origin console

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.       


cyborg@DESKTOP-3MKIE5L MINGW64 ~/git-vizsga (console)
$ git push https://github.com/ayle10/vizsga_4.20_.git~
remote: Repository not found.
fatal: repository 'https://github.com/ayle10/vizsga_4.20_.git~/' not found

cyborg@DESKTOP-3MKIE5L MINGW64 ~/git-vizsga (console)
$ git remote set-url origin https://github.com/ayle10/vizsga_4.20_.git

cyborg@DESKTOP-3MKIE5L MINGW64 ~/git-vizsga (console)
$ git push -u origin master
error: src refspec master does not match any
error: failed to push some refs to 'https://github.com/ayle10/vizsga_4.20_.git'

cyborg@DESKTOP-3MKIE5L MINGW64 ~/git-vizsga (console)
$ git remote set-url origin https://github.com/ayle10/vizsga_4.20_.git

cyborg@DESKTOP-3MKIE5L MINGW64 ~/git-vizsga (console)
$ git push
fatal: The current branch console has no upstream branch.
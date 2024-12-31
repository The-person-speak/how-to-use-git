# how-to-use-git
## 第一单元
### configuration
1. Verify your Git version : git --version
2. git config --global user.name ""
3. git	config	user.email
4. git	config	--global	core.editor	your_preferred_editor
### Initialize an empty local Git repository using
   git	init
### Commit to a Local Repository
  1. View file status using
      git	status
  2. Stage content using
      git	add
  3. Commit content using
      git	commit -m ""
  4. View the commit history using
      git	log
      git log --oneline
### Push	to	a	Remote	Repository
  1. git clone url or git remote add
  2. git push -u origin main

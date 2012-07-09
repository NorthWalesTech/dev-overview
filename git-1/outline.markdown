ACTION POINT LF - burn CDs potentially.
ACTION POINT LK - install Git onto SAW machines.
ACTION POINT RB - key signing

At beginning - split groups to one competent person per group

Target audience
Existing Git user with command line experience

1. Intro
	who everyone is
	splitting into groups of 
	learning outcomes
	expected current understanding - use version control and 'get it'
	overview of what's to come
	Pro Git - we're following it

2. Background
	why bother with DVCS? Centralised vs Distributed
	Git
	what are people using?
		Sourcetree
		GitX
		Command line - use for rest of day
		GitGui
		Netbeans/Eclipse
		XCode
		
		Serverside
		GitLite
		Territe
		SVNGit
		GitHub
		etc
		
	History of Git - go and watch linus's google talk 

3. Git basics
	Nearly everything is local 
	Three states!!
	Getting repository - init & clone
	Recording changes
		status
		adding files
		staging changes (STAGING)
		ignoring files
		viewing staged and unstaged changes
		committing
		moving files
		viewing history (GUIs), including log -p
		
GROUP SESSION 1 -> Git basics - go and do some stuff
	Stage a file but don't commit it
	Modify a different file
	
4. Undoing things	
	Amending commit
	Unstaging a staged file
	Unmodifying a modified file

5. Remotes
	Pull & Fetch
	Push
	Inspecting remote - git remote show origin
	
6. Tagging
	Listing
	Creating
		annotated
		lightweight tags
	Sharing tags

GROUP SESSION 2
	Undo the modification
	Unstage the staged file
	Amend the last commit
	Push changes
	Tag as "0.1" (only one group pushes tag)
	
Branching

Making the most of your history

Patterns

Git Flow

Additional discussion points
	Skipping staging area
	Tagging later
	Configuration, line endings
	Snapshots vs differences
	Gerrit
	SVNGit
	Git annex
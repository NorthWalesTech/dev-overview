ACTION POINT LF - burn CDs potentially.
ACTION POINT LK - install Git onto SAW machines.
ACTION POINT RB - key signing

Initial set-up - include branches and tags

At beginning - split groups to one competent person per group

Target audience
Existing Git user with command line experience

#13:00
1. Intro 10 minutes
	who everyone is
	splitting into groups of X
	learning outcomes
	expected current understanding - use version control and 'get it'
	overview of what's to come
	Pro Git - we're following it

2. Background - 10 minutes
	why bother with DVCS? Centralised vs Distributed
	Git - History of Git - go and watch linus's google talk 
		
3. Git basics 20 minutes
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
	Viewing history (GUIs), including log -p

#13:40	
GROUP SESSION 1 -> Git basics - go and do some stuff 20 minutes + 20 minute coffee break
	Stage a file but don't commit it
	Modify a different file

#14:20
4. Undoing things - 5 minutes
	Amending commit
	Unstaging a staged file
	Unmodifying a modified file

5. Remotes - 5 minutes
	Pull & Fetch
	Push
	Inspecting remote - git remote show origin
	
6. Tagging - 5 minutes
	Listing
	Creating
		annotated
		lightweight tags
	Sharing tags

#14:35
GROUP SESSION 2 - 25 minutes
	Undo the modification
	Unstage the staged file
	Amend the last commit
	Push changes
	Pulling
	
#15:00
Branching & Stashing - 30 minutes
	Local branching
	Local merging
	Conflict resolution
	Branch deletion
	Stashing
	Git Flow
	
#15:30
GROUP SESSION 3 - 30 minutes + 20 minute coffee break

#16:20
Making the most of your history - 15 minutes
	blame
	what message for this commit
	bisect

#16:35
END

Patterns

Additional discussion points
	Skipping staging area
	Tagging later
	Configuration, line endings
	Snapshots vs differences
	Gerrit
	SVNGit
	Git annex
	Unmerging changes
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

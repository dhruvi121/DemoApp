Git:

#Install Git
1. How to check if installed:
	
	- Open terminal
	- Type "git version" and check the command response.
	- If it respond with "git version 2.30.2.windows.1"

2. What are the benefits of git	
	
	a. It maintains code history (maintains version)
	b. It maintains code backup
	c. Supports multiple branch to facilate multiple environment
	d. It enables code review using Pull request.
	
	
	master > main
	
	1. new project (default branch will be main)
	2. create new "develop" branch from main
	3. create new "feature" branch from develop. lets says "feature-menu-1"
	4. Developer will push code to "feature-menu-1"
	5. Developer will raise PR to merge code into develop.
	6. Once PR is approved, the changes will be merged to develop.
	7. TL will create release branch for UAT. let says "release/v1.0"
	8. If QA raise any in UAT, create new branch from release and "hotfix/v1.0" and raise PR once needed to be release into UAT.
	9. If UAT is passed, create PR to merge changes into main. Also, needed to merge changes to develop branch. 
	10. Once changes are merged into main, production build will be released.
	
	
	11. 
	
	feature/1
	
	
	
			
			develop+1
			
			release+1
					
				hotfix
			
			main	
                hotfix			
			
			feature-new-menu
			
			
			
			Modified for release
# :hammer_and_wrench: :octocat:	SofHarDevOps4BioMedEng: 
# Hands-on Workshop on Software and Hardware Developer Operations for Biomedical Engineers

## Workshop
### Aims  
The aim of this workshop is to provide an introduction to the GitHub toolkits to manage the development of software and hardware projects for biomedical engineers.  

### Audience
This workshop is targeted to persons with little to none experience with GitHub tools. However, intermediate and advance users might also find the topics of interests.

### Dates and times
22 to 26 August 2022! (Exact days to be confirmed)

### Instructor(s)
Miguel, etc 


### Prerequisites  
* Create GitHub account: https://github.com/  
* Terminal applications: [Git BASH](https://gitforwindows.org) for windows users and a terminal for mac and Linux users.  
* Setting up Setting up [SSH keys](tools/ssh)
* Clone this repo:
```
mkdir -p $HOME/repositories/ && cd $HOME/repositories/ ## suggested path
git clone git@github.com:KCL-BMEIS/SofHarDevOps4BioMedEng.git
```

### Content
1. Introduction to GitHub 
	* Version control 
	* Git
		* The Good 
		* The Bad 
	* The concepts  
		* Commits 
		* Graphs 
		* Branches / Tags 
		* Detaching 
		* Conflicts 
		* Rebasing 
		* Merging 
		* Cherry picking 

2. Project management  
	* Project  
	* Milestones 
	* Labels 
	* Discussions 
	* Wikis  
	* repository forks and what they are for (ie. allowing outside users to propose PRs without being collaborators on the original repo)

3. Continous Integration
	* Actions 
	* doing code releases through Github and 
	* triggering actions to do deployment (eg. uploading to PyPI for Python), 
	* other continuous integration tasks such as testing before PRs can be accepted 

4. Standards
	* Software Testing and validation (IEC 62305) 
	* Medical Device Software (IEC 60601)
	* Good machine learning practices by FDA

5. Exercises 
	* doing PRs in Github and what the protocol for that should be for a small team, 
	* PRs between forks, 

6. Software/Hardware projects
	* Version control for CAD files (pcbs, stls, others) 
	* Markdown  
	* CHANGELOGs 
	* Jupyter notebook features 
	* Jupyterlab 
	* Projects combining software/hardware 
		* https://github.com/nasa-jpl/open-source-rover  
		* https://github.com/NVIDIA-AI-IOT/jetbot  


### References 
* GitAhead to visualise what's going on and prevent some patterns of error 
* Git cheat sheet: https://education.github.com/git-cheat-sheet-education.pdf : a quick and easy to reference document on the most common git commands. [by RS] 
* Git "choose your own adventure": http://sethrobertson.github.io/GitFixUm/fixup.html. Essentially it asks a series of questions and then tells you the combination of git commands to fix whatever you need. I find it useful when you have done something particularly stupid (say pushed to remote when you did not mean to). [by RS] 
* Tutorials  
	* https://lab.github.com/githubtraining/first-day-on-github   
	* https://lab.github.com/githubtraining/introduction-to-github  
	* https://lab.github.com/githubtraining/first-day-on-github 
	* http://sethrobertson.github.io/GitFixUm/fixup.html 
* Onshape and gihub: https://forum.onshape.com/discussion/14327/making-onshape-document-available-on-github 
* GitFlow concepts (https://www.atlassian.com/git/tutorials/comparing-workflows/gitflow-workflow) [by EK]  

## Reproducibility, replicability and trust in science 2022

### Abstract 
[See submitted abstract](docs/abstract-to-rrts2022)

## References
https://coursesandconferences.wellcomeconnectingscience.org/event/reproducibility-replicability-and-trust-in-science-20220907


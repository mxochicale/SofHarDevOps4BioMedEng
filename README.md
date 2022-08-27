<h1 align="center">
:hammer_and_wrench: :octocat:	SofHarDevOps4BioMedEng: 

Hands-on Workshop on Software and Hardware Developer Operations for Biomedical Engineers
</h1>
<div align="center">
E. Kerfoot and M. Xochicale     

2nd conference on Reproducibility, replicability and trust in science 2022   
Cambridge, UK. 07–09 September 2022.
</div>


## Abstract 
In last decade, there has been a good response from the scientific community to adopt the full scientific replication, including code, data, and software (Peng 2011). 
However, there is a current need to adopt the best practices of fully scientific replication workflows to both software and hardware.
Recently, Diederich et al. 2022, for instance, highlighted the challenges of proper file-sharing and policies for hardware, which led Diederich et al. to suggest using guidelines of Open Source Hardware Association (OSHWA) and workshops for Open Hardware Makers as way to create more trustworthy science (Diederich2022).
Similarly, Stirling et al. 2022 proposed hardOps, hardware operations, as a way to address challenges in reproducibility for hardware, consisting on six stages: plan, design and document, prepare and verify, distributed production, physical testing, and feedback (Stirling 2022). 
Hence, following up our previous work on "open-corTeX: A framework for Continuously-integrated Open-source Reproducible TeX" (Xochicale 2020), this work presents a workshop on the best practices for Software and Hardware operations, aiming to equipping the next generation of Biomedical Engineers with appropriate skills and tools to create reproducible and trustworthy science.
The workshop contains six lessons on (1) introduction to git, GitHub, (2) project management, (3) continuous integration, (4) standards, (5) exercises and (6) examples of projects.

## Poster

[add it]

## Workshop
### Aims  
The aim of this workshop is to provide an introduction to the GitHub toolkits to manage the development of software and hardware projects for biomedical engineers.  

### Audience
This workshop is targeted to persons with little to no experience with GitHub tools. However, intermediate and advance users might also find the topics of interests.

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

## Content
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


## References 
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


## Clone repository
After generating your SSH keys as suggested [here](https://docs.github.com/en/github/authenticating-to-github/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent) (or [here](https://github.com/mxochicale/tools/blob/main/github/SSH.md) with few extra notes).
You can then clone the repository by typing (or copying) the following line in a terminal at your selected path in your machine:
```
mkdir -p $HOME/repositories/ && cd $HOME/repositories/ ## suggested path
git clone git@github.com:mxochicale/SofHarDevOps4BioMedEng.git
```

## References
https://coursesandconferences.wellcomeconnectingscience.org/event/reproducibility-replicability-and-trust-in-science-20220907


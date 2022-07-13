# :hammer_and_wrench: :octocat:	SofHarDevOps4BiomedicalEng: Hands-on Workshop on Software and Hardware Developer Operations for Biomedical Engineers

## Workshops
### Aims  
The aim of this workshop is to provide an introduction to the GitHub toolkits to manage the development of software and hardware projects for biomedical engineers.  

### Audience
This workshop is targeted to persons with little to none experience with GitHub tools. However, intermediate and advance users might also find the topics of interests.

### Dates
Late late August

### Instructorsr(s)
Miguel Xochicale,


### Prerequisites  
* Create GitHub account: https://github.com/  
* Ready to use terminal applications: [Git BASH](https://gitforwindows.org) for windows users and a terminal for mac and Linux users.  
* Setting up Setting up [SSH keys](tools/ssh)

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
	* repository forks and what they are for (ie. allowing outside users to propose PRs without being collaborators on the original repo), 

3. Continous Integration
	* Actions 
	* doing code releases through Github and 
	* triggering actions to do deployment (eg. uploading to PyPI for Python), 
	* other continuous integration tasks such as testing before PRs can be accepted 

4. Standards
	* IEC 62305 - Testing and validation
	* Good machine learning practices by FDA
	* Medical Hardware  

5. Exercises 
	* doing PRs in Github and what the protocol for that should be for a small team, 
	* PRs between forks, 

6. Software/Hardware projects
	* Version control for CAD files (pcbs, stls, others) 
	* Markdown  
	* CHANGELOGs 
	* Jupyter notebook features 
	* Jupyterlab - it helps prevent some of the more common errors as well as just being convenient if Jupyter is something you're standardising on. 
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
* GitFlow concepts (https://www.atlassian.com/git/tutorials/comparing-workflows/gitflow-workflow) by [EK]  

## Abstract to reproducibility-replicability-and-trust-in-science-20220907
Since the publication of the spectrum of reproducubility by Roger Peng in December 2011, there has been a good response from the scientific community to adapt the full scientific replication, including code, data and software \cite{peng2011}. 
However, there is a current need to adapt the best practices of fully scientific replication workflows to the combination of software and hardware and hardware itself.
Diederich \textit{et al.} \cite{Diederich2022}, for instance, highlighted the challenges of proper file-sharing and policies for hardware, leading authors to propose the use of guidelines like OSHWA and workshops for Open Hardware Makers as way to create more trustworthy science. 
Similarly, Stirling et al. \cite{stirling2022} proposed hardOps, hardware operations, as way to address challenges in reproducibility for hardware, consisting on six stages: plan, design and document, prepare and verify, distributed production, physical testing, and feedback. 
Following up previous our work on "open-corTeX: A framework for Continuously-integrated Open-source Reproducible TeX"
\cite{xochicale2020}, this work presents a workshop for the best practices for Software and Hardware operations, aiming to train the next generation of Biomedical Engineers.
The workshops contains topics on (1) introduction to git, github, (2) project management, (3) continues integration, (4) standards,(5) exercises and (6) examples of projects following good practices.
The resources for the workshop are available at https://github.com/mxochicale/SofHarDevOps4BiomedicalEng.

## References
https://coursesandconferences.wellcomeconnectingscience.org/event/reproducibility-replicability-and-trust-in-science-20220907


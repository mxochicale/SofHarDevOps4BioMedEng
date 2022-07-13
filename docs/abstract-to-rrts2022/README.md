# Abstract for Reproducibility, Replicability and Trust in Science 2022

## Submitted abstract
Since the publication of the spectrum of reproducubility by Roger Peng in December 2011, there has been a good response from the scientific community to adapt the full scientific replication, including code, data and software (peng et al. 2011). However, there is a current need to adapt the best practices of fully scientific replication workflows to the combination of software and hardware and hardware itself.
Diederich et al. 2022, for instance, highlighted the challenges of proper file-sharing and policies for hardware, leading authors to propose the use of guidelines like OSHWA and workshops for Open Hardware Makers as way to create more trustworthy science. 
Similarly, Stirling et al. 2022 proposed hardOps, hardware operations, as way to address challenges in reproducibility for hardware, consisting on six stages: plan, design and document, prepare and verify, distributed production, physical testing, and feedback. 
Following up previous our work on "open-corTeX: A framework for Continuously-integrated Open-source Reproducible TeX" (Xochicale 2020), this work presents a workshop for the best practices for Software and Hardware operations, aiming to train the next generation of Biomedical Engineers.
The workshops contains topics on (1) introduction to git, github, (2) project management, (3) continues integration, (4) standards,(5) exercises and (6) examples of projects following good practices.
The resources for the workshop are available at https://github.com/mxochicale/SofHarDevOps4BiomedicalEng

## OVERLEAF: "Anyone with this link can edit this project"
https://www.overleaf.com/2673429979cmyzgqwvxhdj

## Building tex abstract with:

### (a) Github Actions
#### Setting it up
1. Add `shh-rsa` key in https://github.com/settings/keys following [the documentation](https://help.github.com/en/github/authenticating-to-github/adding-a-new-ssh-key-to-your-github-account) in github.

2. Create a new secret variable called `DEPLOY_KEY` in 
https://github.com/mxochicale/rrts2020/settings/secrets 

Where the value is taken from `id_rsa` with 
`vim ~/.ssh/id_rsa` which looks like:  
```
-----BEGIN RSA PRIVATE KEY-----
...
-----END RSA PRIVATE KEY-----
```

3. Create a gh-pages branch for the pdf files [(see more)](https://www.freecodecamp.org/forum/t/push-a-new-local-branch-to-a-remote-git-repository-and-track-it-too/13222).
```
git checkout -b pdf
rm -rf * ~.git
git commit -m 'clean pdf branch'
git push origin pdf
```

4. Create github action workflow
* Create `.github/workflows/main.yml`
* Setting up variables for pdf documents and keys in [main.yml](../.github/workflows/main.yml)
* Then: do git add, commit and push origin master.


### (b) Local build
#### build LaTeX projet
```
make
```
#### clean LaTeX project
```
make clean
```

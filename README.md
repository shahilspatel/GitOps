<h1>GitOps - Deploy to Kubernetes using Jenkins Github Pipeline</h1>


<h2>Description</h2>
Project consists of an application with a repository in GitHub with a app.py file  for the Kubernetes base code and a deployment.yaml file for Kubternetes manifest files. When the code is pushed to GitHub, a Jenkins job, buildimage, will be triggered to build a Docker container image hosted on DockerHub. After this, the Jenkins job will then trigger another Jenkins job, updatemanifest, which will update the image in the deployment.yaml in GitHub. ArgoCD will detect the manifest file change and automatically deploy the new deployment.yaml file to Kubernetes cluster.

GitOps vs. DevOps:
- Periodically syncs the running Kubernetes cluster with the desired state in Git Repo
- Increased security due to CD and CD permissions being separated and less number of components
- DevOps is necessary to deploy a Kubernetes cluster and Continuous Integration.
<br />


<h2>Languages and Utilities Used</h2>

- <b>AWS</b> 
- <b>Kubernetes</b>
- <b>Jenkins</b>
- <b>DockerHub</b>
- <b>ArgoCD</b>

<h2>Environments Used </h2>

- <b>Windows 10</b> (21H2)

<h2>Program walk-through:</h2>

<p align="center">
Launch the utility: <br/>
<img src="https://i.imgur.com/62TgaWL.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Select the disk:  <br/>
<img src="https://i.imgur.com/tcTyMUE.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Enter the number of passes: <br/>
<img src="https://i.imgur.com/nCIbXbg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Confirm your selection:  <br/>
<img src="https://i.imgur.com/cdFHBiU.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Wait for process to complete (may take some time):  <br/>
<img src="https://i.imgur.com/JL945Ga.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Sanitization complete:  <br/>
<img src="https://i.imgur.com/K71yaM2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Observe the wiped disk:  <br/>
<img src="https://i.imgur.com/AeZkvFQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>

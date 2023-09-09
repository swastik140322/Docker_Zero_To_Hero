# Docker_Zero_To_Hero
Quick setup — if you’ve done this kind of thing before
or	
https://github.com/swastik140322/Docker_Zero_To_Hero.git
Get started by creating a new file or uploading an existing file. We recommend every repository include a README, LICENSE, and .gitignore.

…or create a new repository on the command line
echo "# Docker_Zero_To_Hero" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/swastik140322/Docker_Zero_To_Hero.git
git push -u origin main
…or push an existing repository from the command line
git remote add origin https://github.com/swastik140322/Docker_Zero_To_Hero.git
git branch -M main
git push -u origin main
…or import code from another repository
You can initialize this repository with code from a Subversion, Mercurial, or TFS project.

Day 23
Containers: 
     Introduction
     Docker 
     Buildah
  Virtualization -- Logically Separation of HW Resources
  why virtualization term came in the resources utilization? This is because of the waste of HW resources at server level
  on an organization level and a lot of server deployed.  
  Two major point in virtulization : Hypervisor and Virtual Machine
  Dcoker is a package which contains application, Libraries and System dependencies
  Snapshot  -- 1 to 3 Gb 
  Container 100MB to 500 MB in Size very minimal 
  Very light weight in nature
  Why Docker is so popular
  command containers -> DockerFile --> Docker Engine --> image --> container
  Docker LifeCycle:  DockerFile --> Build --> image --> run --> Container
  Docker --> Docker Engine --> Single Point of Failure (SPOF). If Docker engine fails then all container will stopped.
  Buildah is solution for Docker Container 

  Day 24
  
  
  

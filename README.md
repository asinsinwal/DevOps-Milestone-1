# CSC-519-DevOps-Project-Milestone I

## Team Details:

| Team Member             | Unity ID      | 
| ------------------------|:-------------:| 
| Rahul Daga              | rndaga        | 
| Omkar Joshi             | onjoshi       |  
| Animesh Sinsinwal       | assinsin      |   
| Sneha Kulkarni          | skkulkar      |



## Ansible Scripts:

1. The ansible script for deploying Checkbox.io on Ubuntu 14.04 server is contained in the file [trusty.yml]()
2. The ansible script for deploying iTrust is contained in the file [test.yml]()

## Screencast:

Here is a link to our [screencast]()


## Experiences and issues faced while setting up the system:

#### iTrust
* Credentials for iTrust: 
iTrust requires credentials to even clone the repository. We had to handle this issue separately because we could not put these in any of the files either. Thus, we had to take the credentials through an appropriate channel and handle all the files accordingly.Since, there is no module readily avaialble to carry out these tasks, this was a major issue that took considerable amount of time to solve.

* iTrust has too many dependencies. This required significant amount of research and we invested time in setting up the   dependencies appropriately.

* The iTrust documentation has been written in such a way that it is from an end user's perspective, rather than of being of much help to a developer. Thus, we had to find command line modules for all the functionalities.


#### Setting up a Virtual Machine within a Virtual Machine
* There is not enough documentation for hosting a virtual machine inside another virtual machine. This was an obstacle too.

* Since we are hosting a Virtual Machine within a Virtual Machine, we face memory provisioning issues as well.

* Different version of Ubuntu have different requirements. We had to modify ansible scripts accordingly to handle the issues faced due to this.



* Making all the ansible tasks idempotent was a big challenge as a lot of tasks required executing direct shell commands. We have thus, put in efforts to ensure that our tasks are idempotent as far as possible by avoiding using modules like the shell module and so on.



## Contribution:


| Tasks                                                                              | Performed By           | 
| -----------------------------------------------------------------------------------|:----------------------:| 
| 1. Ansible scripts for Checkbox.io deployment                                      | Sneha Kulkarni         | 
| 2. Ansible scripts for iTrust deployment                                           | Animesh Sinsinwal      |  
| 3. Jenkins automation upto post-build action                                       | Omkar Joshi            |   
| 4. Jenkins automation post-build action onwards, setting up a VM inside a VM       | Rahul Daga             |




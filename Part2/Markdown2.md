# Git Manual

**How to install git on windows**

Before installing Git on windows, check some system components. Your windows version needs to be Windows 8.1 or later, a minimum of 400MB of spare disk space, and have 64bit CPU. These are the bare requirements. If you have these, install git through the official website, and then download it from the installer on the computer. If you face issues installing on a workplace computer due to the company's business server, enquire on how to properly download through the business IT department.

**Using Git**

Some important aspects to consider before using Git should be the importance of different branches and organisation. Having different branches within a repository allows development to occur in different areas without affecting the main branch until approval is given. It is also important to have consistent naming conventions to keep data within a repository well organised. Looking at branches, the key thing to remember is to keep work done in lower branches, not in key branches. having all your work done entirely through main messes up work and causes diorganisation and a lack of flexibility to change in the future.

**Steps to using Git**

1) First, set up branches within the git that are needed, at minimum a main branch, staging branch, and working branch.
2) New data or data that is still in the process of being actively edited should exist in the working branch
3) When data from working is at a point that is at a desired state, push requests for the data to the staging branch should be initiated.
4) Data within the staging branch should then be configured to reach a fully desired state
5) once that state is acheived, initiate a push request to the main branch.
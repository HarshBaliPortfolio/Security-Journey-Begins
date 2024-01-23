# Overview 
If every employee can see every document within an organisation then there is no confidentiality within the organisation. Therefore, regardless of the type of an organisation, implementation of security concepts such as: “need-to-know-basis” and “separation of duties'' is very important to protect confidentiality. Linux provides the ability to implement these security concepts through configuring file permissions. 


## Steps I took to complete the activity:
1. I examined the existing permissions on the file system using [Current File Permissions](/UpdatingFilePermissions/CurrentFilePermissions.pdf) document. 
2. Then I checked whether the permissions set on the files matches the authorization that should be given, as per the criteria. 
3. Upon finding misconfigured file permissions, I changed the permissions to authorise the appropriate users and removed any unauthorised access.
4. Finally, I documented this is [Changing File Permissions](/UpdatingFilePermissions/ChangingFilePermissions.pdf) document. 




## Case Study:
You are a security professional at a large organisation. You mainly work with their research team. Part of your job is to ensure users on this team are authorised with the appropriate permissions. This helps keep the system secure. You recently had a meeting with a research lead and have agreed on file permission criteria to keep research confidential. They have asked you to check whether the current file permissions meet the criteria and if not you are required to change them.


### File Permission Criteria:
- The organisation does not allow others to have write access to any files. 
- The research team has archived .project_x.txt, which is why it’s a hidden file. This file should not have write permissions for anyone, but the user and group should be able to read the file. 
- The files and directories in the projects directory belong to the researcher2 user. Only researcher2 should be allowed to access the drafts directory and its contents.

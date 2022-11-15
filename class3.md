# Class 3 Notes

## **1.Version Control**

-A system that allows you to track different versions of a file or set of files by tracking changes. You can rollback a file or project to an older version, which allows you to view what modifications have been made. This is a great way to resolve mistakes in files.

## **2.Centralized Version Control (CVCS)**

-This system allows for team collaboration by having a single server storing all changes and files versions that can be accessed by any client. This allows team members to know what their colleagues are doing within the files and gives administrators easier access into dividing revision privileges.

## **3.Distributed Version Control (DVCS)**

-DVCS addresses the issue of the CVCS server being the single point of failure. If a CVCS goes down or in the event of corruption on the database's hard disk, collaborators cannot work together on a file and all work would be lost. So to prevent a loss of that magnitude, a DVCS grants clients the ability to create mirrored repositories.

## **4.What is Git?**

-A free and open source software for distributed version control. It stores data in a file system composed of snapshots. When a changed version of a project is saved (commit), Git creates a snapshot of the file and stores a reference to it.^ When it comes to using Git, nearly every operation is local as most of the necessary information can be found on local files. This allows you to work offline or off a VPN if need be. Which is very useful for long flights on a plane or long trip on a train. A major factor in why Git is very useful is the integrity of the software. For data management Git is able to track every single change made to any file or directory while detecting any file corruption or loss of information if the situation arises.

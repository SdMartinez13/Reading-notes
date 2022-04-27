# Class 3 Notes

>Git Tutorial: A comprehensive guide 

 - need solid understanding of Terminal

- DVCS-Distributed Version Control Systems

- Because the DVCS allows for multiple mirrored repositories, programmers working in teams can collaborate with each other in various ways to complete a joint project, which enables the use of various simultaneous workflows.

>Snapshots

- Git is a DVCS that stores data in a file system made up of snapshots. Each time you save a changed version of your project — called commit — Git creates a snapshot of the file and stores a reference to it. If the file has not changed, Git only stores a reference to the already-stored identical version of it.

>Local Operations

- Git mostly relies on local operations because most necessary information can be found in local resources. This allows for process expediency because a project’s history resides on the local disk, eliminating the need to fetch history information from the server, and allowing one to continue work on a project even when not online or on a VPN.

>Tracking Changes

- Every single change applied to any file or directory is tracked by Git. And, as the gatekeeper, Git will always detect file corruption or loss of information in transit.

>Loss of Data

- Git is set up to greatly minimize the possibility of irreversible damage to files, such as accidentally lost data. Git makes it extremely difficult for a snapshot of your file that is committed to be lost.

>States

- Files in Git can reside in three main states: committed, modified and staged.

>Committed

- Data is securely stored in a local database

>Modified

- File has been changed but not committed to the database


# CompleteMultipleWorkflowTasks
Adds a user interface to complete multiple workflow task of same category

![complete-multiple-workflow-tasks](https://user-images.githubusercontent.com/42966709/45804241-2fc27b80-bcd9-11e8-846f-a8646f353029.gif)

How it works:
Completion of Multiple Workflow Tasks is easier for users because of  ItemType Action “Process Workflow Tasks” that allows users to vote/delegate/refuse multiple tasks of same category. This functionality allows users to enhance voting facility provided by Aras and save users time and work efficiently. 

Project Details:

Built Using: Aras 11.0 SP12

Browsers Tested: Microsoft Edge, Google Chrome 68

Installation:

Important - Always back up your code tree and database before applying an import package or code tree patch!

Pre-requisites:
1.	Aras Innovator installed (version 11.0 SP12 preferred)
2.	Aras Package Import tool

Installation Steps:
1.	Backup your database and store the BAK file in a safe place.
2.	Open up the Aras Package Import tool.
3.	Enter your login credentials and click Login
o	Note: You must login as root for the package import to succeed!
4.	Enter the package name in the TargetRelease field.
o	Optional: Enter a description in the Description field.
5.	Enter the path to your local ..\ CompletionMultipleWorkflowTasks\imports.mf file in the Manifest File field.
6.	Select CompletionMultipleWorkflowTasks in the Available for Import field.
7.	Select Type = Merge and Mode = Thorough Mode.
8.	Click Import in the top left corner.
9.	Close the Aras Package Import tool.
10.	Locate InBasket-VoteDialog.aspx file at Client\scripts\InBasket\ For Example: “C:\Program Files (x86)\Aras11SP12\Innovator\Innovator\Client\scripts\InBasket\”
11. Replace this file with newly downloaded file InBasket-VoteDialog.aspx

Usage:
1.	Log in to Aras.
2.	Navigate to My Inbasket
3.	Select multiple Workflow Tasks of same category. Right-click and use 'Process Workflow Tasks' action.
4.	Vote Dialog will appear with the details of the first Workflow Task and at the background all other selected tasks will be processed with the same vote.

Contributing
1.	Fork it!
2.	Create your feature branch: git checkout -b my-new-feature
3.	Commit your changes: git commit -am 'Add some feature'
4.	Push to the branch: git push origin my-new-feature
5.	Submit a pull request
For more information on contributing to this project, another Plural Labs project, or any Plural Community project, shoot us an email at info@pluraltechnology.com.


Credits
Complete Multiple Workflow Tasks created by Ajinkya Gaikwad from Plural Technology Private Limited
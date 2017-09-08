# COMP6001 17B Swift Report


## Detailed Plan
In this report we will discuss the plan for our Swift Timesheet Application. The Swift Timesheet Application will be a mobile app for the iPhone device specifically. The goal of the application is to produce a detailed timesheet for the scanned or searched object, for example you will have the capability to scan or input a room number or a student identification card and be produced with a timesheet display on the mobile device. The Swift Timesheet Application will utilize some builtin functionality of iOS 11 to scan the barcode for the student identification card and scan the room number, the Application will also utilize network capabilities to talk to an API which will store and maintain student, room and timesheet information. With these tools and technologies combined the application will be able to produce accurate timesheets that can be presented to the user in real time.

## Wire-Frames

### Landing Page
_coming_

### Timesheet Edit Page
_coming_

### Timesheet Display Page
_coming_

### Scan Pages
_coming_

### Search Pages
_coming_


## Tools Used

### Slack
_coming_

### Trello
We have decided to use Trello as our project manangement system because it is most familiar and utilizes our needs collectively. Within the team there is experience using Trello so it was the first application considered, another application for a project management system considered was Github Projects, this was dismissed as it appeared less interactive then the original option Trello which is customizable with cats as the main theme. Trello also has Github interaction which allows Github repositories to become linked to the cards and tasks which gives us insight into our Github project and branch at hand. Trello also has an interactive mobile application where we can view/update/delete cards on the fly, which is handy for on the go updating.

### Github 
 **GitHub** will be used as our online Version Control Distribution Service. An open source platform with the largest community of software developers currently with 20 million users.
  
>>‘Allows an artist’s to be free of  mundane and repetitive tasks’, can build on a previous version.' (IBM, 2016)

We have a set of microservices and mesh applications combined for our app functionality. Composable services to aid in the design and development of our iOS Timetable App. GitHub enables each team member to work remotely working on a copy of the repository. 
Our team will be able to; clone and work on the project (using XCode, as detailed by Cody); pull requests, will alert Team Leader (Matt) to review the changes;  commit code; merge with main repository multiple times during development, for each build.  Issues are discussion threads. In a tab where bugs can be reported, requests made, or comments, then alert team of issues.  I.e., if a developer found an issue with the Camera Input (as detailed by Ashton) the team would then be notified and the issue can be reviewed.

GitHub has been chosen over the similar service Bitbucket, as it (GitHub) offers issue tracking and links into Slack (our communication tool as, detailed by Geoff), and more importantly links into Trello (Project Management platform tool in use, as detailed by Matt).   

GitHub utilizes Markdown a requirement for this project, which will benefit this collaborative work report as it displays in HTML for ease of reference and quick viewability. Catering to the process of agile development. GitHub is an essential tool to work collaboratively, track who made changes. 
 
The combination of tools we have chosen ensures we can develop our Timetable application over days instead of weeks, with the ability to communicate, see work flows, to efficiently produce a quality iOS mobile software application in Apple's Swift programming langauge.
 
Please view my personal journal report for in-depth explanation, details of features, definition and references. 

### XCode
_coming_

### Camera Input
We decided to use the phone's built in camera to scan the barcode on a student's ID card, rather than just entering their ID number into a text box or something like that. Of course, we do have an option to just enter the number in case the card isn't scanning or the student doesn't have one, but we wanted to do something a little bit more interesting for our main idea. We thought that using the camera's input to scan the barcode would be a good idea as it means the student doesn't have to remember (or even know) their ID number or moodle login details. Currently a student has to log in to moodle to check their timetable which is very slow and inefficient because you have to go through several different pages and menus to get to the timetable. We thought that being able to just point your phone at your ID card and have your timetable shown instantly would be much quicker and more efficient. We also thought that using a camera input would be a good experiment to try as none of us had really worked with camera input before, and iOS/swift have built in functions for scanning both QR codes and regular barcodes. We thought it would be an interesting experiment to use it and see how it would be implemented in a real-world situation.


## Delegated Roles

### Matt's Role
_coming_

### Geoff's Role
_coming_

### Ashton's Role
Since we were wanting to use the phone's camera to scan the ID cards, Ashton was assigned to work on figuring out how to use and display the camera input, and use it to detect and scan a barcode on the cards. Originally we discussed using ARKit to achieve this, however we realised that this was actually unneccessary for just a barcode scanner. Ashton did some research and discovered that iOS and swift actually have QR code and barcode reading supported natively by the camera, so he has looked into how to use that and will be using it in our app to scan the barcodes on the student ID's. 

### Cody's Role
_coming_

### Amber's Role
_coming_

Welcome to MarkUs
=================

MarkUs (pronounced "mark us") is an open-source tool which recreates the ease
and flexibility of grading assignments with pen on paper, within a web
application. Designed to support programming assignments, students may submit
their work through the web interface or through a version control system. Students
can form groups to collaborate on assignments. Instructors add marking schemes,
assign graders to students and then later release the marks to the students. The
graders can view the students submissions, fill in the marking schemes, and annotate
the students work. MarkUs facilitates much of the administrative work of setting
up and grading an assignment.

MarkUs is written using Ruby on Rails, and uses Subversion to store the student submissions. MarkUs
is the successor to the OLM project, an earlier grading tool.


## MarkUs Users

- [User Guide](UserGuide)
  - [Instructor Guide](Doc_Admin)
  - [Grader Guide](Doc_Grader)
  - [Student Guide](Doc_Student)
  - [RESTful API](RESTfulApiDocumentation)

Users may also find the [Sandbox](http://www.demo.markusproject.org/) useful.


## Developer Resources

If you are interested in contributing to MarkUs, there is lots of information below to help you get set up. Please help us keep this documentation up to date!

The [Developer's Blog](http://blog.markusproject.org) has quite a few useful posts to help you get started or understand design decisions that were made along the way. It also includes status reports from various terms.

### Project communication:

- IRC Channel: #markus on irc.freenode.net
  - [Logs of the channel](http://www.markusproject.org/irc/) are also available.
- Mailing list address:<markus-dev@cs.toronto.edu>
  - Mailing list archive at [marc.info](http://marc.info/?l=markus-dev&r=1&w=2)

Most of the low-level technical discussion takes place on the [Issue list](https://github.com/MarkUsProject/Markus/issues) and in [Code Reviews](https://github.com/MarkUsProject/Markus/pulls). There is a [guide to creating MarkUs Code Reviews](HowToCodeReview).


- Git Resources:
  - [MarkUs and Git](GitHowTo)
  - [A Git Tutorial](http://library.edgecase.com/git_immersion/index.html)
  - [Progit Book](http://progit.org/book)
  - [Gitref.org](http://gitref.org)
  - [Git Backend Wiki](GitBackEnd)

- [Issue Labels](LabelsWhatTheyMean)

- [Updating the Wiki](WikiUpdate)

<!-- TODO Modify User Guide link -->


## MarkUs Developer Installation Guides

### GNU/Linux
- [Setting up a development environment on GNU/Linux](InstallationGnuLinux)

### Mac OS X
- We have not been able to get the subversion bindings compiling on Mac at all, so you should use [Vagrant](SettingUpVagrantEnvironment) or a straight VM.

### Windows

We have never had any success installing MarkUs on Windows.  

You have three options if your primary environment is Windows:

- Use [Vagrant](SettingUpVagrantEnvironment)
- Use a Linux VM and follow the [setup instructions](InstallationGnuLinux) for Linux
- Set up your machine to dual boot to Linux.

Note: In Fall 2014, students had problems using Vagrant with Windows, but we have also seen it work well with Vagrant.  The problems with Vagrant and Windows might be related to permissions issues sharing the directory between the VM and the host machine. One way to resolve this issue is to clone MarkUs on the VM, and not use the shared directory.



### Setting up the Database
- [SQLite](SettingUpSQLite)
- [MySQL](SettingUpMySQL)
- [PostgreSQL](SettingUpPostgreSQL)


## MarkUs Developer Documentation

### Project Vitals

Repository: Create a GitHub account and fork MarkUsProject/MarkUs (see GitHub help for more info).


## Screencasts

- [Student File Submission: September 2 2009](http://www.youtube.com/watch?v=ofpyaty20FQ)
- [Student Group Formation: August 17, 2009](http://www.youtube.com/watch?v=Ed_z_tHCAg8)
- [The Grader View: June 6, 2009](http://www.cs.toronto.edu/~reid/screencasts/OLM-2009-06-03.swf)
- [Flexible Marking Scheme Selection: December 1, 2009](http://www.youtube.com/watch?v=x4mbE3WBgog)
- [Flexible Marking Scheme Criterion: December 1, 2009](http://www.youtube.com/watch?v=tVkti9y91RA)
- [Notes created through the Modal dialog as an Admin: December 3, 2009](http://www.youtube.com/watch?v=eoxriy2cYW0)
- [Notes created through the Modal dialog as a TA: December 3, 2009](http://www.youtube.com/watch?v=J4r18LNDwPs)
- [Creating and editing a grade entry form as an admin: December 4, 2009](http://www.youtube.com/watch?v=r7UnaNYe2rw)
- [Notes tab: December 11, 2009](http://www.youtube.com/watch?v=IcuG6AlJfvQ)
- [Entering and releasing the marks for a grade entry form as an admin: April 4, 2010](http://www.youtube.com/watch?v=-v6eVy94pdI)


## Project Contributors
Aaron Lee, Adam Goucher, Aimen Khan, Alexander Kittelberger, Alexandre Lissy, Alex Krassikov, Alysha Kwok, Amanda Manarin, Andrew Hernandez, Andrew Louis, Angelo Maralit, Anthony Le Jallé, Anton Braverman, David Das, Arianne Dee, Benjamin Thorent, Benjamin Vialle, Bertan Guven, Brian Xu, Bryan Shen, Camille Guérin, Catherine Fawcett, Christian Jacques, Christine Yu, Christopher Jonathan, Clément Delafargue, Clément Schiano, Danesh Dadachanji, Daniel St. Jules, Daniyal Liaqat, Daryn Lam, David Liu, Diane Tam, Dina Sabie, Dylan Runkel, Ealona Shmoel, Egor Philippov, Erik Traikov, Eugene Cheung, Evan Browning, Farah Juma, Fernando Garces, Gabriel Roy-Lortie, Gillian Chesnais, Geoffrey Flores, Hanson Wu, Horatiu Halmaghi, Ian Smith, Ibrahim Shahin, Jay Parekh, Jeffrey Ling, Jeremy Merkur, Jeremy Winter, Jérôme Gazel, Jiahui Xu, Jordan Saleh, Joseph Mate, Joseph Maté, Justin Foong, Karel Kahula, Kitiya Srisukvatananan, Kurtis Schmidt, Lawrence Wu, Luke Kysow, Marc Bodmer, Marc Palermo, Mark Rada, Mélanie Gaudet, Michael Lumbroso, Mike Conley, Mike Gunderloy, Mike Stewart, Mike Wu, Misa Sakamoto, Neha Kumar, Nelle Varoquaux, Nicholas Maraston, Nicolas Bouillon, Nick Lee, Nicolas Carougeau, Noé Bedetti, Oloruntobi Ogunbiyi, Ope Akanji, Rafael Padilha, Razvan Vlaicu, Robert Burke, Samuel Gougeon, Sean Budning, Severin Gehwolf, Shenglong Gao, Shion Kashimura, Simon Lavigne-Giroux, Su Zhang, Tara Clark, Tiago Chedraoui Silva, Tianhai Hu, Valentin Roger, Veronica Wong, Victoria Mui, Victor Ivri, Vivien Suen, William Roy, Xiang Yu, Yansong Zang, Zachary Munro-Cape

**Supervisors:** Karen Reid, Morgan Magnin, Benjamin Vialle, David Liu


## Term Work

Status Reports:

- [2013](http://blog.markusproject.org/?m=2013&cat=73)
- [2012](http://blog.markusproject.org/?m=2012&cat=73)
- [2011](http://blog.markusproject.org/?m=2011&cat=73)
- [2010](http://blog.markusproject.org/?m=2010&cat=73)
- [2009](http://blog.markusproject.org/?m=2009&cat=73)


## Everything a Developer Needs to Know about Ruby, Ruby on Rails and MarkUs

- **Getting Started with Ruby, Ruby on Rails and MarkUs**

  - [Short Rails Debugging HOWTO](RailsDebugging)
  - [How to program in Ruby, Rubybook](http://ruby-doc.org/docs/ProgrammingRuby/)
  - [Rails 3.0 API](http://railsapi.com/doc/rails-v3.0.8rc1/)
  - [Rails 3.2 Guides](http://guides.rubyonrails.org/v3.2.13/)
  - [General Guide Lines to code - Code review from Mike Gunderloy](GeneralGuideLines)
  - http://apidock.com/rails
  - [Some notes from a Ruby book taken by Tara Clark](http://taraclark.wordpress.com/category/ruby-on-rails)
  - [How to use MarkUs Testing Framework](TestFramework) (still in alpha)


- **MarkUs Coding Style/Coding Practices/Rails Gotchas**

  - [Basic Guidelines for MarkUs Development](DeveloperGuidelines) (**IMPORTANT!**)
  - [How To Do a Code Review](HowToCodeReview)
  - [Rails ERB quirks](RailsERbStyle)
  - **Please document your code according to the RDoc specification**- (see [How to Use RDOC](http://rdoc.sourceforge.net/doc/))
  - [Difference between COUNT, LENGTH, and SIZE](http://blog.hasmanythrough.com/2008/2/27/count-length-size)
  - [Our Ruby/Rails testing guidelines](TestingGuidelines)
  - [Security testing guidelines](SecurityTesting)
  - [Internationalization](Internationalization)

- **MarkUs API/Test Coverage**

  - [MarkUs Ruby Doc](http://www.markusproject.org/dev/app_doc)
  - [MarkUs Test Coverage](http://www.markusproject.org/dev/test_coverage)

- **MarkUs Releases**

  - [Preparing a Release and Patch](PreparingReleaseAndPatch)

- **User Roles and Stories for MarkUs**

  - General / Constraints

    - [MarkUs is internationalized](GeneralUseCase_Internationalized)
    - [MarkUs is configurable](GeneralUseCase_Configurable)
    - [Rubrics are not allowed to change once Submissions have been collected](GeneralUseCase_NoRubricChangesAfterCollection)

    - [Instructor](Role_Instructor)

      - [Instructors can create / edit assignments](Instructor_CreateEditAssignments)
      - [Instructors can download / export files](Instructor_DownloadExportFiles)
      - [Instructors can hide students](Instructor_HideStudents)
      - [Instructors can do everything that Graders can do](Instructor_CanDoWhatGradersDo)
      - [Instructors can release / unrelease completed marking results](Instructor_ReleaseMarkingResults)
      - [Instructors can map particular students / groups to Grader_(s) for marking](Instructor_MapGradersToGroupings)
      - [Instructors can download / export a file that describes the Student / Grouping mapping to Graders](Instructor_DownloadMapGradersToGroupings)
      - [Instructors can upload a file that will do the Student /Grouping mapping to Graders](Instructor_UploadMapGradersToGroupings)
      - [Instructors can manage groups without restrictions](Instructor_ManageGroupsWithoutRestrictions)

    - [Grader](Role_Grader)

      - [Graders can easily tell which submissions are assigned to them to mark](Grader_EasyToSeeWhatToMark)
      - [Graders can view a Submission from a Student / Grouping](Grader_ViewSubmissions)
      - [Graders can view / annotate / mark a particular file from a Submission](Grader_ViewAnnotateMarkParticularFile)
      - [Graders can add annotations to particular lines of code within a Submission File](Grader_AnnotateLinesOfCode)
      - [Graders can create reusable Annotations](Grader_CreateReusableAnnotations)
      - [Graders can create short, formatted overall comments on a Submission](Grader_CreateOverallComment)
      - [Graders can view and use a Rubric for marking a Submission for an Assignment](Grader_ViewUseRubric)
      - [Graders can view a summary of marked submissions](Grader_ViewSummaryOfMarkedSubmissions)
      - [Graders can add bonuses / penalties to submissions](Grader_AddBonusesPenalties)
      - [Graders can modify the marking state of a submission result](Grader_CanModifyMarkingStatus)
      - [Graders can easily switch to the next / previous Submission for marking](Grader_CanSwitchToNextSubmission)

    - [Student](Role_Student)

      - [Students can view marks of submissions](Student_ViewMarks)
      - [Students can view annotations of marked submissions/assignments](Student_ViewAnnotations)
      - [Students can submit files for their assignments](Student_SubmitFiles)
      - [Students can view / edit submission files for assignments](Student_ViewEditFiles)

- **Database Schema**

  - AutoGenerate Database Schema
    - [View Schema Diagram](images/database_20101001.png)

  - [Questions and Answers (Old Document)](SchemaQuestions)

- **MarkUs Component Descriptions**

  - [Group / Grouping Behaviour](GroupsGrouping)
  - [Groupings and Repositories](GroupsGroupingsRepositories)
  - [Authentication and Authorization](Authentication)
  - [Annotations](Annotations)
  - [How Student Work is Graded and Re-graded ](HowGradingWorks)
  - [Submission Rules](SubmissionRules)
  - [The FilterTable Class](FilterTable)
  - [Simple Grade Entry](SimpleGradeEntry)
  - [Notes System](NotesSystem)

- **Feedback Notes**

  - [2009-05-22: Phyliss](PhylissFeedback)
  - [2009-06-22: Ryan](RyanFeedback)

- **Tips and Trick**

  - [Dropping/Rebuilding Database Quickly and Easily](DropAndRebuildDb)

- **IDE/Editor Notes**

  - [jEdit](JEdit)
  - [NetBeans](NetBeans)
  - [Aptana RadRails / Eclipse](AptanaRadRails)


## MarkUs Deployment Documents

### Installation Instructions for MarkUs using `RAILS_ENV=production`

- [Setup Instructions for MarkUs Stable (MarkUs 0.10.0)](InstallProdStable)
- [Hosting several MarkUs applications on one machine (for Production)](MultipleHosting)
- [How to use LDAP with MarkUs](LDAP)
- [How to use Phusion Passenger instead of Mongrel](ApachePassenger)

- [Old Setup Instructions for MarkUs Stable (MarkUs 0.5, 0.6, 0.7 and 0.8 branches)](InstallProdOld)

For a complete list of local wiki pages, see [TitleIndex](http://github.com/MarkUsProject/Markus/wiki/_pages).

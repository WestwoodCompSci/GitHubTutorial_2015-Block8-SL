GitHub Tutorial
===============
As an introduction to the *GitHub* ecosystem, this minimalistic repository has been created as a common, shared workspace that students can use to begin exploring and experimenting with the *GitHub* platform.

Follow the [instructions](#instructions) below to be granted access to "pull from" and "push to" this repository.

Topics
------
#### GitHub
1. Signing up at [GitHub.com][1]
2. [Joining](#join) the [WestwoodCompSci][3] Team
3. [Installing](#install) [Git][6] and/or the [GitHub Client Application][6]

#### Repositories
3. [Cloning](#clone) a Repository
4. [Committing](#commit) Changes to a Repository
5. [Creating](#create) a New Repository
6. [Forking](#fork) an Existing Repository

#### Pull Requests
7. [Submitting](#pull) a Pull Request
8. [Merging](#merge) a Pull Request

<a id="instructions"></a>Instructions
-------------------------------------
#### <a id="join"></a> Join the WestwoodCompSci Team
1. If you haven't already done so, [sign up][1] for a GitHub account.
2. Send an email to [WestwoodCompSci@gmail.com][2] with a message containing your real name and your GitHub user name.

	```code
	Please add me to the "WestwoodCompSci" organization.
	
	Real name: ____________________
	Github name: ____________________
	```

3. Once your information has been received by the WestwoodCompSci administrator (i.e., the teacher), you will be added to the [WestwoodCompSci][3] team for your class.

NOTE: Adding users to teams is a manual process that must be done by hand. Please be patient until the team administrator has a chance to add your account, at which point, you'll receive a notification indicating that you can continue with the tutorial.

--

#### <a id="install"></a> Install the GitHub Client Application
1. If you do not already have the GitHub client application installed on your computer, you will need to download one (e.g., [GitHub for Windows][4] or [GitHub for Mac][5]) and possibly [Git][6] (depending on your OS). Follow the [detailed instructions][6] for setting up Git for your specific platform.
2. Launch your GitHub client application and enter the login credentials for your GitHub account.

--

#### <a id="clone"></a> Clone a Repository
1. Make sure that your GitHub account has been added to the [WestwoodCompSci team][7] before continuing.
2. Launch the GitHub client application.
3. Click the `+` sign in the upper left corner of the application.
4. Select the `Clone` tab.
5. Select the "WestwoodCompSci" repository for your particular class/block and click on the [Clone Repository] button.
6. Browse to and select an appropriate location on your system where you would like to store a local copy of the project repository. If on a school computer, select/create a folder on your H: drive. If on your personal computer, select/create a folder where you normally store the documents that you create.
7. You now have a full, editable copy of the entire project repository stored locally on your computer that can be synced with the online repository stored remotely at [GitHub.com][1]. Any changes you make to these files can be "pushed" to and merged with the master repository on the server and any changes to the repository can be "pulled" from the server to update your copy.

--

#### <a id="commit"></a> Commit Changes to a Repository
1. Navigate to the folder on your local drive where you stored the repository.
2. Create a text file containing a _simple question_ of your choice and save it with your name (e.g. `JohnDoe.txt`).

	```
	What is your favorite movie?
	```
3. Launch the GitHub client application.
4. Select this repository from the list on the left and click on the button to show the uncommitted `Changes` that have been made locally.
4. In the `Summary` field, enter a brief statement of the change you've made (e.g. "Added JohnDoe.txt").
5. In the `Description` field, you can enter a lengthier, more detailed description of the changes you are making to the repo. While the description is optional, it is strongly recommended when you are making more extensive changes to the project, especially when multiple files are involved.
6. Commit and sync your changes to the online repository.
	+ **Windows:** _Click the `Commit` button to assert that these changes should be made to the repo. Next, click `Sync` in the upper right corner to initiate the sync between the remote and local copies of the repo._
	+ **Mac:** _Click the `Commit and Sync master` button to assert that these changes should be made and to initiate the sync between the remote and local copies of the repo._

	During the sync process, your changes will be _pushed_ to the GitHub server and any changes that other users might have made will be _pulled_ down from the server.
7. Navigate back to the folder on your local drive where you stored the repository.
8. Open any text file that some other user has created. Append your answer to their question at the end of the file and save the file (i.e., `File -> Save`).
9. Commit and sync the latest changes as before using the GitHub client. Be sure to include a statement of your changes in the `Summary` field.

**NOTE:** _Merge conflicts_ can occur when changes committed by one user overlap with proposed changes made by another user. For example, consider the sequence of events in the following scenario:

```
1. Adam syncs the repo, downloading the file "foo.txt".
2. Betty syncs the repo, downloading the file "foo.txt".
3. Adam edits the file "foo.txt".
4. Adam commits his changes, uploading his edited version of "foo.txt" to the repo.
5. Betty edits the file "foo.txt".
4. Betty commits her changes, attempting to upload her edited version of "foo.txt" to the repo.
5. A merge conflict occurs!
```

In the example above, because she synced _before_ Adam's commit, Betty's edited version of "foo.txt" does not contain the changes made by Adam. But Adam's version (now in the repo) does not contain the changes made by Betty. This problem can be easily resolved (and the 2 versions _merged_) if the changes do not interfere with one another. However, if Adam's changes overlap with Betty's changes, the resolution is not so straight forward and will require closer attention to manually negotiate the proposed changes between Adam and Betty.

--

#### <a id="create"></a> Create a New Repository
1.  In the GitHub client application, click the `+` sign in the upper left corner of the application.
2. Select the `Create` tab.
3. Enter `Xxxxx's Guestbook` (where `Xxxxx` is your user name) as the name for a new repository and click `Create Repository`. Note the `Local Path` where the local copy of your repository will be created.
4. In the upper right corner of the GitHub client application, click on `Publish Repository` to push the repo to your GitHub account.
5. Under `Description`, enter `My first repository`.
6. Select your own GitHub account as the location for this new repository.
7. Click `Publish` to push your initial commit to the GitHub remote server.
8. Navigate to the folder on your local drive where your local repository was created and open it.
9. Create a text file containing the following contents and save it into your repository with the name `Visitors.txt`.

	```
	Visitors:
	1) 
	2) 
	3) 
	```
10. In the GitHub client application, commit and sync your changes as before (see steps 3 - 6 of [`Commit Changes to the Repository`](#commit) above).
11. Access your account on [GitHub.com][1] and view your new repository.
12. Click the `Add a README` button to add a descriptive info page for your repository. The default `README.md` is just a plaintext file, but allows you to use [Markdown][8] syntax for simplified text formatting.

	Markdown is an extremely easy-to-use method for creating HTML-formatted text without the complexity of learning/reading/writing raw, HTML syntax. [John Gruber][9], the creator of Markdown, describes its philosophy as follows:

	```
	Readability, however, is emphasized above all else. A Markdown-formatted
	document should be publishable as-is, as plain text, without looking 
	like it’s been marked up with tags or formatting instructions.
	```
	In fact, this [README.md][10] document that you're reading right now is written entirely in Markdown.

--

#### <a id="fork"></a> Fork an Existing Repository
1. From the [WestwoodCompSci teams][11] page on [GitHub.com][1], click on any other member's account to visit their GitHub homepage.
2. Under the `Repositories` tab, click on the member's `Guestbook` repository to view its contents.
3. Click `Fork` in the upper right corner of the repository page to create your own fork of the other member's `Guestbook` and select to add it to your own account.
4.  In the GitHub client application, click the `+` sign in the upper left corner of the application.
5. Select the `Clone` tab.
6. Select the repository that you just forked and click on the `Clone Repository` button.
7. Select a location on your local hard drive where you want a copy of the forked repository to be downloaded and stored.

You now have fully separate and independent version of the original repository. If the original version on GitHub is changed in any way, your copy will no longer receive updates of those changes. Similarly, any changes you commit to your forked repository will only affect your version and will not be reflected in the original repository. If you wish your fork to be merged back with the original (including all changes you've made), you will need to submit a _pull request_ (see next section below).

--

#### <a id="pull"></a> Submit a Pull Request
1. Navigate to the folder on your local drive where your fork of another users repository is stored.
2. Open the `Visitors.txt` file and add your user name to the list of visitors. Make sure to save the file when you're done.
3. Launch the GitHub client application.
4. Commit and sync your changes as before (see steps 3 - 6 of [`Commit Changes to the Repository`](#commit)).
5. Access your account on [GitHub.com][1] and under the `Repositories` tab, click on the forked repository to view the changes you just committed.
6. Click on `Compare` link to view the difference between your fork and the original repository. GitHub shows you a `diff` of each file that has changed. In the `diff`, text that has been added to a file is highlighted in green while text that has been deleted or replaced is highlighted in red. These are the changes that you will be proposing to the owner of the original repository.
7. Click the `Create Pull Request` button to create a request asking the owner of the original reposititory to consider merging the changes from your fork with the master repository.
8. Provide a `summary` statement and a detailed `comment` explaining the changes that you are proposing.
9. Click the `Create Pull Request` button to formally submit your request.

--

#### <a id="merge"></a> Merge a Pull Request
1. Access your account on [GitHub.com][1] and under the `Repositories` tab, click on your own `Guestbook` repository that you created ealier (see [`Create a New Repository`](#create)).
2. Click on the `Pull Requests` link on the right side of the page.
3. If you have received any `Pull Requests` from other users who have forked your repository, they will be listed here.
4. For each open `Pull Request`, you can either click on the `Merge Pull Request` button to accept and perform the proposed changes or you can click on the `Close Pull Request` button to reject the proposed changes and leave your repository as is. If you choose the latter, you may provide comment to explain why you opted against making the propsed changes.

NOTE: In cases where a _merge conflict_ occurs, the pull request cannot be automatically merged by the repository owner and the conflict must be resolved manually before the merge can be performed. See "[Resolving Merge Conflicts][12]" for more information on how to handle this scenario.

--

#### Experiment with Other Repositories
1. Using the repositories you and your classmates have created throughout this tutorial, play around with the GitHub website and client application to practice working with the repository/version control system.
2. Create a new repository that contains a simple, `Hello World` project. Keep adding more and more to the project as you practice committing the changes to the repository.
3. Search the GitHub system to find interesting projects from other developers, fork their repositories, and explore/modify their contents.

##### Sample Repositories from Westwood Students/Alumni
* [Westwood Robotics][13]: Code for BEST and FRC robotics competitions
* [QuickHAC][14]: Quickly and efficiently check your grades (Yash Aggarwal, Simon Zeng, et al)
* [Entanglement][15]: Block puzzler (Shawn Wu)
* [MoveX][16]: A 2D Platforming game focused around pure movement (Young Wang)
* [FEMultiplayer][17]: Fire Emblem multiplayer application (Shawn Wu, Young Wang, Chase Terry)
* [HotSounds][17]: A drum kit for your computer (Brian Ellis)

--
######_Last Edited 3/14/2015_



[1]: https://github.com
[2]: mailto:WestwoodCompSci@gmail.com?subject=GitHub%20Request
[3]: https://github.com/WestwoodCompSci
[4]: https://windows.github.com
[5]: https://mac.github.com
[6]: https://help.github.com/articles/set-up-git/
[7]: https://github.com/orgs/WestwoodCompSci/teams
[8]: http://whatismarkdown.com/
[9]: https://daringfireball.net/projects/markdown/
[10]: README.md
[11]: https://github.com/orgs/WestwoodCompSci/teams
[12]: https://help.github.com/articles/resolving-merge-conflicts/
[13]: https://github.com/WestwoodRobotics
[14]: https://github.com/quickhac
[15]: https://github.com/chudooder/entanglement
[16]: https://github.com/jedyobidan/MoveX
[17]: https://github.com/chudooder/FEMultiplayer
[18]: https://github.com/kitchWWW/HotSounds
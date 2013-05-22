## Evernote Tools

### Daily Notes (Log)

* Creates one new note with titled "Daily Notes for YYYY-MM-DD".
* The note is created in a Notebook called "Daily Notes".
* After the note is created, additional calls will append to the note.
* Useful if used in conjunction with Drafts.


**dn**
:	Appends to Daily Notes note.

**dn+cmd**
:	Appends to Daily Notes note and opens the the note.


### Get Tools

**eni**
:	Get selected note's ID in URL form.


### Set Tools

**esu**
:	Set the selected notes' source URL to the frontmost Safari tab.


### Modify Tools

**ead**
:	Prepend selected notes' title with date stamp; append note's body with date stamp.

**ed**
:	Append selected notes' body with date stamp.

**ept**
:	Prepend selected notes' title with with query string.

### Set Tags

**ets**
:	Tag selected notes with son's name.
:	**You will need to edit this action**

**etw**
:	Tag selected notes with wife's name.
:	**You will need to edit this action**

**eto**
:	Tag selected notes with out_board_brain.

**etag**
:	Tag selected notes with a single tag.


### Log Files

NB: This is just an example of one of my actions, it's easy to duplicate.

**eaw**
:	Append to Note "Way of the Future".

### Move Selected Notes to a Notebook

NB: This is just an example of one of my actions. It's easy to duplicate.

**emcp**
:	Move the selected notes to my Commonplace notebook.

### Tag and Move Selected Notes to a Notebook

**emcs**
:	Move selected notes to Code Snippets notebook and tag them "code".

**emcs**
:	Move selected notes to CHILD_NAME's Artwork notebook and tag them "family" and "CHILD_NAME".

**emgi**
:	Move selected notes to Gift Ideas notebook and tag them "gift_idea".

**emmw**
:	Move selected notes to Mistakes notebook and tag them "word" and "definition".


## Evernote Search Tools

NB: There is more functionality than listed here:
1. Most search actions can be opened in a new window with the action modifier: cmd.
2. All Search action have optional queries. Just type the keyword a space and a query term.

**es**
:	Basic Evernote search.

**eut**
:	Notes updated today.

**euy**
:	Notes updated yesterday.

**ewr**
:	Weekly Review - All notes updated the past week.

**ect**
:	Notes created today.

**ecy**
:	Notes created yesterday.

**ec1w**
:	Notes created last week.

**ec2w**
:	Notes created two weeks ago.

**ec3w**
:	Notes created three weeks ago.

**ecl**
:	Notes with any checkboxes.

**ecl+opt**
:	Notes with unchecked checkboxes.

**epdf**
:	Notes with PDF Attachments.

**epdf+Shift**
:	Notes without PDF Attachments.

**eclip**
:	Notes containing web clippings.

**eclip+Shift**
:	Notes without web clippings.

**eshared**
:	Notes that are shared.

**eiphoto**
:	Notes with images from iPhone. (Mobile)

**eiphoto+Shift**
:	Notes without images from iPhone. (Mobile)

**emob**
:	Notes created by a mobile device.

**emob+Shift**
:	Notes not created by a mobile device.

**eapp**
:	Notes created by apps other than Evernote.

**eapp+Shift**
:	Notes not created by apps other than Evernote.

**etitle**
:	Search for notes that contain the query in the title.

**etitle+Shift**
:	Search for notes that do not contain the query in the title.

**eimg**
:	Notes that contain image attachments.

**eimg+opt**
:	Notes that contain Gif attachments.

**eimg+Shift**
:	Notes that do not contain image attachments.

### NB: The Following Actions Do Not Have a cmd Modifier.

**eaudio**
:	Notes that contain audio attachments.

**evid**
:	Notes that contain video attachments.

**eexcel**
:	Notes that contain MS Excel attachments.

**eword**
:	Notes that contain MS Word attachments.

**epp**
:	Notes that contain MS Powerpoint attachments.

### A Few Examples Regarding Tags and Notebooks

**ecml**
:	Child Medical Log. Searches on two tags: 'your_childs_name_here' and 'medical'.

**erbls**
: Reading Backlog - Security. Searches Notebook "Books to read" and tag "security".

### Evernote Templates

See [Taming the Elephant: Awesome Evernote Tips and Tricks](http://mac.tutsplus.com/tutorials/productivity/taming-the-elephant-awesome-evernote-tips-and-tricks/) for how to make templates. I'm currently rethinking my templates, but this is a very simple example of how you can trigger them with Alfred.

NB: You need to add the path to your template file in the AppleScript.

One thing to remember: the content of a note is HTML. You could make some very stylish notes if that floats your boat.

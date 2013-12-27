## Evernote Tools

### Daily Notes (Log)

* Creates one new note with titled "Daily Notes for YYYY-MM-DD".
* The note is created in a notebook called "Daily Notes".
* After the note is created, additional calls will append to the note.
* Useful if used in conjunction with Drafts.

**dn**
:  Appends to Daily Notes note.

**dn+cmd**
:  Appends to Daily Notes note and opens the the note.


### Date Stamps

* Append date stamp to note body.
* Append date stamp to note body and prepend title.

### Move and Tag Selected Notes

* Move the selected note(s) to the Filing Cabinet notebook; tags are optional.
    * +cmd adds tag *receipt*.
* Move the selected note(s) to the Commonplace notebook; tags are optional.
    * +cmd adds tag *quote*.
* Move the selected note(s) to the Gift Ideas notebook; tags are optional.
* Move the selected note(s) to the Code Snippets notebook; tagged *code*; additional tags are optional.
* Move the selected note(s) to the Mistakes notebook; tagged *definition* and *word*.

### Move to notebook

* Move selected note(s) to the How-To notebook.
* Move selected note(s) to the General Reference notebook.
* Move selected note(s) to the Timeline notebook.
* Move selected note(s) to the Inbox notebook

### Note Bits

* Get note history.
* Get note information.
* Get note link.
* Make note plain text.
* Set note's URL to the front Safari Tab.

### Operational

* Move to Tags.
* Move to Notes.
* Move to Notebooks.

### Running Lists

* An Example of how to append to a specific note.

### Tags

* Tag selected note(s) with wife's name and family.
* Tag selected note(s) with son's name and family.
* Set Tags.
   * Tags can not have spaces.
   * Tags are separated by spaces.
* Delete Tag.
   * Warning: Will also delete sub-tags.

### Titles

* Find and Replace Text in Note Title(s).
* Title case.
* Prepend Title.




## Evernote Search Tools

NB: There is more functionality than listed here:
1. Most search actions can be opened in a new window with the action modifier: cmd.
2. All Search action have optional queries. Just type the keyword a space and a query term.

**es**
:  Basic Evernote search.

**eut**
:  Notes updated today.

**euy**
:  Notes updated yesterday.

**ewr**
:  Weekly Review - All notes updated the past week.

**ect**
:  Notes created today.

**ecy**
:  Notes created yesterday.

**ec1w**
:  Notes created last week.

**ec2w**
:  Notes created two weeks ago.

**ec3w**
:  Notes created three weeks ago.

**ecl**
:  Notes with any checkboxes.

**ecl+opt**
:  Notes with unchecked checkboxes.

**epdf**
:  Notes with PDF Attachments.

**epdf+Shift**
:  Notes without PDF Attachments.

**eclip**
:  Notes containing web clippings.

**eclip+Shift**
:  Notes without web clippings.

**eshared**
:  Notes that are shared.

**eiphoto**
:  Notes with images from iPhone. (Mobile)

**eiphoto+Shift**
:  Notes without images from iPhone. (Mobile)

**emob**
:  Notes created by a mobile device.

**emob+Shift**
:  Notes not created by a mobile device.

**eapp**
:  Notes created by apps other than Evernote.

**eapp+Shift**
:  Notes not created by apps other than Evernote.

**etitle**
:  Search for notes that contain the query in the title.

**etitle+Shift**
:  Search for notes that do not contain the query in the title.

**eimg**
:  Notes that contain image attachments.

**eimg+opt**
:  Notes that contain Gif attachments.

**eimg+Shift**
:  Notes that do not contain image attachments.

### NB: The Following Actions Do Not Have a cmd Modifier.

**eaudio**
:  Notes that contain audio attachments.

**evid**
:  Notes that contain video attachments.

**eexcel**
:  Notes that contain MS Excel attachments.

**eword**
:  Notes that contain MS Word attachments.

**epp**
:  Notes that contain MS Powerpoint attachments.

### A Few Examples Regarding Tags and notebooks

**ecml**
:  Child Medical Log. Searches on two tags: 'your_childs_name_here' and 'medical'.

**erbls**
: Reading Backlog - Security. Searches notebook "Books to read" and tag "security".

### Evernote Templates

See [Taming the Elephant: Awesome Evernote Tips and Tricks](http://mac.tutsplus.com/tutorials/productivity/taming-the-elephant-awesome-evernote-tips-and-tricks/) for how to make templates. I'm currently rethinking my templates, but this is a very simple example of how you can trigger them with Alfred.

NB: You need to add the path to your template file in the AppleScript.

One thing to remember: the content of a note is HTML. You could make some very stylish notes if that floats your boat.

# The Best ID3 Tagging Tool for Podcasters

Problem =

ID3 tagging podcasts is tedious. Also, consistency looks pro, but it requries focus which could be automated and done better with a program.

I've included this 4 step series. Initial users will go through steps 1-4. Afterwards, the user's show information will be stored. Once the user's first show information is stored, when new users open the program, they will forever begin at step 2 as the information related to the show will automatically be assumed for their show.


-- Step 1 - Establishing show information (this happens initial use only, then info is stored)

User will be prompted to enter their show's information. Questions to include:
- Artist
- Album
- Year *
- Comment  **
- URL
- Show Art ***

* - Suggest user leaves year blank to set tagging info to write current
  year.
** - Suggest they include the URL of their website int the comment to
  make the content evergreen across shows
*** - Show art is a square .jpg or .png file between 500 and 3000 pixles in height/width.

NEXT STEP - Upon completion, print "Thank you, You can now start tagging." Then the screen will fade to Step 2.


-- Step 2 - Drag and Drop your .mp3 into this Window Screen

User is prompted to drag and drop their .mp3 into the window. Computer remembers
path and moves onto next screen upon verification that file is .mp3
  NOTE: If not an .mp3, just have the text wiggle a bit and do nothing

(Screenshots included)

-- Step 3 - Thank You. Episode Title?

The episode title is the only dynamic piece of information required from the user
requiring input (.mp3 aside).

I've added two screenshots here to explain the user experience as the title of the
podcast exceeds the first line of the window.

-- Step 4 - Thank You. Your Podcast has Been Tagged in Excellence.

This screen reads once the .mp3 is tagged (this should be instantaneous after the
user clicks enter)


= Establishing v0.1

This initial tool works best for podcasters who produce multiple episodes of a single show.

The hardest problems are in executing the important parts (id3 tagging info, image storing)

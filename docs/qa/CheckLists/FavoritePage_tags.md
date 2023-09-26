| №  | Description                                                                                                                                                                                                                                              | Requirement | Commentary                                                                         |
| -- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------- | ---------------------------------------------------------------------------------- |
|    | 1.1 Favorite empty opening page 11                                                                                                                                                                                                                       |             |                                                                                    |
| 1  | Text "here will be your added words as soon as you create tags and start adding favorites" is presented                                                                                                                                                  |             |                                                                                    |
| 2  | Red button "create a tag" is shown in a middle of the screen                                                                                                                                                                                             |             |                                                                                    |
| 3  | Pressing a button is leading to opening a favourites_create a tag (12) page                                                                                                                                                                              |             |                                                                                    |
| 4  | Image is the same as on model                                                                                                                                                                                                                            |             |                                                                                    |
| 5  | Above text is a signature image of stars                                                                                                                                                                                                                 |             |                                                                                    |
|    | 1.2 Favorite create a tag page 12                                                                                                                                                                                                                        |             |                                                                                    |
| 6  | Text 1 line "create a tag:" 2 line "create a tag for adding translations to favorites in a well-organized way 3 line placeholder "e.g Lesson1"<br>4 line "You can always manage your tags, renaming, adding, and deleting them in the favorites section" |             |                                                                                    |
| 7  |                                                                                                                                                                                                                                                          |             |
| 8  | Texts are in the same format as in layout, text does not go out of screen                                                                                                                                                                                |             |                                                                                    |
| 9  | Red button "create" is below all text                                                                                                                                                                                                                    |             |                                                                                    |
| 10 | Above text is a signature image of stars                                                                                                                                                                                                                 |             |                                                                                    |
| 11 | Validation? For example no # allowed                                                                                                                                                                                                                     |             | perhaps check for sql injections, max number of string [e.t](http://e.tc/).c?      |
| 12 | If this is the first tag of user, switch to 13_favourites_first_tag, else switch to page 14                                                                                                                                                              |             |                                                                                    |
|    | 1.3 First tag created 13                                                                                                                                                                                                                                 |             | here a limit on how many tags users can create?                                    |
| 13 | Text below created tag 1 line "Your first tag has been created" 2 line "Now you can add translated words to favorites using this tag"                                                                                                                    |             |                                                                                    |
| 14 | Red button "create" is below all text, when pressed leads to create a tag page (12)                                                                                                                                                                      |             |                                                                                    |
| 15 | There is no search text box                                                                                                                                                                                                                              |             |                                                                                    |
|    | 1.4 Favorites_tags standard page 14                                                                                                                                                                                                                      |             |                                                                                    |
| 16 | Chosen tag to add words to tag is highlighted by gray color                                                                                                                                                                                              |             |                                                                                    |
| 17 | Search text box is located under "Favorites"                                                                                                                                                                                                             |             |                                                                                    |
| 18 | placeholder text "Search" is written in search text box                                                                                                                                                                                                  |             |                                                                                    |
| 19 | Below search there is statistics of how many tags and translations is presented                                                                                                                                                                          |             |                                                                                    |
| 20 | To the right of a tag there is a "pencil" button,when pressed bottom sheet (14.3) appears to rename a tag                                                                                                                                                |             |                                                                                    |
| 21 | All tags have a number to the right that indicates how many words have this tag                                                                                                                                                                          |             |                                                                                    |
| 22 | Red button "create new tag" is moving down every time new tag is made and there is still space for it below                                                                                                                                              |             |                                                                                    |
| 23 | If there are too many tags to show on 1 page, red button became fixed below and scroll option appears                                                                                                                                                    |             |                                                                                    |
| 24 | Sorting option can be chosen by pressing "sort" button on top right corner", bottom sheet appears (14.1)                                                                                                                                                 |             |                                                                                    |
|    | 1.4.1 sorting                                                                                                                                                                                                                                            |             |                                                                                    |
| 25 | Image with stars that is similar to 14.1 frame                                                                                                                                                                                                           |             | Not sure about the image, no model currently. What happens when no result appears? |
| 26 | 1 String "Sort by" 4 buttons 1 "date created" 2 "date modified" 3 "A-Z" "Z-A"                                                                                                                                                                            |             |
| 27 | all sort options do what they told about                                                                                                                                                                                                                 |             |                                                                                    |
| 28 | This bottom sheet can be draw down                                                                                                                                                                                                                       |             |                                                                                    |
| 29 | Appears when sorting button is pressed                                                                                                                                                                                                                   |             |                                                                                    |
|    | 14.3 Favourites_rename                                                                                                                                                                                                                                   |             |                                                                                    |
| 30 | Appears when "pencil" button is pressed                                                                                                                                                                                                                  |             |                                                                                    |
| 31 | Image with stars above                                                                                                                                                                                                                                   |             |                                                                                    |
| 32 | 1 string "Rename a tag" text box that has in it a name of chosen tag                                                                                                                                                                                     |             |                                                                                    |
| 33 | tag name changes only if "done" button is pressed                                                                                                                                                                                                        |             |                                                                                    |
|    | 15 tags active                                                                                                                                                                                                                                           |             |                                                                                    |
| 34 | This frame activates when making a long tap on any tag                                                                                                                                                                                                   |             |                                                                                    |
| 35 | When frame activates, bottom menu appears where 4 buttons from left to right appears                                                                                                                                                                     |             |                                                                                    |
| 36 | Buttons on bottom menu are 1) Export 2) Button move to tag 3) Copy to tag 4) delete                                                                                                                                                                      |             |                                                                                    |
| 37 | When pressing "Export" button 19 bottom sheet opens up                                                                                                                                                                                                   |             |                                                                                    |
| 38 | When pressing "Move to tag" button 18 bottom sheet opens up                                                                                                                                                                                              |             |                                                                                    |
| 39 | When pressing "Copy to tag button 17 bottom sheet opens up                                                                                                                                                                                               |             |                                                                                    |
| 40 | When pressing "delete" button 16 bottom sheet opens up                                                                                                                                                                                                   |             |                                                                                    |
| 41 | The only way to stop this mode is to press "back" button at the upper left                                                                                                                                                                               |             |                                                                                    |
| 42 | From top to bottom 1) Selected "x" where x is a number of selected tags 2) Select all tags button, 3) statistics on how many tags and words are presented 4) Tags list                                                                                   |             |                                                                                    |
| 43 | Pressing select all tags button when it is not activated will select all tags                                                                                                                                                                            |             | What happens if the user manually chooses all tags? Will it activate itself?       |
| 44 | Pressing it again will ...                                                                                                                                                                                                                               |             | Will do what? Unselect all?                                                        |
| 45 | If the tag is chosen, it will be highlighted by dark blue background and a checkmark to the left of a tag will appear                                                                                                                                    |             |                                                                                    |
|    | 16 delete                                                                                                                                                                                                                                                |             |                                                                                    |
| 46 | From top 1) image of trash can 2) delete "x" selected tags with all the added translations?<br>3) red button "delete" 4) "You can restore deleted translations from the bin back to favorites within 7 days where x is number of selected tags           |             |                                                                                    |
| 47 | Pressing delete button will put all selected tags to bin                                                                                                                                                                                                 |             |                                                                                    |
| 48 | Swipe down or pressing outside bottom sheet will close it                                                                                                                                                                                                |             |                                                                                    |
| 49 | If it was closed, all tags are still selected, none tags deleted                                                                                                                                                                                         |             |                                                                                    |
| 50 | If delete button was pressed, bottom sheet goes down, deleted tags will disappear from list                                                                                                                                                              |             |                                                                                    |
| 51 | If tags were deleted, push ap notification will appear on the bottom of the screen                                                                                                                                                                       |             |                                                                                    |
| 52 | Push ap notification (16.1) text is "x tags was moved to the recycle bin" where recycle bin is underlined, and x = number of tags chosen                                                                                                                 |             |                                                                                    |
|    | 19 export_tags                                                                                                                                                                                                                                           |             |                                                                                    |
| 53 | From top 1) image of exporting page 2) Export selected tags with all the added translations"<br>3) 2 red buttons, "export in .pdf" and" export in .xlsx" 4) The file will be saved in Downloads folder                                                   |             |                                                                                    |
| 54 | Swipe down or pressing outside bottom sheet will close it                                                                                                                                                                                                |             |                                                                                    |
| 55 | If it was closed, all tags are still selected, none tags deleted                                                                                                                                                                                         |             |                                                                                    |
| 56 | If export button was pressed, bottom sheet goes down, a file will be created in chosen format with all selected tags                                                                                                                                     |             |                                                                                    |
| 57 | File is created once in downloads folder                                                                                                                                                                                                                 |             |                                                                                    |
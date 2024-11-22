# JapDic 
Version 1.0
Made by Vik

## Idea description
Idea is to retrieve data from my [quizlet form link](https://quizlet.com/pl/957743446/japanese-a1-flash-cards/). I have, and will add words there which I want to convert easily into table using python.

Simple algo desc:
1. Create list of terms
2. Retrive new terms - turns out you can export words from web page without scraping - use comma separation
3. Check if terms in the list
4. Add to list new terms
5. Extract as table new terms
6. Finish

Full link for easiness - `https://quizlet.com/pl/957743446/japanese-a1-flash-cards/`

## Possible problems now:
- [X] Get words from quizlet
- [X] Access notion page
    - [X] Mod notion page
- [X] Add table to notion page
- [X] Populate table
    - [X] get last id used in table
- [X] Add check for last created file
- [X] Option to select separator
- [-] Update date before table?
- [X] Check for duplicates
- [X] Save 
- [ ] Extract table file in folder
    - fix saving when there is pronoucing column
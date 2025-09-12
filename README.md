# MoodDiary
Mood Diary Web Page

[Webpage Link](https://emi-mii.github.io/MoodDiary/)

Project Overview and Purpose:

This “Mood Diary” is a SPA for users to log their daily mood. With its purpose being to allow for easy logging and viewing of daily mood logs, text reflection, and image upload. The purpose of the project is to create a user-friendly tool for daily emotional tracking, that also demonstrates persistent storage and accessibility.


Features and Functionality:

- Daily Entry Logging: Users can record one mood entry per day that consists of selecting their daily mood, providing a text entry for the day, and an optional image of their choice.

- Edit Entry: Users can edit existing entries in the default List view, to optionally change text, image, or mood selection. This edit mode has a distinct visual style for clarity.

- Delete Entry: Users can also delete existing entries.

- List View: Users are defaulted in the app to the List view that displays all mood diary entries in reverse chronological order, with newest entries at the top.

- Calendar View: Users have the option of switching to the Calendar view that represents days by the emoji logged. Users can optionally click on the mood emoji for that day to see the full entry.

- Persistent Storage: All entries are stored locally in the browser using localStorage, so each user maintains their own diary


Known issues or limitations:

One of the main issues or limitations is the use of local storage only, meaning entries are not synced across devices or users.


Future enhancement ideas:

One of the future enhancements that could be implemented is allowing for users to upload multiple images or even videos to their entries. Another enhancement could be allowing for users to search/filter through their entries for example by mood or keywords. Above all I think the best improvement would probably be having user entries stored in a backend database with user accounts, for entries to be synced across devices and users. This enhancement could even be expanded and allow for users to add eachother and view eachothers diary logs, even allowing them to choose what components friends can view. Asethetic changes like adding a theme, and catering the emoticons to this theme could also be implemented for a more enticing look.
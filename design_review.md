# Design Review

## Introduction
In this section, we conducted a comprehensive review of the proposed designs using an expert evaluation technique. The purpose of this review was to identify potential usability issues, assess the strengths and weaknesses of each design, and gather insights to inform the development of our final prototype.

## Evaluation Method
We chose to employ a heuristic evaluation method based on Nielsen's 10 Usability Heuristics. Each team member independently reviewed the designs and provided their findings. The heuristics we focused on include:

1. Visibility of system status
2. Match between system and the real world
3. User control and freedom
4. Consistency and standards
5. Error prevention
6. Recognition rather than recall
7. Flexibility and efficiency of use
8. Aesthetic and minimalist design
9. Help users recognize, diagnose, and recover from errors
10. Help and documentation

## Heuristic Evaluation - Completed by Felix

| Heuristic                         | Severity | Issues | Recommendation/Comments |
|-----------------------------------|----------|--------|--------------------------|
| Visibility of System Status       |     2     |   The process of adding an expense and selecting group members is not immediately apparent, requiring users to navigate and scroll through the interface.     |             Implement a clearer indication of the selected group and provide real-time feedback during the process of adding an expense. For example, a prominent display or confirmation message when a group is selected or a member is added to the expense.              |
| Match between system and the real world |     3     |   The system defaults to a manual split for expenses, which is not the typical real-world behavior where expenses are usually split equally by default. This requires additional steps from the user to adjust the splits.     |           Change the default setting to an equal split of expenses, with the option to switch to manual or percentage splits if needed. This aligns more closely with real-world expectations and reduces unnecessary user input.       |
| User control & freedom            |     2     |    Users cannot remove certain members from an expense, meaning that every member from the selected group will be involved in the expense even when not all members were part of it.    |           Allow users to deselect specific members from the expense. By default, all group members can be selected, but users should have the option to remove those not involved. This provides flexibility and ensures that expenses are accurately recorded.               |
| Consistency & standards           |     1     |    The group selection mechanism might suggest that multiple groups can be selected for a single expense, which can cause confusion and errors.    |          Make it explicit that only one group can be selected for each expense. A dropdown menu could help, but ensure it maintains the app’s aesthetic appeal. Use standard UI elements that users are familiar with to indicate single selection.     |
| Error prevention                  |     0     |        |                          |
| Recognition rather than recall    |     0    |        |                          |
| Flexibility & efficiency of use   |      1    |    Advanced users might find the process of manually splitting expenses or switching groups cumbersome.    |           Introduce shortcuts or advanced options for experienced users, or a system to save recurrent expenses.               |
| Aesthetic & minimalist design     |       1   |   The current design may become cluttered, especially when dealing with large groups with many members.     |           Maintain a minimalist design by collapsing less frequently used options and information until needed. Use visual hierarchy and whitespace to keep the interface clean and focused.       |
| Help users recover                |      0    |        |                          |
| Help & documentation              |      1    |    There is a lack of immediate help or tooltips that explain how to use certain features, which can be problematic for new users.    |           Include contextual help and tooltips that provide users with quick, relevant information about how to use various features. A comprehensive help section or user guide accessible from within the app would also be beneficial.      |


## Heuristic Evaluation - Completed by Elliott

| Heuristic                         | Severity | Issues | Recommendation/Comments |
|-----------------------------------|----------|--------|--------------------------|
| Visibility of System Status       |     2     |      Little visibility for wether members are able to be removed from groups/expenses |         create clear and intuitive buttons for removing members                 |
| Match between system and the real world |     1     |    Small changes may need to be made to interface for removing members.    |            Good use of typical flows of operations, (Create group -> Add members -> Create expense). Navigation tabs and hotbars are similarly used in other main stream apps. All language is familiar.              |
| User control & freedom            |     0     |       |            Complete freedom for user with availability to set descriptions for expenses and groups as well as uploading their own images for group profile identification. Users also have the availability to personalise and change their account name, email, username, phone number, Gender, Pronouns.             |
| Consistency & standards           |     1     |    Small issues with design consistency, for instance beveling around edges of UI cards are not the same throughout the app, font sizing needed to be more consistent and follow patterns.    |             To improve this, make button and text templates to copy throughout the wireframes.             |
| Error prevention                  |     0     |        |           All tabs have confimation requests where applicable.               |
| Recognition rather than recall    |     1     |    small things were overlooked that would affect the overall flow for a first time user    |                   follows consistent design pattern patterns, everything is easily readable for the most part, some small things such as more intuitive ways to remove members / friends bring the score up.     |
| Flexibility & efficiency of use   |     1     |      There are some small improvements to be made in the management tab, specifically the process of adding friends, group members and expenses.   |             creating more a more intuitive flow from one page to the other as well as clearer buttons in the friends tab would solve this.             |
| Aesthetic & minimalist design     |     0     |         |            colors were not overused, buttons were kept non invasive and the overall design was not cluttered              | 
| Help users recover                |     0     |       |                 users are given the oppertunity to click edit or go back to certain properties such as expenses and groups as well as pages that require you to go into.         |
| Help & documentation              |     3     |    there are no documentation or help offered for most of the app  |                     small amounts of help / documentation is offered in the log in window and some of the profile settings     |


## Heuristic Evaluation - Completed by Dillon

| Heuristic                         | Severity | Issues | Recommendation/Comments |
|-----------------------------------|----------|--------|--------------------------|
| Visibility of System Status       |          |        |                          |
| Match between system and the real world |          |        |                          |
| User control & freedom            |          |        |                          |
| Consistency & standards           |          |        |                          |
| Error prevention                  |          |        |                          |
| Recognition rather than recall    |          |        |                          |
| Flexibility & efficiency of use   |          |        |                          |
| Aesthetic & minimalist design     |          |        |                          |
| Help users recover                |          |        |                          |
| Help & documentation              |          |        |                          |
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

Task: Add an Expense

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

Task: changing group members

| Heuristic                         | Severity | Issues | Recommendation/Comments |
|-----------------------------------|----------|--------|--------------------------|
| Visibility of System Status       |    1      |    Not clear how to remove members from the group. No buttons     |       Great Visibility of what members are included in the group. When adding members there is a clear seperation between group members and non group members. Could use some clearer options for removing members.                   |
| Match between system and the real world |     1     |    The process to removing members needs to be more intuitive    |           very similar to real world examples. With small improvements to be made to the removal of members.                |
| User control & freedom            |     0     |         |        Lots of freedom, easily manueverable to different sections of the app directly from that page. also given options to edit members whether it be to remove or add them. Group members are never forced to be permanent when first created.                  |
| Consistency & standards           |     1     |   inconsistency with the type of button to add/remove members      |   could switch to using the same style for both, preferably the add method as the remove is not very intuitive and may be confusing for first time users                       |
| Error prevention                  |    0      |        |            Error prevention is handled very well, anywere that the user is required to enter in any new data they are asked whether they are sure they would like to add it in the way of a confirmation overlay              |
| Recognition rather than recall    |      1    |    small issues with design inconsistencys for buttons may cause the user to get confused or be unsure what to press to do a certain action such as the difference between adding and removing members    |            it is a small issue but easily remedied by making both buttons the same so that the user can easily recognise what to do rather than having to remember each time from what they have done in the past.              |
| Flexibility & efficiency of use   |     0     |        |                great use of efficiency and flexibility there is a clear flow through the process of edditing members in a group as well as the flexability to add new friends directly from that tab.          |
| Aesthetic & minimalist design     |     1     |        |              style mismatch between add and remove members             | could be more minimalist and by using the same method/style for the add /remove the style and flow of the task will make more sense to the user
| Help users recover                |     0     |        |           at all times the user is able to go back to the previous page                |
| Help & documentation              |      2    |   could use a dedicated help / documentation page for if the users had quiries     |          for the most part there is clear help/documentation offered througout the log in and profile building, however adding a page inside the profile offering more detailed help in how to carry out all tasks as well as any other common questions a user might have would be very helpful.                |


## Heuristic Evaluation - Completed by Dillon

Task: Create and edit a group

| Heuristic                         | Severity | Issues | Recommendation/Comments |
|-----------------------------------|----------|--------|--------------------------|
| Visibility of System Status       | 1 | The prototype shows clear titles at the top indicating the current screen/status (e.g. "Create Group", "MoneyMates") | Maintain this clarity in all parts of the app. |
| Match between system and the real world | 1 | The language used is simple and matches real-world terminology related to flatmate expenses. One minor issue is "No Expenses" label is a bit system-oriented. | Consider changing "No Expenses" to a more user-friendly message like "You have no expenses yet" |  
| User control & freedom            | 0 | The prototype has a persistent bottom navigation bar allowing easy movement between sections. There is also a clear way to exit/cancel creating a group once started by using the "Back" button. | No changes required |
| Consistency & standards           | 1 | Interface elements like buttons, icons, and layout appear consistent across screens. One inconsistency is the "Done" button to finish group creation - most apps use "Create" or "Save". | Change "Done" to "Create Group" to better align with interface conventions | 
| Error prevention                  | 2 | Currently the prototype does not show any error prevention if required fields are left blank when creating a group. | Add field validation and prevent form submission until all required details are entered |
| Recognition rather than recall    | 0 | Main actions like creating groups and expenses are visible on the home screen, minimizing need for user recall. Icons and buttons are clear and recognizable. | No changes needed |
| Flexibility & efficiency of use   | 1 | The prototype demonstrates a simple, focused design suitable for novice users. Power user shortcuts could be an enhancement for more efficient use. | Consider adding shortcuts like swipe gestures or long-press for common actions |
| Aesthetic & minimalist design     | 0 | Clean, minimal design with ample white space and only relevant content shown. Effective use of color to highlight key actions. | Ensure the design remains minimal and focused on essential elements. |
| Help users recognize, diagnose, and recover from errors | 3 | No visible error recovery options are present. The prototype does not yet demonstrate error handling, so users may get stuck if they encounter a problem. | Create helpful error messages to identify issues and suggest solutions. Provide a way to report problems within the app. |
| Help & documentation              | 3 | There is no obvious way to access help or documentation in the prototype. | Add an easily accessible help section with FAQs, tutorials and a way to contact support if needed. Consider brief intro tooltips for new users. |
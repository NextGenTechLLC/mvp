# Using Ellipsis {#using-ellipses}

The ellipsis character (…) is used in the interface for two primary reasons: informing the user of an additional required information and letting the user know text has been shortened.

## Additional Information {#additional-information}

An ellipsis should be used to let a user know that more information or a further action is required before their action can be performed. Usually this means that the user should expect a new interface element to appear such as a new window, dialog, toolbar, etc in which they must enter more information or make a selection before completing the intended action. This is an important distinction because a user should typically expect an instant action from buttons and menu items while this prepares them for an alternate behavior. More specifically, an ellipsis should be used when the associated action:

* **Requires specific input from the user.** For example, Find, Open, and Print commands all use ellipses because the user must select or input the item to find, open, or print. An easy way to remember this is to think of a question requiring and answer: Find what? Open what? Print what?
* **Is performed in a new window or dialog.** For example, Preferences, Report a Problem, and Customize Toolbar all use ellipses because they open a new window (sometimes another app) or dialog in which the user makes a selection or inputs other information. Consider that the absence of an ellipsis implies the app will handle the action immediately. This means that the app will automatically generate a report or customize its own toolbar. Using an ellipsis makes the important distinction that the user will be writing the report or selecting which toolbar items to show.
* **Warns the user of a potentially dangerous action.** For example, Log Out, Restart, and Shut Down all use ellipses because they display an alert that asks the user to confirm or cancel a potentially harmful action. Again, this is the user clicking a button or menu item that requires them to input more information or make a selection before the action is completed.

## Shortened Text {#shortened-text}

Ellipses should be used when shortening text that cannot fit in any specific place. For example, if a playlist's name is longer than the space available in the sidebar, truncate it and use an ellipsis to signify that it's been truncated. There are two ways to use an ellipsis when shortening text:

* End truncation. If the important or distinctive text is at the beginning of the string, truncate it at the end and append an ellipsis.
* Middle truncation. When the end of the text is more important or distinctive, truncate the text in the middle and replace the truncated text with an ellipsis.

If you're unsure, it's best to use middle truncation as it keeps both the beginning and end of the string in tact. It's also important that you do not ship your app with any truncated text; truncation should only be the result of a user action such as resizing a sidebar or entering custom text.

## When Not to Use Ellipsis {#when-not-to-use-ellipsis}

* In an entry's placeholder text. An ellipsis is not necessary here and adds no value.
* For a submenu item. The right arrow already indicates that this entry spawns a submenu and is not an action.

--------------------------------------

Be sure to use the actual ellipsis character (…) rather than three consecutive period (.) characters.

#### Next Page: [Naming Menu Items](/docs/human-interface-guidelines/naming-menu-items) {.text-right}
## IdeaBox

[Try it out!](https://adam-rice.github.io/IdeaBox/)

Created by [Graham Nessler](https://github.com/gness1804) and [Adam Rice](https://github.com/adam-rice).

An application to store your ideas using Javascript and jQuery as well as JSON and localStorage to persist data between sessions.

An Idea has an id, title, body, and a quality.
The id should be a unique identifier.
Title and body are free-form strings.
Quality should be one of the follow: “genius”, “plausible”, and “swill.”
By default, the idea’s “quality” should default to the lowest setting (i.e. “swill”).

* When visiting the application, the user should:
See a list of all existing ideas, including the title, body, and quality for each idea.
Ideas should appear in descending chronological order (with the most recently created idea at the top).

The text fields should be cleared and ready to accept a new idea when an idea is submitted.
The page should not reload.

Each idea in the list should have a link or button to “Delete” (or 𝗫).
Upon clicking “Delete”, the appropriate idea should be removed from the list.
The page should not reload when an idea is deleted.
The idea should be removed from localStorage. It should not re-appear on next page load.

Each idea in the list should include an “upvote” and “downvote” button.
Clicking upvote on the idea should increase its quality one notch (“swill” → “plausible”, “plausible” → “genius”).
Clicking downvote on the idea should decrease its quality one notch (“genius” → “plausible”, “plausible” → “swill”).
Incrementing a “genius” idea or decrementing a “swill” idea should have no effect.

When a user clicks the title or body of an idea in the list, that text should become an editable text field, pre-populated with the existing idea title or body.
The user should be able to “commit” their changes by pressing “Enter/Return” or by clicking outside of the text field.
If the user reloads the page, their edits will be reflected.

At the top of the idea list, include a text field labeled “Search”.
As a user types in the search box, the list of ideas should filter in real time to only display ideas whose title or body include the user’s text. The page should not reload.
Clearing the search box should restore all the ideas to the list.

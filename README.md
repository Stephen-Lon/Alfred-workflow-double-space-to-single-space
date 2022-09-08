# Alfred-workflow-double-space-to-single-space
An Alfred workflow to convert certain double spaces to single spaces in selected text

This workflow is a Universal Action which takes selected text and converts certain double spaces in the text to single spaces. You then have the choice of copying the amended text to the clipboard or simply quitting the workflow.

The conversion works as follows:

- a double space following any *word* will be automatically converted to a single space;
- a double space following any specific *character* will be converted to a single space.

The characters which will trigger conversion if followed by a double space are listed in the user configuration (so that you can change them if you wish). For example, the default configuration will ensure there is only one space following a full stop (or period). If you want two spaces following a full stop simply delete the full stop from the default user configuration (you can always reset the default configuration if you need to do so).

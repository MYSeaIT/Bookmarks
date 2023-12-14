# Site Bookmarker Project

## Overview
This project is a simple web application that allows users to bookmark their favorite sites.

## Development Process
1. Started by creating the HTML structure for the webpage in `index.html`.
2. Linked the Bootstrap and custom CSS files for styling.
3. Created the functionality to save and delete bookmarks in `script.js`.
4. Implemented form validation to ensure the user enters valid site names and URLs.
5. Tested the functionality and made adjustments as necessary.

## Encountered Errors
### Error 1: Form submission not triggering saveBookmark function
- Cause: Incorrect assignment of event listener to the form.
- Solution: Identified the issue and corrected code to properly attach the event listener.

### Error 2: Incorrect URL format not being handled
- Cause: Missing validation for URL format in `validateForm` function.
- Solution: Added regular expression validation to ensure the correct URL format.

### Error 3: Missing protocol in bookmark URL
- Cause: URLs without a protocol were not properly handled.
- Solution: Created the `addPrefix` function to prepend "http://" to URLs lacking a protocol.

### Error 4: Empty bookmarks array causing issues
- Cause: Failure to check for null value when fetching bookmarks from localStorage.
- Solution: Implemented a check for null value and initialized the bookmarks array if null.

### Additional Functionality Errors
- Issue: Deleting a bookmark does not update the displayed list.
  - Cause: Incomplete implementation of `deleteBookmark` function.
  - Solution: Modified the function to properly update the list of bookmarks after deletion.

## Conclusion
Throughout the development process, various errors were encountered and resolved, resulting in a functional and reliable web application for bookmarking favorite sites.


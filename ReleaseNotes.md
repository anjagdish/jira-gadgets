## JIRA Issues Gadget 1.2 ##

### New Features ###
  * Overall improvement of the way summary information is displayed and well as truncation of long summaries. Changed CSS in order to auto-hide part of the summary that overflows.
  * Added a pop-up tooltip that displays more information about the issue. The information displayed is: **issue key**, **type**, **status**, **resolution** and full length **summary**.

### Bug Fixes ###
  * Removed 'maxSummaryLength' user preference as it is no longer required.
  * Links on summaries did not work properly on Firefox with Redirect Remover add-on. With the summary improvements this is no longer an issue.

### Known Issues ###
  * [Issue 9](http://code.google.com/p/jira-gadgets/issues/detail?id=9) - Tooltip window may stay displayed even if mouse moves out of the area. This window will stay until the gadget is refreshed (you can set the refresh rate in user properties). If this will happen too often, you may choose to disable this feature (via user preferences), which will cause the gadget to revert back to its previous behavior. Your feedback on this issue is welcome.

## JIRA Issues Gadget 1.1 ##

### New Features ###
  * Added content refresh. The frequency of refresh is customizable. This enables the gadget to poll for updates in Google Desktop, which does not automatically refresh as Google homepage does.
  * Increased the number of displayable issues to 30. This enables to see more issues if the  user chooses to.

### Bug Fixes ###
  * Added a message to display in case if no matching issues are found.
  * Fixed a typo in CSS text-align.


## JIRA Issues Gadget 1.0 ##

### New Features ###
  * Initial implemetation, which fetches 1-10 issues from JIRA via its XML view.



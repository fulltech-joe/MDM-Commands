# MDM Commands and Scripts-
These are the commands that I will regularly build out MDM tenants (Mosyle, JAMF, etc.). It is always evolving with more commands as I create/find ways to impliment things.

## Crashplan Collect Logs

This will copy the Crashplan log folder under /Library/Logs/Crashplan to the desktop and then compress that copied folder. This does not require the user to open the Crashplan desktop app. Sometimes the app does not want to open, so this is a better solution since it does the complicated things for the user. In the future this could just compress the original log folder, but I didn't do it that way (yet) :^)

## Demote User

Sometimes having a user as an admin is a neccesary but should not be kept long term. This script will remove the admin permissions and restore the user to Standard. Just update the username variable and run as root through your MDM.

## TeamViewer ID

Run it to get the TV ID. Its easy.

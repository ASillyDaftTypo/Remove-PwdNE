# Remove-PwdNE
Mass-remove the 'Password Never Expires' option on a batch of AD accounts &amp; notify the user.
Simple script that I turned into a module instead, because hey, why not?
Does what it says on the tin: Removes the 'Password Never Expires' option from a batch of AD accounts, as specified by the input & sends a notification email to the user.
The script also changes the date the password was updated to the current date to prevent any instant-lockout issues.

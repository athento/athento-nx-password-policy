# athento-nx-password-policy
Nuxeo plugin that adds password policy restrictions when a user password is set or changed.

# Features

This plugin allows to enable password policy such as:

 * temporarily lock-out users with too many failed login attempts
 * temporarily lock-out IP addresses with too many failed login attempts
 * enforce a minimum password length
 * enforce password complexity rules
 * require a password change after a certain period
 * require a password change when a temporary password has been set, eg. when the user administrator provides passwords for (new) users.
 * allow to filter the IPs from which a user may log in.

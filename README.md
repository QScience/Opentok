OpenTok
=======

Adds video conference functionality to visualscience. Using this module one can easily create video conference rooms and send invitations to the participants from the userlist.

Find dependencies here: http://drupal.org/project/opentok

You will need to download and istall the libraries drupal module. After doing so create a /sites/all/libraries directory, and put jquery.opentok and json-js plugins there in folders named "jquery.opentok" and "json-js". Only after doing so you can enable the opentok module. 


To use the email notifications you need to enable the trigger(core)  module. After enabling it go to Structure -> Triggers, and assign "Invite Participants" action to execute when a new content is saved, and also assign "Update info for participants" action to execute when a content is updated. Both triggers are defined by node module.
# SPT-AKI-ProfileEditorHelper-Fix-3.9.4
File hosting for the botched fix, until SPT-AKI-Profile-Editor gets updated.

Warning:
Uninstaling or deleting the helper in ProfileEditor means you will have to reapply the fix.

Instructions:
1. Follow the original instructions: https://github.com/SkiTles55/SPT-AKI-Profile-Editor/blob/5ed91be35a2653bbdfca5ab5e3ae290faf19a67c/Guidelines/ModHelperENG.md
2. On step 5 you will recive a red message. Close the server.
3. Move the fix files (user folder) into your spt directory. Choose replace files.
4. Launch the game. 
5. Launch the server again, this time you should get the green message, and the server will start hosting.
6. Launch the Profile Editor, the DB should now be correct.

Some of these steps are probably unnecessary, I just haven't tested them, this is how it worked on my machine.

Disclaimer:
This is a botch. Without ChatGpt this wouldn't exist, my typescript knowledge was precisely 0 when I started this, also shout out to reading the documentation. I created this in like 10 hours, 5 of which I should have been asleep. I typically only write projects for myself, but since its been a month I figured I would publish this.

To do:
1. Figure out how profile editor installs the modhelper, so the fix can be installed in the first place.
2. Do QA testing
3. Pull request, Fork, or whatever. To get the original updated. I had to get around to learning github at some point.

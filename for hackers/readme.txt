This patch is intended for those who want to build their own titlescreen hacks 
based on MOTHER Restored. It doesn't include any changes visible to the end user,
just internal changes.

Changes (from most to least important)
1.  Easy Ring encounter rate code moved from $9F73 to $9FD3 to make room for 
    the larger Earth Bound title screen.
2.  New universal tilemap added that can be used to create both the MOTHER and
    Earth Bound title and intro screens.
3.  Header updated to the iNES 2.0 header used in the No-Intro version of 
    Earthbound Beginnings.
![](menu.png) 
Quick little raw memory card that has 16K sectors and a malformed icon that should cause the icon read size to return 0x28CD800.  This gets sanity checked to its doom, and there seems to be no way to bypass the check as the maximum directory length scales *down* with sector size increase proportionally

[Save File](Test2.USA.raw)
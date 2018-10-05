# How to set-up the mute-command

## Set up the `?mute` command

In this tutorial I'll show you, how to set up the `?mute` command, that it works correctly.

It's really easy, so **lets go**. :D

First, you have to create a new role, or choose a role that already exists. The role **shouldn't** have the following permission:

![Permisson](https://i.imgur.com/Nr0TfQk.png)

Also, the position of the "Mute" role **should** be **above** the muteable roles, to make shure that the "Mute" role can overwrite the text-permissions of the roles, which are below the "Mute" role.

![Role-Postition](https://i.imgur.com/yBvWJ5N.png)

After that, define the "Mute" role for LenoxBot with `?muterole` _rolename_

![Muterole](https://i.imgur.com/dJ0wFZS.png)

**That's it.** Now you can use `?mute` _@User time{d, h, m, s} {reason}_

![Mute](https://i.imgur.com/mHJdqrR.png)

_And now:_ Take away the troublemakers. :\)


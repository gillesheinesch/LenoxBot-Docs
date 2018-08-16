title: Set up the mute Command
description: A tutorial, how to set up the mute command correctly

# Set up the `?mute` command

In this tutorial I'll show you, how to set up the `?mute` command, that it works correctly.

It's really easy, so **lets go**. :D

First, you have to create a new role, or use a role that exists already.
The role **shouldn't** have the following permissions:

![Image Permisson](https://i.imgur.com/Nr0TfQk.png)

Also, the position of the role **should** be **over** the roles, that should be able to mute, so the "Mute" role can overwrite the text-permissions of the roles, which position is under the "Mute" role.

![Image Role-Postition](https://i.imgur.com/yBvWJ5N.png)

Now, you can define the "Mute" role for the bot with `?muterole` *rolename*

![Image Muterole](https://i.imgur.com/dJ0wFZS.png)

**That's it.** Now you can use `?mute` *@User time{d, h, m, s} {reason}*

![Image Mute](https://i.imgur.com/mHJdqrR.png)

*And now:* Take away the troublemakers. :)

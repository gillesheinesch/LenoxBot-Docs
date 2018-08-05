title: Set up the ?mute Command
description: A tutorial, how to set-up the ?mute Command correctly

# Set up the `?mute` command

Here, i'll show you, how to set up the `?mute` command, that it works correctly.

It's really easy, so **lets go**. :D

First, you have to create a new role, or use an excisting.
The role **shouldn't** have the following permissions:

![Image Permisson](https://i.imgur.com/Nr0TfQk.png)

Also, the Position of role **should** be **over** the Roles, that should be muted, so the "Mute" Role can overwrite the Text-Permissions of the Roles, which Position is under the "Mute" Role.

![Image Role-Postition](https://i.imgur.com/yBvWJ5N.png)

Now, you can define the "Mute" Role for the Bot with `?muterole` *rolename*

![Image Muterole](https://i.imgur.com/dJ0wFZS.png)

That's it. Now you can use `?mute` *@User time{d, h, m, s} {reason}*

![Image Mute](https://i.imgur.com/mHJdqrR.png)

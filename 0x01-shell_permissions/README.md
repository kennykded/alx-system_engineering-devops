<h1>Shell Permissions Scripts</h2>

<p>0-iam_betty: a script that switches the current user to the user betty.</p>

<p>1-who_am_i: a script that prints the effective username of the current user.</p>

<p>2-groups: a script that prints all the groups the current user is part of.</p>

<p>3-new_owner: a script that changes the owner of the file hello to the user betty.</p>

<p>4-empty: a script that creates an empty file called hello.</p>

<p>5-execute: a script that adds execute permission to the owner of the file hello.</p>

<p>6-multiple_permissions: a script that adds execute permission to the owner and the group owner, and read permission to other users, to the file hello.</p>

<p>7-everybody: a script that adds execution permission to the owner, the group owner and the other users, to the file hello.</p>

<p>8-James_Bond: a script that sets the permission to the file hello as follows:</p>

Owner: no permission at all
Group: no permission at all
Other users: all the permissions

<p>9-John_Doe: a script that sets the mode of the file hello to this:</p>

-rwxr-x-wx 1 julien julien 23 Sep 20 14:25 hello

<p>10-mirror_permissions: a script that sets the mode of the file hello the same as olleh’s mode.</p>

<p>11-directories_permissions: a script that adds execute permission to all subdirectories of the current directory for the owner, the group owner and all other users.</p>

<p>12-directory_permissions: a script that creates a directory called my_dir with permissions 751 in the working directory.</p>

<p>13-change_group: a script that changes the group owner to school for the file hello</p>

<p>100-change_owner_permissions: a script that changes the owner to vincent and the group owner to staff for all the files and directories in the working directory.</p>

<p>101-symbolink_link_permissions: a script that changes the owner and the group owner of _hello to vincent and staff respectively.</p>

<p>102-if_only: a script that changes the owner of the file hello to betty only if it is owned by the user guillaume.</p>

<p>103_Star_wars: a script that will play the StarWars IV episode in the terminal.</p>
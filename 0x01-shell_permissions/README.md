### Scripts
* **0-iam_betty** - creates a script that switches current user to betty
* **1-who_am_i** - prints the effective username of the current user
* **2-groups** - script that prints all the groups the current user is part of
* **3-new_owner** - changes the owner of the file hello to the user betty
* **4-empty** - creates an empty file called hello
* **5-execute** - adds execute permission to the owner of the file hello
* **6-multiple_permissions** - adds execution permission to the owner and the group owner, and reads permission to other users, to the file hello
* **7-everybody** - script that adds execution permission to the owner and the other users, to the file hello
* **8-James_Bond** - script that sets permission to the file hello as follows:
    - Owner: no permission at all
    - Group: no permission at all
    - Other users: all the permissions
* **9-John_Doe** - sets the mode of the file hello to :
    ```shell
    -rwxr-x-wx 1 julien julien 23 Sep 20 14:25 hello
    ```
* **10-mirror_permissions** - script that sets the mode of the file *hello* the same as *olleh's* mode
    - The file *hello* will be in the working directory
    - The file *olleh* will be in the working directory
    ---
    **NOTE**

    The mode of olleh will not always be 664. Make sure the script works for any mode.

    ---
    * 
* **11-directories_permissions** - script that adds execute permision to all subdirectories of the current directory for the owner, the group owner and all other users. Regular files should not be changed.
* **12-directory_permissions** - script that creates a directory called *my_dir* with permissions 751 in the working directory.
* **13-change_group** - script that changes the group owner to *school* for the file *hello*
* **100-change_owner_and_group** - script that changes the owner to *vincent* and the group owner to *staff* for all the files and directories in the working directory.
* **101-symbolic_link_permissions** - script that changes the owner and the group owner of *_hello* to *vincent* and *staff* respectively (_hello is in the working directory and it's a symbolic link).
* **102-if_only** - script that changes the owner of the file *hello* to *betty* only if it is owned by the user *guillaume*
* **103-Star_Wars** - a script that will play the StarWars IV episode in the terminal
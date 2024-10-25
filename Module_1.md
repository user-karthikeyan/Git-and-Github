># Diff command

- ## Command
    <code>**diff** old_file new_file</code> 

- ## Description
    - The number **3c3** in this `3` denotes the line number in the old file seperated by type of operation `c` which means the 3rd line in old file is substituted by the 3rd line in the new file.

    - `<` denotes the line in old file

    - `>` denotes the line in new file

- ## Output
    ![Output](images/diff%20normal.png)

- ## Command with option u
    <code>**diff** -u old_file new_file</code> 

- ## Description
    - Provides the difference of two files in a more readable format by both including the lines from the **old file** and **new file**

    - `-` means deletion

    - `+` means insertion

    - By redirecting the output we can save it seperate file with **.diff** extension we can apply the update using the **patch** command

- ## Output
    ![Output](images/diff%20option%20u.png)
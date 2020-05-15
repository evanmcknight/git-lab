Answer 1: git version 2.26.2.windows.1

Answer 2: 
    
    diff.astextplain.textconv=astextplain    
    filter.lfs.clean=git-lfs clean -- %f     
    filter.lfs.smudge=git-lfs smudge -- %f
    filter.lfs.process=git-lfs filter-process
    filter.lfs.required=true
    http.sslbackend=openssl
    http.sslcainfo=C:/Program Files/Git/mingw64/ssl/certs/ca-bundle.crt
    core.autocrlf=true
    core.fscache=true
    core.symlinks=false
    credential.helper=manager
    user.name=Evan McKnight
    user.email=em674716@ohio.edu

Answer 3: git --help gives a list of common git commands.

Answer 4:

    On branch master

    No commits yet

    Untracked files:
        (use "git add <file>..." to include in what will be committed)
            README.md
            answers.md

    nothing added to commit but untracked files present (use "git add" to track) 

Answer 5: 
    
    On branch master

    No commits yet

    Changes to be committed:
        (use "git rm --cached <file>..." to unstage)
                new file:   README.md

    Untracked files:
        (use "git add <file>..." to include in what will be committed)
            answers.md

Answer 6:

    On branch master

    No commits yet

    Changes to be committed:
        (use "git rm --cached <file>..." to unstage)
            new file:   README.md
            new file:   answers.md

Answer 7:

    On branch master
    nothing to commit, working tree clean

Answer 8:

    commit 84fbb59cb8a4db4ea48f8f68742ff387799b3d64 (HEAD -> master)
    Author: Evan McKnight <em674716@ohio.edu>
    Date:   Fri May 15 17:08:38 2020 -0400

    Initial commit

Answer 9:

    On branch master
    Your branch is up to date with 'origin/master'.

    nothing to commit, working tree clean

Answer 10: The changes were not updated in the local directory.

Answer 11: 

    To https://github.com/evanmcknight/git-lab.git
    ! [rejected]        master -> master (fetch first)
    error: failed to push some refs to 'https://github.com/evanmcknight/git-lab.git'
    hint: Updates were rejected because the remote contains work that you do
    hint: not have locally. This is usually caused by another repository pushing
    hint: to the same ref. You may want to first integrate the remote changes
    hint: (e.g., 'git pull ...') before pushing again.
    hint: See the 'Note about fast-forwards' in 'git push --help' for details.

Answer 12: The changes made online were addded.

Answer 13: 
    
        Directory: C:\Users\evanj\Desktop\cs2400\git-lab-2


    Mode                LastWriteTime         Length Name
    ----                -------------         ------ ----
    -a----        5/15/2020   5:31 PM            302 .gitignore
    -a----        5/15/2020   5:31 PM             11 README.md

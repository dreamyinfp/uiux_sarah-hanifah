(3) Version Control and Branch Management (Git)

What is Versioning? Mengatur versi dari source code program

Version Control System

- Single User
  SCCS - 1972 Unix only
  RCS - 1982 Cross-platform, text only
- Centralized
  CVS - 1986 File focus
  Perforce - 1995
  Subversion - 2000 - track directory structure
  Microsoft Team Foundation Server - 2005
- Distributed
  Git - 2005
  Mercurial - 2005
  Bazaar - 2005

GIT
Salah satu version control system populer yang digunakan pada developer untuk mengembangkan software secara bersama-sama (real world collaboration). Terdistribusi (bukan tersentralisasi). Dibuat oleh Linus Torvalds (2005) - Linus Kernel (https://github.com/torvalds/linus). Git track every file change. Your changes, John's changes, and everyone! Git can be installed on Mac, Windows, and Linux.

Git can undo some 'points'. We call it Commit. (Commit = the record of changes)

How to Create a new repository

1. Namai Repository (sesuaikan dengan kebutuhan)
2. Pilih akses. Publik atau Privat.
3. Centang pilihan Add .gitignore.
4. Pilih Node pada pilihan .gitignore template.
5. Klik Create repository button.

The Staging Area Concept
Di Working Station atau Working Directory setelah ada perubahan dan kita ingin memasukkannya ke staging area, kita melakukan Git Add. Setelah kita Git Commit & Git Push, baru akan masuk ke repository atau masuk ke dalam website GitHub.

Commit Message
"if applied, this commit will be your subject line here."

For example:

- If applied, this commit will refactor subsystem X for readability
- If applied, this commit will update getting started documentation
- If applied, this commit will remove deprecated methods
- If applied, this commit will release version 1.0.0.

Notice how this doesn't work for the other non-imperative forms:

- If applied, this commit will fix the bug with Y
- If applied, this commit will change the behavior of X
- If applied, this commit will more fixes for broken stuff
- If applied, this commit will sweet new API methods

Git Diff and Stash
Git Diff untuk mengetahui bagaimana perubahan yang terjadi di file yang telah diedit. Git Stash untuk menyimpan perubahan tersebut. Sehingga nanti bisa dikembalikan di perubahan-perubahan yang diinginkan.

Inspecting Repository
Bagaimana kita me-management versi dari file yang kita buat.

Git Reset

--soft
uncommit changes, changes are left staged (index)

--hard
uncommit + unstage + delete changes, nothing left.

Branch berfungsi untuk melindungi Main Project kita.

Git Branching

# show all branch

$ git branch --list

# create a new branch called <branch>

$ git branch <branch>

# force delete the specified branch

$ git branch -D <branch>

# list remote branch

$ git branch -a

Pull Request
Teknik ini digunakan agar kita bisa berkontrobusi terhadap Repository yang sudah ada.

Workflow Collaboration
"How to understand the proper workflow to collaborate with GitHub or Gitlab?"
"How to optimize your workflow with GitHub or Gitlab?"

1. Let the master branch undisturbed
   $ (master) git branch development
   $ (master) git checkout development

2. Avoid direct editing on development
   $ (development) git branch feature1
   $ (development) git checkout feature1

3. Apply the feature to development only
   $ (feature1) git checkout development
   $ (development) git merge feature1

4. Apply development to master when it's done
   $ (master) git merge development

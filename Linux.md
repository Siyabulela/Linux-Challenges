https://umuzi-org.github.io/tech-department/projects/linux/beginner/

----------------------------------------TASK 1
1. ls. Desktop  Documents  Downloads  Music  Pictures  Public  Templates  Videos

2. /home/recruit. It means, I'm in a sub-folder called recruit, inside a folder called home.

3. mkdir workspace/ cd workspace

4. I see nothing on the directory 'workspace', because there is nothing on that directory.

5. touch README.md

6. cp README.md CHANGELOG.md

----------------------------------------TASK 2
1. touch exercise.md
   mv exercise.md ../tmp
   cd /tmp
   rm exercise.md

----------------------------------------TASK 3
1. touch umuzi.md recruits.md cohort.md

2. echo "UMUZI IS FIRE" > umuzi.md
   echo "UMUZI IS FIRE" > recruits.md
   echo "UMUZI IS FIRE" > cohort.md

3. cat umuzi.md recruits.md cohort.md

4. cat umuzi.md recruits.md cohort.md > summary.md

5. echo "The End" >> summary.md

------------------------------------------TASK 4
1. locate umuzi
   /home/recruit/workspace/umuzi.md

2. locate umuzi > search_result.md

------------------------------------------TASK 5
1. cd /documents
   touch pad.md

2. cd ../Desktop

3. cp ../Documents/pad.md work/copy_pad.md

4. locate updatedb
   /etc/updatedb.conf
   /etc/alternatives/updatedb
   /etc/alternatives/updatedb.8.gz
   ...

5. cd -
   /home/recruit

6.sudo apt upgrade locate copy_pad.md
   /home/recruit/Desktop/work/copy_pad.md


-------------------------------------------TASK 6
1. find -name *.pdf

2. find -name *.pdf >> Documents/saved_results

3.find . -mtime -1 -print

-------------------------------------------TASK 7
1. nano my_bio.md

2. Ctrl + x

3. mkdir my_files
   mv my_bio.md my_files

-------------------------------------------TASK 8
1. sudo apt update

2. sudo apt upgrade
   Y

3. sudo apt install

4. sudo apt install tree

5. sudo dpkg -i code_.deb


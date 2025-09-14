(master)
mkdir Balite_IT120_Act1
cd Balite_IT120_Act1
git init
touch Profie.txt
touch Education.txt
touch Background.txt
touch Readme.txt
touch Test.py
(Branch 1)
git status
git add --all
git status
git commit -m "Add ammends in Profile.txt and update Readme.txt"
git status
git checkout Balite_B2
(Branch 2)
git checkout Balite_B1 -- Readme.txt
git status
git add --all
git status
git commit -m "Add ammends in Education.txt and update Readme.txt"
git status
git checkout Balite_B3
(Branch 3)
git checkout Balite_B2 -- Readme.txt
git status
git rm Test.py
git status
git add --all
git status
git commit -m "Add ammends in Background.txt, update Readme.txt, remove Test.py"
git status
git checkout Balite_B4
(Branch 4)
git checkout Maraon_B3 -- Readme.txt
git rm Test.py
git status
git add --all
git status
git commit -m "Update Readme.txt and remove Test.py"
git checkout master
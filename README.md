# Yes
for i in {1..10}; do
  echo "Commit number $i" >> progress.txt
  git add progress.txt
  git commit -m "Feature update: Added line $i to progress tracker"
#no for somwthing

Requirements:
Having a version of Python above 3.14 installed on your computer.
Having named the folder containing the files 'rbx2source'

--Command Prompt Command--


cd path/to/rbx2source

pyinstaller --onefile rbx2source/Rblx2Source.py ^
  --add-data "rbx2source/Icon.png;." ^
  --add-data "rbx2source/gmod.png;." ^
  --add-data "rbx2source/sfm.png;." ^
  --add-data "rbx2source/tf2.png;."

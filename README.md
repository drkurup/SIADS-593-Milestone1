# SIADS-593-Milestone1

This is the SIADS-593 Milestone project Readme document.

Refer to this URL to see the Chicago L Map: [Chicago L Map](https://www.transitchicago.com/assets/1/6/ctamap_Lsystem.png)

The Chicago L Ridership data science project is collaboratively developed in Deepnote. This is developed as part of the SIADS-593-Milestone1 project.

GitHub URL: [https://github.com/drkurup/siads_593_milestone1](https://github.com/drkurup/siads_593_milestone1) (This is a private repository for the time being)

## Project Structure

![Project Structure](files/siads593_milestone1_project_structure.png)

## Git Status

```bash
(venv) root@deepnote:~/work/siads_593_milestone1 # git status
On branch main
Your branch is up to date with 'origin/main'.

Changes not staged for commit:
  (use "git add/rm <file>..." to update what will be committed)
  (use "git checkout -- <file>..." to discard changes in working directory)

        modified:   README.md
        deleted:    deepnote/Daily Notebook.ipynb
        modified:   deepnote/Init.ipynb
        deleted:    deepnote/Monthly Notebook.ipynb

Untracked files:
  (use "git add <file>..." to include in what will be committed)

        .gitignore
        deepnote/Analysis.ipynb
        deepnote/Data_Collection_And_Cleaning.ipynb
        deepnote/Visualizations.ipynb
        files/
        src/

no changes added to commit (use "git add" and/or "git commit -a")
(venv) root@deepnote:~/work/siads_593_milestone1 # git add .
(venv) root@deepnote:~/work/siads_593_milestone1 # git status
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git reset HEAD <file>..." to unstage)

        new file:   .gitignore
        modified:   README.md
        new file:   deepnote/Analysis.ipynb
        deleted:    deepnote/Daily Notebook.ipynb
        new file:   deepnote/Data_Collection_And_Cleaning.ipynb
        modified:   deepnote/Init.ipynb
        deleted:    deepnote/Monthly Notebook.ipynb
        new file:   deepnote/Visualizations.ipynb
        new file:   files/requirements.txt
        new file:   src/data/CTARidershipMonthly_20240521.csv
        new file:   src/data/CTA_Stops_20240526.csv
        new file:   src/data/DECENNIALDHC2020.P1-Data.csv
        new file:   src/data/DECENNIALSF12000.H002-2024-05-27T193225.csv
        new file:   src/data/DECENNIALSF12010.P1-Data.csv
        new file:   src/data/final_merge_061124.csv
        new file:   src/data/station_lookup_table.csv
        new file:   src/data/tertiary_dataset_cleaning_output_061224.csv
        new file:   src/reports/final_merge_dataset_profiling.html
        new file:   src/reports/primary_dataset_profiling.html
        new file:   src/reports/secondary_dataset_profiling.html
        new file:   src/reports/tertiary_dataset_profiling.html

(venv) root@deepnote:~/work/siads_593_milestone1 # git commit -m "Changes to Data collection, cleaning, analysis, visualizations, Init. Adding requirements.txt"
[main 9d3fba5] Changes to Data collection, cleaning, analysis, visualizations, Init. Adding requirements.txt
 
(venv) root@deepnote:~/work/siads_593_milestone1 # git push
(venv) root@deepnote:~/work/siads_593_milestone1 # git config --global user.name "Your name"
(venv) root@deepnote:~/work/siads_593_milestone1 # git config --global user.email "Your email"
(venv) root@deepnote:~/work/siads_593_milestone1 # git remote set-url origin https://your-username:your-PAT@github.com/your-username/siads_593_milestone1.git
(venv) root@deepnote:~/work/siads_593_milestone1 # git config --global credential.helper cache
(venv) root@deepnote:~/work/siads_593_milestone1 # git config --global credential.helper 'cache --timeout=3600'
(venv) root@deepnote:~/work/siads_593_milestone1 # git push origin main


## Running the Project in Deepnote

To run a Notebook, copy the `*.ipynb` files from the `deepnote/` folder to the Notebooks section in Deepnote.

![Deepnote Workspace](files/siads593_deepnote_structure.png)


When the workspace is initialized, Deepnote will automatically run `Init.ipynb` and all the installations mentioned in `requirements.txt`. Make sure to copy `requirements.txt` from `deepnote/.` to the root level of `Files/.`

## Running the Project in Jupyter Notebook

Follow the above steps to checkout the project from the GitHub repository. Use the `Jupyter/` files to run in Jupyter Notebook.

Note that the installations, libraries, and setup might need some manual intervention when using a Deepnote project in Jupyter Notebook.

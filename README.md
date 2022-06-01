# Overview

The following project is meant as a data science exercise to highlight and showcase your technical abilities.

Essentially, we want to mimic (at small scale), a data science project that is similar to one you would encounter for the position. For this particular project you are given a [csv file](./sports-teams.csv) that represents the major U.S. sports.

Your task is to ingest this CSV file and create a couple of interactive plots, and move the data into a "database".

The resulting code, plots, and "database" files should be uploaded to your github account and linked in the response email.

You may start with either task but the outline below should describe what we are looking for in each part.

## Creating Plots

- Create a plot that represents the total sadium capacity (as a bar chart) of each team. An example can be found [here](./plots/stadium-capacity.pdf).
  - Now make this plot interactive, such that you can filter the data being plotted based on League (MLB, NFL, etc.), City (Los Angeles, New York, etc.), or any other field you find relevant.
- Plot the cumulative sum of Stadium Capacity over time, it should look somthing like [this plot](./plots/total-capacity.pdf).
- Build a plot that shows the number of chamionships per field (State, City, etc.). Allow the user to define which field they want to plot against.

## Writing to a database

The "database" in our example will simply be a [directory](./directory) that will contain JSON files. You are to take each row in the csv document and create them as separate documents where the file name is the name of the team.

## Final Thoughts

The project does not require any particular language, but the final returned files should have an organized structure and have comments and documentation explaining how to make the resulting files.

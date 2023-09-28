# datafun-06-projects

### Author: [Adrian Vega](https://github.com/adriacv17) <br >Respository: [datafun-06-projects](https://github.com/adriacv17/datafun-06-projects) <br> Data: 09/28/2023

## Focus of Repository

In this module, you will:

    1. Perform a guided exploratory data analysis project.
    2. Conduct a unique data analysis exploration.

The objective is to craft a compelling narrative ("tell a story") using data, showcasing not only your analytical skills but also your professional and engaging communication abilities.

### Chapters

This module requires the skills learned in previous chapters. The first is a guided exploratory data project that focuses on diamonds.csv and is based on in Exercise 9.16 beginning on page 352 of the text. The second is a project of your choice, related to your domain.

Decide what you would like your second project to focus on / showcase. Review the requirements for the project and make sure your topic lends itself to successfully completing all requirements.

### Set up a Virtual Environment

Next, we'll create and activate a virtual environment specifically for this project. We'll also install additional packages required for this project.

### Create a Virtual Environment

1. Open the terminal in VS Code. (View / Terminal)
2. Run the following command to **create** a virtual environment for this project.

```shell
python -m venv .venv
```

Verify that a new `.venv` folder was created. It may take a while for the command to complete.

🚀 Rocket Tip: When VS Code Python Extension offers to select the Environment, say Yes.

### Activate the Virtual Environment

Wait for the creation to finish, then **activate** the virtual environment:

- For PowerShell: `.\.venv\Scripts\Activate`
- For macOS/Linux:  `source .venv/bin/`

🚀 Rocket Tip: Notice the terminal changes to reflect the active virtual environment.

### Install Dependencies to the Active Virtual Environment

Install additional project dependencies into the active virtual environment.
The packages ipykernel and jupyterlab are required to run a notebook.
The packages pandas, matplotlib, and seaborn are used to work with data and charts.

```shell
python -m pip install --upgrade pip ipykernel jupyterlab
python -m pip install --upgrade pandas matplotlib seaborn
python -m pip install --upgrade voila
```

Alternatively, you can install all the packages listed in the requirements.txt file.

```shell
python -m pip install --upgrade -r requirements.txt
```

Note: The `--upgrade` parameter gets the latest version of each package.

## Task 1 - Prepare Your Module Repository

1. GitHub
    a. Create a new repository named datafun-06-projects on GitHub.
    b. Initialize it with the default README.md.
2. Local Machine
    a. In VS Code, clone your new repo into your Documents folder.
3. Repository Essentials
    a. Add a .gitignore file from a previous Python project.
    b. Add a requirements.txt file to hold external dependencies for Jupyter notebooks and others as you need them. 
4. Update README.md
    a. Modify the README.md to include your name, the link to your repo, and the focus of this project repository. 
    b. Include instructions with the exact commands to: 
        1. Create and activate your virtual environment.
        2. Install all required external dependencies.
    c. Execute your Python files.
5. Create your local virtual environment (hint: use venv to create a .venv folder)
6. Activate your local virtual environment (hint: call a command in the .venv subfolder)
7. Install any external dependencies you need (hint: use requirements.txt and all the files needed for Jupyter notebooks, pandas, etc.)
8. Push to GitHub 
    a. Add and commit all your changes with a commit message "Initialized repo"
    b. Push your changes to GitHub

### Task 1 - Verify Repository

1. Take a screenshot of your GitHub project repository after you've pushed these changes to GitHub.
2. Display the screenshot as evidence of task completion.

## Task 2 - Guided Diamonds Project

This first project is a guided exploration. 

1. Follow the instructions for Exercise 9.16 (starting pg. 350).
2. Complete the exercise in a Jupyter notebook. 
3. Include the title of the notebook, your name, and date at the top.
4. Include the following Markdown Section Headings in your notebook. 
    a. Section 1-Load: Get the file, store it in your repo, and load it into a DataFrame. 
    b. Section 2-View: Display the first 7 rows and the last 7 rows.
    c. Section 3-Describe: Use the DataFrame describe() function to calculate basic descriptive statistics for all numeric columns. 
    d. Section 4-Series: Use the Series method describe() to calculate the descriptive stats for all category/text columns.
    e. Section 5-Unique: Use the Series method unique() to get unique category values. 
    f. Section 6-Histograms: Use the DataFrame's hist() function to create a histogram for each numerical column.

### Task 2 - Push to GitHub

1. Execute the completed notebook
2. Add, commit, and push your changes to GitHub. You can use incremental commits as you work - provide useful commit messages.
3. At the end, use a commit message like "Task 2 complete".
4. Verify your GitHub notebook appears complete and well-presented. 

### Task 2 - Verify

1. Capture a screenshot of your completed notebook as viewed in GitHub at the conclusion of this task.
2. Display the screenshot as evidence of task completion.

## Task 3 - Custom Exploratory Data Project

1. Use everything you've learned to conduct a unique data exploration project using some information related to your domain. 
2. Create a new notebook that uses a dataset of your choice.
3. The notebook name should make it clear this is your unique project.  
4. Use this project to feature all of the key skills learned. See the list above. 
5. Include challenging Python programming aspects - find a reason to use filter(), map(), and list comprehensions.
6. Have fun and make it unique.

Your second project must show the following Python skills and Markdown sections:

1. Section 1-Load - Read from a data file into a pandas DataFrame.
2. Section 2-View - Display the first 5 rows and the last 5 rows.
3. Section 3-Describe: Use the DataFrame describe() function to calculate basic descriptive statistics for all numeric columns. 
4. Section 4-Series: Use the Series method describe() to calculate the descriptive stats for all category/text columns.
5. Section 5-Unique: Use the Series method unique() to get unique category values. 
6. Section 6-Histograms: Use the DataFrame's hist() function to create a histogram for each numerical column.
7. Section 7-List: Get some of your information into a list. Process each item in the list (use for or comprehensions as you like). 
8. Section 8-Filter: Use filter() to show only part of the information. 
9. Section 9-Map: Use map() to transform some of the data. 
10. Include a title section with your name - this is your branding - make it professional and attractive.
11. Use Markdown section headings to professionally present your work. 
12. Tell a story with data - lead us through your project and summarize your interesting results. 

### Task 3 - Push to GitHub

1. Execute the completed notebook
2. Add, commit, and push your changes to GitHub. You can use incremental commits as you work - provide useful commit messages.
3. At the end, use a commit message like "Task 3 complete".
4. Verify your GitHub notebook appears complete and well-presented. 

### Task 3 - Verify

1. Capture a screenshot of your completed notebook as viewed in GitHub at the conclusion of this task.
2. Display the screenshot as evidence of task completion.

## Optional Bonus Section

1. As part of your custom project, use a library or module we did not explore in class.
2. Consider imageio, nltk, texatistic, textblob, wordcloud, or others. 
3. Look for something new that might interest you. 
4. Learn it on your own and apply it to your domain/project. 
5. Clearly label your Section Bonus using Markdown. 
6. In the bonus section, explain what you chose, why, how it went, and your results. Do you recommend it? 
7. This is a chance to show advanced, creative skills - make it valuable for others by describing it well. 

### Optional Bonus - Push to GitHub

1. Execute the completed notebook
2. Add, commit, and push your changes to GitHub. You can use incremental commits as you work - provide useful commit messages.
3. At the end, use a commit message like "Bonus complete".
4. Verify your GitHub notebook appears complete and well-presented. 

### Optional Bonus - Verify

1. Capture a screenshot of your completed notebook as viewed in GitHub at the conclusion of this task.
2. Display the screenshot as evidence of task completion.
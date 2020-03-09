# Write your headline here

### Write your nutgraf here

Make sure your pitch answers the following questions:

- Why this story is relevant ("So what?) and why now?
- What is the single question your story tries to answer?
- Why will this story resonate with your audience?

What else has been done on this topic (provide links)? How is your angle different or fresh?

- [Related headline (NYT)](https://www.nytimes.com/2020/03/09/upshot/coronavirus-oil-prices-bond-yields-recession.html)
- [Related headline (NPR)](https://www.nytimes.com/2020/03/09/upshot/coronavirus-oil-prices-bond-yields-recession.html)
- [Related headline (WNYC)](https://www.nytimes.com/2020/03/09/upshot/coronavirus-oil-prices-bond-yields-recession.html)

Describe how and where you found the data with links and put the raw data (csv, xls, pdf) in a folder called `data` in this folder and/or provide a [link](https://docs.google.com/spreadsheets/d/1IdeVJv7SpbKwD1jMfOlXvIpx-ZwitU-3Y6c4iLqGu7c/edit#gid=1257216346) to your Google Sheet. Show your data work in your Google Sheet – this could be sorting, aggregating, filtering, pivot tables, vlookups, etc.

Write up at least one or up to three findings from your analysis based on the data you found.

- Finding 1
- Finding 2
- Finding 3

Who are some potential human sources you could reach out to for more info?

What is the maximum (best) story possible? What's the minimum (fallback) story if your hypothesis doesn't prove out?

## How to publish and submit your project

1. Clone a fresh copy of this project.
   `git clone git@github.com:JOUR73351/google-sheets-project.git NAME-OF-YOUR-PROJECT-HERE`

2. Remove my git tracking from the project
   ```rm -rf .git`

3. Create a new repository in GitHub called `NAME-OF-YOUR-PROJECT-HERE` with the following settings.
   ![new repository](assets/newrepo.png)

4. Follow GitHub's instructions for initializing a repo. Make sure you've checked `ssh`.

```
git init
git add -A
git commit -m "first commit"
git remote add origin git@github.com:YOUR-USERNAME-HERE/YOUR-REPO-HERE.git
git push -u origin master
```

5. Write your pitch in `README.md`.

6. Write your story in and add your assets and charts to `index.html`. Feel free to play around with and change the styles, but you are not required to. Delete the code that you don't need for your story.

7. When making changes, run the following git commands.

```
git add -A
git commit -m "YOUR-COMMIT-MESSAGE-HERE"
git push
```

8. To publish, go to the settings of your GitHub repo, scroll down to GitHub Pages, and configure the source to the master branch.
   ![GitHub Pages](assets/ghpages.png)

# Git & GitHub Lesson

## Objective:
Learn how to collaborate using Git and GitHub, including cloning, branching, pushing changes, and making pull requests (PR).

## Task:
Clone this repo, create a branch with your name, add your own homework file under the `homework/` folder, push changes, and submit a PR.

### Steps:

1. Fork this repo (click Fork at the top right).
2. Clone your fork:
    ```bash
    git clone https://github.com/YOUR_USERNAME/git_lesson2_batch13.git
    cd git_lesson2_batch13
    ```
3. Create and switch to your own branch (use your name):
    ```bash
    git checkout -b yourname_homework
    ```
4. Add your homework file inside the `homework/` folder, e.g., `yourname_homework.pdf`.
5. Stage and commit your changes:
    ```bash
    git add homework/yourname_homework.pdf
    git commit -m "Added homework for YOURNAME"
    ```
6. Push changes to your GitHub fork:
    ```bash
    git push origin yourname_homework
    ```
7. Go to GitHub, create a new Pull Request from your branch to the main repo.

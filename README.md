
## Aim:
It is created with a purpose of helping newbies into Open Source Contribution by guiding them to their initial Pull requests.

## What is Open Source Contribution?
Open-Source Software is a type of software whose code is publicly available to use and modify. Open-Source Contribution involves contributing to the development or improvement of open-source software.

## How Open Source can boost your carreer?
- Improve coding skills. 
- Gain early experience often required by companies for employment. 
- Increase community and peer recognition.
- Find greater job prospects.
- Aid in salary negotiations.
- Improve software on a user and business level.

## Contributing
Repo for you to raise a Pull Request for practice.

Just add your (username.md) in the contributor folder and answer the following questions in your Markdown file

- Introduce Yourself
- Tech Stack you use
- Copy & Paste the below code:
```bash
### Introduce Yourself

### Tech Stack I use
```

### TLDR Steps
1. Fork this repository.
2. Clone your forked version.
3. Make changes.
4. Commit your changes ( write a short descriptive message of what you have done).
5. Push your changes to your forked version.
6. Go to original project on Github & Create a Pull Request.

## Installation Steps
1. Fork this repository.
2. Clone your forked copy of the project.
```bash
git clone https://github.com/<your username>/demo-open-source.git
```
3. Change the working directory
```bash
cd demo-open-source
```
4. Add a reference to the original repository.
```bash
git remote add upstream https://github.com/prashant-gehlot/demo-open-source.git
```
5. Check the remotes for this repository.
```bash
git remote -v
```
6. Always take a pull from the upstream repository to your main branch to keep it at par with the main project(updated repository).
```bash
git pull upstream main
```
7. Create a new branch.
```bash
git checkout -b <your_branch_name>
```
8. Perform the desired changes to the code bass.
9. Track your changes.
```bash
git add .
```
10. Commit your changes.
```bash
git commit -m "Relevant message"
```
11. Push the committed changes in your feature branch to your remote repo.
```bash
git push -u origin <your_branch_name>
``` 
12. To create a pull request, click on compare and pull requets. Please ensure you compare your feature branch to the desired branch of the repo your are suppose to make a PR to.
13. Your have made a PR to this project. Sit back and relax while I review your PR.



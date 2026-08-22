# Development Tools and Standards
> by **Alyzee Yvon Celaya (@alyzcly)**  
> _Created on Saturday, August 22, 2026_

---
## i. Clone Repository
```bash
git clone https://github.com/alyzcly/Software-Versioning-Lab
```
The repository was cloned using the `git clone` command. This created a local copy of the GitHub repository for performing the required Git version control activities.

## ii. Creating New Branch
```bash
git checkout -b feature-update
```
A new branch named `feature-update` was created using the `git checkout -b` command. The command also switched the working branch from `main` to `feature-update`.

## iii. Modify README.md
Add your name and laboratory information.
The `README.md` file was modified to include the student's name and laboratory information required for Laboratory 1.

## iv. Commit Changes
**a. Stage Changes**  
```bash
git add .
```
The `git add .` command was used to stage the modified files for the commit.  

**b. Commit Changes**
```bash
git commit -m "Updated README with laboratory information"
```
The staged changes were committed using the required commit message:
> **Updated README with laboratory information**

## v. Push Changes
```bash
git push origin feature-update
```
The `feature-update` branch was pushed to the GitHub repository using the `git push` command.

## vi. Create Pull Request
**a. Pull Request**
**feature-update → main**
A Pull Request was created to propose the changes from the `feature-update` branch to the `main` branch.

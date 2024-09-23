# Github + Markdown

## Autor
Mohamed Alyouika

## Introduction

**GitHub** is a web-based interface that uses **Git**, the open source version control software that lets multiple people make separate changes to web pages at the same time. 
As Carpenter notes, because it allows for real-time collaboration, GitHub encourages teams to work together to build and edit their site content.

GitHub is primarily used for:
- **Version control**: Tracking changes to code over time, allowing developers to revert to previous versions if needed.
- **Collaboration**: Enabling teams to work together on projects, sharing code and reviewing changes.
- **Open-source development**: Serving as a hub for open-source projects, making it easy to contribute to and learn from the work of others.
- **Project management**: Providing tools for planning, tracking, and organizing development tasks.

In this report, I will be showing the different functions of  github  with the steps to follow and any information I consider relevant.

## Steps to follow to get Github up and running in Linux

1. Create an account and logIn to [Github](www.github.com).
2. Open Linux Terminal: Crtl+T
3. Write the following commands:

```
$ sudo apt update.
$ sudo apt install git
```
4. If it works then check for the installed version.

```
$ git --version
```
5. Go back to the Terminal and write:
```
$ git config --global user.email “<myGithubEmail>”
$ git config --global user.name “<myGithubName>”
```
6. We create a new repository in Github and upload the file.
```
$ git init
$ git add .
$ git commit -m “Upload the test file”
$ git push
```
At some point it may ask for a GitHub token. They can be obtained from **GitHub** → **Account Settings** → **Developer Settings** (On the left, at the bottom) → **Personal access tokens** → **Generate new token**.
8. Check Github if the file has been uploaded correctly.  

## Conclusion

In conclusion, GitHub is an essential platform for software developers and teams seeking to improve efficiency, collaboration, and code quality. Its robust features, strong open-source community, and integration capabilities make it a valuable asset for modern software development practices. By leveraging GitHub, developers can streamline their workflows, collaborate effectively, and contribute to the growth of the software development ecosystem.


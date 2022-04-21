
# Github Setup (Locally on VS Code)



For an existing folder, if you want to initialize git into it.
Follow the steps listed below:


## Configuration

```
git config --global user.email "your_email"
git config --global user.name "your_name"
```

Here ``--global`` represents that you are configuring github account globally i.e. same account for all the files where you will initialise ``git``.

_Note:_ _If you want to set the identity for only a particular repository,_ ***Omit*** ```--global```.

### Git commands
_Note:_ _If there is no branch in repo then commands below going to work smoothly_.
- ``` git init ```
- ``` git remote add origin _repo-url_ ```
- ``` git add . ```
- ``` git commit -m "commit_message" ```
- ``` git push -u origin master ```

_Else case_: _If there is one branch already then there can be issue of different commit history while merging the branches_.

#### Run these commands then
- ``` git checkout master ```
- ``` git branch main master -f ```
- ``` git checkout main ```
- ``` git push origin main -f ```



## Run Locally
When you want a repo to use in your local machine. Do follow below commands.

Clone the project

```bash
  git clone https://link-to-project
```

Go to the project directory

```bash
  cd my-project
```
And then start working on it.

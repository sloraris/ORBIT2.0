# ORBIT 2.0
<p align="center">
  <img src="orbit2.0.png" alt="ORBIT logo" style="border-radius:50%" />
</p>

## Repo layout
```
ORBIT2.0
┃
┣━━ <device>
┃   ┣━ config
┃   ┣━ .env
┃   ┣━ README
┃   ┗━ <service>
┃      ┣━ config
┃      ┣━ .env
┃      ┗━ README
┃
┗━ README
```

## Practices for industry parity
### 1. New branches for adding to or adjusting repo:
*Create new branch*
```
git checkout -b feature/add-<item or feature being added>
```
*Perform changes, make edits, or add files as needed*\
*Commit changes to branch (make sure to add new files to Git first so they can be tracked and committed)*
```
commit -m "<commit message>"
```
*Create pull request on Github and verify changes before merging to main*


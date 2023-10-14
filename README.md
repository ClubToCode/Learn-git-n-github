# Learn-git-n-github
![Linkes and resources](https://github.com/ClubToCode/Learn-git-n-github/assets/97173586/84811a49-7418-4087-9360-c07a36975e7e)

## GitHub account setup and Connecting Git to your account: 
- First, create a `GitHub account` by `Sign in` via your email at this [Link](https://github.com/).
    > While creating your account remember that you have to use your own as the `username`, with some number
- Download Git in your system : [👉Download from here👈](https://git-scm.com/downloads).
  
### Setup Git
For Git to work properly, we need to let it know who we are so that it can link a local Git user (you) to GitHub. When working on a team, this allows people to see what you have committed and who committed each line of code.

- Open any terminal or command prompt and enter the below commands. The commands below will configure Git. Be sure to enter your own information inside the quotes.

```sh
git config --global user.name usernamehere
git config --global user.email yourmailhere@example.com
```

- To verify that things are working properly, enter these commands and verify whether the output matches your name and email address.

```  
git config --get user.name
git config --get user.email
```

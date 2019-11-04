---
layout: tabbed-assignment
---

# Instructions

## Pull changes from the **upstream** repository {{site.data.assignment.upstream}}
1. Open **GitHub Desktop**.
1. Use the **View on GitHub** button to go to your repository on GitHub (in a browser).
1. On GitHub you should see a line right above the branch selection button that tells you how your fork compares to the original (upstream) version. **You should see that you are behind the SKHS-GDP-2019-2020 version.**
1. Click on the **Pull Request** button underneath the green **Clone or Download** button.
1. The pull request dialog will almost certainly be reversed, it will read (something like):

   ```
   base repository: SKHS-GDP-2019-2020/Prototype-1 base: master <
   head repository: Your-Username/Prototype-1 compare: master
   ```
   
   You want it to read:
   
   ```
   base repository: Your-Username/Prototype-1 base: master <
   head repository: SKHS-GDP-2019-2020/Prototype-1 compare: master
   ```
   
   So that the changes are being merged from the master branch of the SKHS-GDP-2019-2020/Prototype-1 repository into your repository.
   
1. As you switch the repositories you will probably end up with GitHub deciding that you are trying to compare the master branch of the same repository and it will take away the repository options leaving you with just branches. Click the **compare across forks** link to get back the repository options.
1. Now **create your pull request**.
1. **Merge** your pull request.

## Enable GitHub Pages for your repository

1. This, then
1. That, and finally
1. The other thing

## Notes

<!-- Don't edit links here, change them in _data/assignment.yml instead, -->

[slides]: <{{site.data.assignment.slides}}>
[template]: <{{site.data.assignment.template}}>

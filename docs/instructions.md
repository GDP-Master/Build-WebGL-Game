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

Now you're ready to setup and test a GitHub Pages website.

## Enable GitHub Pages for your repository

You must have a verified e-mail associated with your GitHub account to use GitHub Pages. If you do not, you will not be able to publish your prototype on the web.

1. On GitHub, click on the **Settings** tab in your repository.
1. Scroll down until you find the **GitHub Pages** section.
1. Under **Source** choose **master branch /docs folder** from the drop down menu.

   This will enable GitHub Pages, right now there will be nothing there - other than a fairly boring placeholder page - once you build your prototype and push it to GitHub it will replace the placeholder page. There will be a delay (up to 10 minutes) before your page is published for the first time. If there are problems, GitHub will send you an e-mail with an explanation.

1. After selecting the source for your GitHub Pages site, the page will scroll back to the top. Scroll back down to the **GitHub Pages** section. There you should see some text in a blue highlighted area that starts **Your site is ready to be published at** followed by a link to your site. After a few minutes, reload the page. The highlight will turn to green when the site is published. When it does click on the link. You should see a web page (not a 404 error web page).

You've got a site! Now to build the game.

## Build a WebGL version of your game

1. Launch **Unity Hub** and open your **Prototype-1** project.
1. Make sure the **Prototype-1** scene is open.
1. Open the **File** menu and choose **Build Settings**.
1. In the Build Settings dialog:
   - Click on the **Add Open Scenes** button (below the lower right corner of the **Scenes In Build** pane).
   - Select **WebGL** in the **Platform** pane.
   - Click the **Switch Platform** button is the bottom right corner.
1. Click **Build And Run**.
   - In the file picker select your **Prototype-1** folder.
   - In the **Save As:** text area enter **docs**.
   - Click **Save**.
   - If you are warned that '"docs" already exists. Do you want to replace it," click **Replace**.
1. Unity will now build a WebGL version of your prototype.

   The first build will take a **long** time. A **very** long time. Fortunately subsequent builds are faster.
   
1. When the build completes Unity will attempt to launch a local web browser to test the game. If it succeeds, try out your game. Nice, eh?

## Push the game to GitHub.

1. Go back to **GitHub Desktop**.
1. You should see a lot of changes. Make sure that they include a folder named **Build** in your **docs** folder.
1. Write a summary and click **Commit**.
1. **Push** your changes.

## Test your game.

1. In **GitHub Desktop** use the **View on GitHub** button to go to the repository on GitHub.

<!-- Don't edit links here, change them in _data/assignment.yml instead, -->

[slides]: <{{site.data.assignment.slides}}>
[template]: <{{site.data.assignment.template}}>

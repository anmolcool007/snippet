<p style="text-align:center;" align="center">
  <img align="center" src="https://github.com/anmolcool007/snippet/blob/main/display/snippetbg.jpg" width="40%" height="40%"/></p>
<br>

## About Snippet

**Design Contributions**

[Snippet](https://anmolcool007.github.io/snippet/) is a easy to contribute CSS design repository to get you started on your jouney towards Open Source. This will also be an open library for the world to see various template in action  and use them in their WebApps. There are no external libraries involved so the setup is hassle free and the contributors are admired by displaying their name and github link on the [website](https://anmolcool007.github.io/snippet/). 

## How to contribute

- Fork this repository
- Create a new CSS file with design name inside `./typohraphy/css-contributions` folder, [Unleash Your Creativity !!]
- Edit the `./typography/contributors.js` file as follows:

```js
{
    name: 'the-name-of-your-animation',
    author: 'your-github-username',
    author_url: 'your-github-url'
}
```
>Note **1**: Don't make any other class in your CSS file that will effect the page design.<br>
>Note **2**: The name of the class used should be same as the name of the CSS file and also name in the contributors.js file.<br>
>Note **3**: Open `./index.html` and select your design name to see the result of your design before pushing it to github.<br>

## Beginner's Guide to GitHub

- Fork the Repository
- Go to your forked repository and copy the HTTPS URL by clicking on code button.
- Open Terminal[In Mac/Linux] or Power Shell[in Windows].
    ```
    git clone 
    ```
- This would set your fork as the "origin" remote.
- Add Upstream by 
  ```
    git remote add upstream https://github.com/anmolcool007/snippet.git 
  ```
- Check your remote and Upstream 

    ```
    git remote -v  
    ```
- Pull from Upstream and create a new branch
    ```
    git pull upstream master
    git checkout -b BRANCH_NAME
    ```
- Make the desired changes in the code.
- Add, commit and push your changes
    ```
    git add -A
    git commit -m "DESCRIPTION_OF_COMMIT"
    git push origin BRANCH_NAME
    ```
- Now compare your branch with upstream and create a pull request.

---

### For Developers

Please contribute to make the templating more dynamic and suggest chaanges for smooth transition of first time contributors.

---

Please Star the Repository and share with all your friends.<br>
Happy Contributing !! :sunglasses:

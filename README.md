<a name="readme-top"></a>

# 📗 Table of Contents

- [📖 About the Project](#about-project)
  - [🛠 Built With](#built-with)
    - [Tech Stack](#tech-stack)
    
- [💻 Getting Started](#getting-started)
  - [Setup](#setup)
  - [Prerequisites](#prerequisites)
- [👥 Authors](#authors)
- [🤝 Contributing](#contributing)
- [⭐️ Show your support](#support)
-- [🙏 Acknowledgements](#acknowledgements)
- [❓ FAQ](#faq)
- [📝 License](#license)

# 📖 [Hello-world] <a name="Hello-World"></a>


**[Hello-world]** is among the first project built by a developer who is in the early stages of learning how to code.
It demonstrates how to connect your local editor code remotely to your github repository.

Furthermore, In this project, you will learn to use linters to fix any error in your code.

## 🛠 Built With  <a name="built-with"></a>

### Tech Stack <a name="tech-stack"></a>

  <summary>Javascript runtime environment</summary>
  <ul>
    <li><a href="https://nodejs.org/en/">Node JS</a></li>
  </ul>

  <summary>Version control</summary>
  <ul>
    <li><a href="github.com">Git Hub</a></li>
  </ul>
</details


<!-- GETTING STARTED -->

## 💻 Getting Started <a name="getting-started"></a>

Creating your first "Hello World" project

To get a local copy up and running, follow these steps.

### Prerequisites

In order to run this project you need:

-Visual Studio Code as editor
-Node JS
-Git bash
-Git hub account


### Setup

Clone this repository to your desired folder:

```sh
  cd my-folder
  git clone[ (https://github.com/fatmahussein/hello-world)]
```
## Linters

A linter is a tool that analyzes your source code to flag programming errors, bugs, stylistic errors, and suspicious constructs(source: [Wikipedia](<https://en.wikipedia.org/wiki/Lint_(software)>)).

There are a few reasons for using linters:

1. Catching syntax errors is more efficient. There is no need to debug simple mistakes like typos - the linter does it for you.
2. The entire codebase looks like written by one person.
3. Programmers can focus on solving problems, instead of cleaning up the code.

## Set-up linters in your local environment i.e on your editor

**Note**: The `npm` package manager is going to create a `node_modules` directory to install all of your dependencies. You shouldn't commit that directory. To avoid that, you can create a [`.gitignore`](https://git-scm.com/docs/gitignore) file and add `node_modules` to it:

```
# .gitignore
node_modules/
```
**NOTE:** If you are running on Windows, you need to initialize npm to create `package.json` file. 
   ```
   npm init -y
   ```
   1. Run
   ```
   npm install --save-dev hint@7.x
   ```
   *not sure how to use npm? Read [this](https://docs.npmjs.com/downloading-and-installing-node-js-and-npm).*
2. Copy [.hintrc](.hintrc) to the root directory of your project.
3. **Do not make any changes in config files - they represent style guidelines that you share with your team - which is a group of all Microverse students.**
   - If you think that change is necessary - open a [Pull Request in this repository](../README.md#contributing) and let your code reviewer know about it.
4. Run
   ```
   npx hint .
   ```
5. Fix validation errors.

### [Stylelint](https://stylelint.io/)

A mighty, modern linter that helps you avoid errors and enforce conventions in your styles.

1. Run

   ```
   npm install --save-dev stylelint@13.x stylelint-scss@3.x stylelint-config-standard@21.x stylelint-csstree-validator@1.x   ```

   *not sure how to use npm? Read [this](https://docs.npmjs.com/downloading-and-installing-node-js-and-npm).*

2. Copy [.stylelintrc.json](./.stylelintrc.json) to the root directory of your project.
3. **Do not make any changes in config files - they represent style guidelines that you share with your team - which is a group of all Microverse students.**
   - If you think that change is necessary - open a [Pull Request in this repository](../README.md#contributing) and let your code reviewer know about it.
4. Run `npx stylelint "**/*.{css,scss}"` on the root of your directory of your project.
5. Fix linter errors.
6. **IMPORTANT NOTE**: feel free to research [auto-correct options for Stylelint](https://stylelint.io/user-guide/cli#autofixing-errors) if you get a flood of errors but keep in mind that correcting style errors manually will help you to make a habit of writing a clean code!

<p align="right">(<a href="#readme-top">back to top</a>)</p>


## 👥 Authors <a name="authors"></a>

👤 **Author1**

- GitHub: (https://github.com/fatmahussein)
- Twitter: (https://twitter.com/FatmaHussein200)
- LinkedIn: (https://www.linkedin.com/in/fatuma-hussein-48149917b/)


👤 **Author2**
 
- GitHub:(https://github.com/batoorsohail)



👤 **Author3**
 
- GitHub:(https://github.com/ismailmunyentwari9)

## 🤝 Contributing <a name="contributing"></a>

<!-- CONTRIBUTING -->

Contributions, issues, and feature requests are welcome!

Feel free to check the [issues page](../../issues/).

## ⭐️ Show your support <a name="support"></a>

If you like this project please keep on coding. NEVER GIVE UP! We are here to collaborate.

You can send a simple "thank you" message to the comment section.


<!-- ACKNOWLEDGEMENTS -->

## 🙏 Acknowledgments <a name="Microverse Inc."></a>

I would like to thank Microverse team for guiding us through this project.

I would also like to thank Sohail and Ismail for the good collaboration that we had in successfully completing this project.


<!-- FAQ (optional) -->

## ❓ FAQ <a name="faq"></a>

- **[Question_1]**
Where can we get the set up for node JS installation?

  - [Answer_1]
Please click on the link https://nodejs.org/en/download/  to get the  setup.


<!-- LICENSE -->

## 📝 License <a name="license"></a>

This project is [MIT](./LICENSE) licensed.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

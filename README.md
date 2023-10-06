<div align="center">
<h1 align="center">
<img src="https://raw.githubusercontent.com/PKief/vscode-material-icon-theme/ec559a9f6bfd399b82bb44393651661b08aaf7ba/icons/folder-markdown-open.svg" width="100" />
<br>PAE</h1>
<h3>◦ Developed with the software and tools below.</h3>

<p align="center">
<img src="https://img.shields.io/badge/SVG-FFB13B.svg?style&logo=SVG&logoColor=black" alt="SVG" />
<img src="https://img.shields.io/badge/JavaScript-F7DF1E.svg?style&logo=JavaScript&logoColor=black" alt="JavaScript" />
<img src="https://img.shields.io/badge/HTML5-E34F26.svg?style&logo=HTML5&logoColor=white" alt="HTML5" />
<img src="https://img.shields.io/badge/Webpack-8DD6F9.svg?style&logo=Webpack&logoColor=black" alt="Webpack" />

<img src="https://img.shields.io/badge/Bootstrap-7952B3.svg?style&logo=Bootstrap&logoColor=white" alt="Bootstrap" />
<img src="https://img.shields.io/badge/ESLint-4B32C3.svg?style&logo=ESLint&logoColor=white" alt="ESLint" />
<img src="https://img.shields.io/badge/JSON-000000.svg?style&logo=JSON&logoColor=white" alt="JSON" />
<img src="https://img.shields.io/badge/java-%23ED8B00.svg?style&logo=openjdk&logoColor=white" alt="java" />
</p>
<img src="https://img.shields.io/github/license/SamyOffer/PAE?style&color=5D6D7E" alt="GitHub license" />
<img src="https://img.shields.io/github/last-commit/SamyOffer/PAE?style&color=5D6D7E" alt="git-last-commit" />
<img src="https://img.shields.io/github/commit-activity/m/SamyOffer/PAE?style&color=5D6D7E" alt="GitHub commit activity" />
<img src="https://img.shields.io/github/languages/top/SamyOffer/PAE?style&color=5D6D7E" alt="GitHub top language" />
</div>

---

## 📖 Table of Contents
- [📖 Table of Contents](#-table-of-contents)
- [📍 Overview](#-overview)
- [📂 Repository Structure](#-repository-structure)
- [⚙️ Modules](#modules)
- [🚀 Getting Started](#-getting-started)
    - [🔧 Installation](#-installation)
    - [🤖 Running PAE](#-running-PAE)
    - [🧪 Tests](#-tests)


## 📍 Overview

## Project description

This project aims to provide users with access to a website where they can view items for sale. The application also offers advanced functionalities to company employees, such as the ability to add or delete items on the site.

## Implementation

The project was implemented using a three-tier architecture, aimed at clearly separating the data layer, the business layer and the user interface layer.

### Three-Tier Structure

- **Data Layer**: This layer is dedicated to data management, be it the database containing information on items for sale, or other data relevant to the operation of the application.

- **Business layer** : The business layer manages the application's logic. This is where functionalities such as adding and deleting items are implemented.

- **User Interface**: This layer is the interface through which users interact with the application. It allows users to view items for sale and use the available functionalities.

### Testing

Each implemented feature has been rigorously tested to ensure that it works properly. Unit tests and integration tests were carried out to validate the different parts of the application. Requests were also tested to guarantee the reliability and security of the application.


---

## 📂 Repository Structure

```sh
└── PAE/
    ├── .DS_Store
    ├── .gitignore
    ├── demo.sql
    ├── init.sql
    ├── package-lock.json
    ├── pom.xml
    ├── request.sql
    ├── requests/
    │   ├── availabilities.http
    │   ├── http-client.env.json
    │   ├── notifications.http
    │   ├── objects.http
    │   └── users.http
    ├── seed.sql
    ├── src/
    │   ├── .DS_Store
    │   ├── main/
    │   ├── package-lock.json
    │   └── test/
    └── webApp/
        ├── .DS_Store
        ├── .eslintrc.js
        ├── .gitignore
        ├── .gitkeep
        ├── package.json
        ├── src/
        └── webpack.config.js
```

---

## 🚀 Getting Started

### 🔧 Installation

1. Clone the PAE repository:
```sh
git clone git clone https://github.com/SamyOffer/Projet_Application_Entreprise
```

2. Change to the project directory and install the dependencies:
```sh
cd PAE/WebApp
```
```sh
npm i 
```


### 🤖 Running PAE

```sh
npm start (in WebApp/)
```
Run the main 

### 🧪 Tests

We have conducted comprehensive testing for a variety of files, achieving a high level of test coverage, particularly for the following files:

AvailabilityUCCImpl,
NotificationUCCImpl,
ObjectsUCCImp, 
UserUCCImpl,

The tests for these files are visible in the folder: 
```sh
cd src/test/java/be/vinci/pae
```
---

[↑ Return](#Top)

---

<a name="top"></a>

<div align="center">
  <h3 align="center">Password Generator GUI (CI/CD and Build .exe)</h3>

  <p align="center">
   A simple and secure password generator with a graphical interface. Instantly creates strong passwords 
   based on your selected criteria.
    <br />
    <br />
    <a href="#about-the-script">About The App</a>  |
    <a href="#features">Features</a>  |
    <a href= "#interface">Interface</a>  |
    <a href="#how-to-run">How to Run</a>  |
    <a href="#cicd-and-build">CI/CD and Build</a>     
  </p>
</div>

<br />
<br />

<!-- ABOUT THE PROJECT -->
## About The App

Password Generator GUI is a lightweight desktop application that lets you create strong, customizable passwords in seconds. 
Designed for simplicity and security, the app allows you to choose password length and character types — including uppercase letters, lowercase letters, digits, and symbols — and instantly copy the result to your clipboard. 
Built with `Python and tkinter`, it's perfect for daily use and personal security.

<p align="right"><a href="#top">Scroll up</a>


<!-- FEATURES -->
## Features

1. Adjustable password length `8 to 64 characters`,

2. Options to include:

   * Uppercase letters (A-Z),

   * Lowercase letters (a-z),

   * Digits (0-9),

   * Symbols (# $ & ! ? *).

3. Generate button,

4. One-click copy to clipboard.

<p align="right"><a href="#top">Scroll up</a>

<!-- Interface -->
## Interface

Clean and intuitive interface built with `tkinter`. Just select the desired options and click `Get a pssword`.


<!-- GETTING STARTED -->
## How to Run

1. Make sure Python 3.8+ is installed

2. Run the app with:

```
python main.py
```
or

```
python3 main.py
```

<p align="right"><a href="#top">Scroll up</a>

<!-- CI/CD and BUILD-->
## CI/CD and Build 

This project uses GitHub Actions to automate building the standalone `.exe` file for Windows.

During setup, I encountered and resolved a few issues:

* The `.github/workflows` folder was misspelled, so the `.yml` file appeared empty in GitHub Desktop, and the workflow didn’t trigger. 

* After correcting the folder name, the pipeline worked, but the resulting `.exe` wouldn’t launch on Windows.

* After troubleshooting and testing, I created a clean branch, committed the changes again, and successfully built a working version.

All issues were fixed — the `.exe` file is now properly built and runs as expected.

<p align="right"><a href="#top">Scroll up</a>
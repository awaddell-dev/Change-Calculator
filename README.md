# Change Calculator

A client-side web application that calculates monetary change and displays an animated breakdown of bills and coins. Built as part of the CCC Web 102 curriculum, this project demonstrates structured front-end development using vanilla web technologies.

---

## Live Demo

View the live project here:  
https://awaddell-dev.github.io/Change-Calculator/

---

## Features

* Calculates total change from amount due and amount received  
* Breaks change down into:
  * $20, $10, $5, $2, $1 bills  
  * Quarters, dimes, nickels, pennies  
* Animated number transitions using `requestAnimationFrame`  
* Slide-in results section  
* Conditional rendering (hides zero-value denominations)  
* Input validation with clear error messaging  
* Responsive layout for desktop and mobile  
* Modern dark money-themed UI    

---

## Tech Stack

* HTML5 – structure and markup  
* CSS3 – layout, responsiveness, and theming  
* JavaScript (ES6) – calculation logic, DOM manipulation, animation  
* Git – version control  
* GitHub Pages – deployment  

---

## Screenshots

### Initial Interface

![Initial Interface](images/ChangeCalc_main.png)

---

### Valid Input Entered

![Valid Input](images/ChangeCalc_input.png)

---

### Invalid Input State

Displays validation messaging when input is invalid or amount received is less than amount due.

![Invalid Input](images/ChangeCalc_invalid.png)

---

### Example Change Breakdown

![Change Breakdown](images/ChangeCalc_output.png)

---

## Installation & Usage

Clone the repository:

```bash
git clone git@github.com:awaddell-dev/Change-Calculator.git

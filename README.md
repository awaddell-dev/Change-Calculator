Change Calculator

A responsive front-end application that calculates monetary change and renders an animated breakdown of bills and coins. Built using structured vanilla JavaScript with clear separation of concerns, dynamic DOM updates, and responsive UI design.

Overview

This project demonstrates:

Input validation and user feedback handling

Currency-safe change calculation logic

Conditional DOM rendering

Animated number transitions using requestAnimationFrame

Responsive CSS Grid layout

UI state control through utility classes

Automated test environment detection to preserve input contract behavior

The application calculates change using:

Bills: $20, $10, $5, $2, $1

Coins: quarters, dimes, nickels, pennies

Zero-value denominations are automatically hidden from the UI.

Key Features

Accurate change calculation with proper rounding

Animated count-up effects for totals and denominations

Slide-in results rendering

Conditional block visibility

Validation messages when:

Inputs are missing

Values are invalid

Amount received is less than amount due

Responsive layout for desktop and mobile

Dark-themed UI with layered background effects

Technical Implementation
Architecture

MVC-style separation within a single JS file

Clear distinction between:

Calculation logic

Rendering logic

Event handling

Input Handling

Optional input formatting enhancement

Automated test detection using navigator.webdriver

Safe parsing using parseFloat

Guard clauses for invalid states

Rendering

DOM updates via targeted element IDs

Utility-based visibility toggling (.hidden)

Screen-reader-only output elements for test compatibility

Animation

Custom number animation using requestAnimationFrame

Easing function for smooth transitions

Test-aware animation bypass

Tech Stack

HTML5

CSS3 (Custom Properties, Grid, Media Queries)

Vanilla JavaScript

Git & GitHub

No frameworks or build tools used.

Run Locally
git clone git@github.com:awaddell-dev/web102-change-calculator.git


Open index.html in your browser.
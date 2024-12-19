# Tailwind CSS Button Centering Issue

This repository demonstrates a common issue encountered when using Tailwind CSS to center elements.  Specifically, a button within a flex container is not centering horizontally as expected.

## Problem
A simple login form is constructed using Tailwind CSS. The intention is to center the entire form on the screen and horizontally center the login button within the form. However, the button is not centered.

## Solution
The issue is resolved by ensuring that the button itself is also a flex item. By adding `flex` to the button's classes, it correctly inherits the centering properties of its parent container.
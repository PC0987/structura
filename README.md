# STRUCTURA

**Live demo:** https://pc0987.github.io/structura/

A browser-based structural analysis tool that solves beams using the Direct Stiffness Method. It runs fully in the browser, with no installation or backend needed.

## What it does

1. Solves beam problems with multiple load types
2. Draws the beam, loads and supports as an SVG diagram
3. Plots the results as charts using Chart.js
4. Shows the output in tabs so results are easy to read

## Tech used

JavaScript, SVG, Chart.js, HTML/CSS

## How it works

The beam is split into elements, a stiffness matrix is built for each one, and they are assembled into a global matrix. The tool then applies the supports and loads and solves for displacements, from which it finds reactions and internal forces.

## Run it locally

1. Download or clone this repo
2. Open index.html in any browser

## Author

Piyush Jain, Civil Engineering, IIT Gandhinagar

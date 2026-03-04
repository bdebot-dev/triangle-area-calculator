# Triangle Area Calculator

A small educational JavaScript tool that computes the area of a triangle using different geometric methods and explains each formula step by step.

The project is designed as a simple learning tool for mathematics and programming. It demonstrates how geometric formulas can be implemented in JavaScript while providing clear explanations of the underlying mathematical reasoning.

## Features

• Calculate the area of a triangle using multiple methods  
• Step-by-step explanation of each formula used  
• Automatic validation of triangle geometry  
• Interactive visualization of the triangle using HTML Canvas  
• Input verification and error handling  
• Clean and minimal interface using pure HTML, CSS, and JavaScript  

## Supported Calculation Methods

### Base and Height

Area is computed using the classical formula:

A = (base × height) / 2

This method illustrates the geometric idea that a triangle is half of a parallelogram.

### Right Triangle (Pythagorean Handling)

The area is computed from the two perpendicular sides:

A = (a × b) / 2

If one side is missing, the program can compute it using the Pythagorean theorem:

a² + b² = c²

The calculator can therefore:

• compute the hypotenuse from the two legs  
• compute a missing leg from the hypotenuse and another leg  
• verify whether three given sides form a right triangle  

### Three Sides (Heron's Formula)

If the three sides of the triangle are known, the area can be calculated using Heron's formula:

s = (a + b + c) / 2  
A = √( s(s − a)(s − b)(s − c) )

The program also checks the triangle inequality before performing the calculation.

## Visualization

The triangle is drawn dynamically using the HTML Canvas API.  
The diagram helps users visually understand the geometric configuration used in the calculation.

## Technologies

This project intentionally uses only simple web technologies:

• HTML  
• CSS  
• JavaScript (vanilla)  
• HTML Canvas

No frameworks or external libraries are required.

## Educational Purpose

This repository is intended as a small demonstrator for:

• geometry teaching  
• algorithmic thinking  
• JavaScript fundamentals  
• mathematical visualization in the browser

It can be used in classrooms, programming exercises, or self-learning contexts.

## How to Use

1. Download or clone the repository.
2. Open the HTML file in a web browser.
3. Select the triangle type.
4. Enter the required values.
5. Click **Calculate** to obtain the result and explanation.

## Possible Extensions

Future improvements could include:

• support for equilateral and isosceles triangles  
• coordinate-based triangle input (three points in a plane)  
• exportable step-by-step calculations  
• responsive UI improvements  
• unit handling (cm, m, etc.)

## License

Open for educational and personal use.
<img src="Docs/images/Satori_Logo.png" alt="Satori Logo" width="200">

# Satori - The Go-Playing Robotic Arm

## Introduction

Welcome to the GitHub repository for "Satori", a project that encompasses the essence of sudden enlightenment - much like its namesake in Zen Buddhism. Satori, in Zen, refers to a moment of profound awakening and understanding, and that's what we aim to achieve in the realm of AI and robotics with this project.

Satori is an innovative robot designed to play the ancient and complex board game, Go. This robot is not just a mechanical player; it's a fusion of intricate 3D printed parts, custom circuitry, a Raspberry Pi core, and sophisticated software that bridges the gap between artificial intelligence and physical interaction.

## Project Description

### The Hardware

- **3D Printed Parts**: Satori's structure is primarily made up of high-quality 3D printed components. These parts are engineered to provide the perfect balance of strength and flexibility needed for precise movements.
- **Custom Circuitry**: At the heart of Satori is a network of custom-designed circuits that manage everything from motor control to signal processing.
- **Raspberry Pi**: Serving as the brain of Satori, a Raspberry Pi orchestrates the overall operations, from interpreting visual data to making strategic decisions in the game.

### The Mechanics

- **Two-Axis Horizontal Robotic Arm**: Satori is equipped with a robotic arm capable of moving along two axes. This allows it to navigate the Go board with precision and agility.
- **Machine Vision**: Utilizing advanced machine vision technologies, Satori can accurately detect the layout of the Go board and the positions of the pieces.
- **Vacuum Pump with Suction Cup**: To interact with the Go pieces, Satori uses a suction cup connected to a vacuum pump. This enables it to pick up and move pieces with remarkable control.

### The Software

- **Board Layout Analysis**: After detecting the board layout through its machine vision system, Satori processes this information to understand the current state of the game.
- **Integration with Kitsue AI**: The true power of Satori comes from its integration with Kitsue, another AI developed for playing Go at superhuman levels. Satori sends the board layout to Kitsue via an API call. Kitsue then analyzes the game and returns the optimal move, which Satori executes on the physical board.

## Getting Started

- **Installation**: Instructions on assembling Satori, installing the necessary software, and connecting the hardware components.
- **Usage**: Guidelines on how to operate Satori, from setting up the Go board to initiating a game with Kitsue.
- **API Documentation**: Detailed information about the API used for communicating between Satori and Kitsue, including endpoint descriptions and data formats.

## Contributing

We welcome contributions from enthusiasts and experts alike. Whether you're interested in improving the mechanical design, enhancing the machine vision capabilities, or optimizing the AI integration, your input is invaluable. Please read our contributing guidelines for more information on how to get involved.

## License

Copyright 2024 Leif Huender

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the “Software”), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED “AS IS”, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.


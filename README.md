<h1>Arduino Step Motor Control for Image Processing</h1>

<h2>Introduction</h2>

<p>
    This Arduino sketch is part of the Image Processing - Color Detection project, developed by Onur Mert ANARAT
    as a term-end project for the "Image Processing" course at Karabük University. The project involves detecting
    and tracking specific colors in a live video feed and controlling hardware components based on the detected colors.
</p>

<h2>Arduino Code Overview</h2>

<p>
    The Arduino sketch (ASV_stepMotorFinal.ino) is responsible for controlling a stepper motor based on the color
    detection results received from the C# application. Here's a brief overview of the key functionalities
    implemented in the sketch:
</p>

<ul>
    <li><strong>Setup:</strong> Initializes the Arduino board, sets up serial communication, and defines pin modes.</li>
    <li><strong>Main Loop:</strong> Reads serial data from the C# application to determine the required motor movement.
        It maps the received values to the appropriate step count and adjusts the motor rotation accordingly.</li>
    <li><strong>Turning Functions:</strong> Implements functions to rotate the stepper motor clockwise (sagaDon) and
        counterclockwise (solaDon) based on the step count received from the C# application.</li>
    <li><strong>Position Adjustment:</strong> Updates the motor position based on the step count and adjusts the
        direction of rotation accordingly.</li>
    <li><strong>Step Stopping:</strong> Stops the motor rotation when the desired position is reached.</li>
</ul>

<h2>Usage</h2>

<p>
    To use this Arduino sketch:
</p>

<ol>
    <li>Connect the Arduino board to the computer.</li>
    <li>Upload the ASV_stepMotorFinal.ino sketch to the Arduino board using the Arduino IDE.</li>
    <li>Ensure that the serial communication settings match those defined in the C# application.</li>
    <li>Run the C# application for color detection and tracking.</li>
    <li>Observe the stepper motor's movement based on the color detection results.</li>
</ol>

<h2>Contributing</h2>

<p>
    Contributions to the project are welcome! If you'd like to contribute, please fork the repository, make your changes,
    and submit a pull request.
</p>

<h2>License</h2>

<p>
    This project is licensed under the MIT License. See the <a href="LICENSE">LICENSE</a> file for details.
</p>

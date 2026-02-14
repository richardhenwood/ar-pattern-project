#displaed ar-pattern-project

[ar-pattern-project online](https://richardhenwood.github.io/ar-pattern-project/)

## About

The project solves a problem I have. I have created a parametric pattern with
[Seamly2D](https://github.com/FashionFreedom/Seamly2D) and I want to
transfer markings onto fabric. I do not have a large format printer.

## Workflow

1. Use Seamly2D to create my shirt pattern pieces. 
2. In Seamly2D generate a layout and export it to SVG. 
3. Load the SVG into [Inkscape](https://github.com/inkscape/inkscape) and manually adjust pieces if necessary.
4. Load the SVG into [ar-project-pattern](https://github.com/richardhenwood/ar-pattern-project).
5. Calibrate the AR world to your surroundings and adjust the pattern to lay exactly over your fabric.
6. Mark the pattern onto the material with chalk.
7. Cut out the pattern and sew it up.

## Calibration

A screenshot of the calibration pattern
![25548188431456720](https://github.com/user-attachments/assets/e40b17a8-6e60-49fb-abdf-c265ccbda9fe)


The left thumbstick will translate the patten plane. The right thumbstick will
rotate the pattern plane using left and right. Up and down on the right
thumbstick will translate the pattern plane in the vertical direction. The
pattern plane is always projected horizontally. Take time to position the plan
perfectly on the fabric.

When the ar-pattern-project has AR mode enabled without loading a costom
pattern SVG file a 'reference' pattern is shown. This pattern includes a 1M
reference square. Use this square to verify that the projection is correctly
calibrated. Use known measurements on your SVG pattern to ensure the chalk
pattern that you transferred onto the fabric is correctly calibrated.

## Alternatives

 + Use some tools to convert the large SVG into multiple A4 pages for printing. Print them and then tape them together.
 + Use a projector to project the pattern onto fabric. This requires calibration of the projector.
 + Use a flatbed laser cutter.

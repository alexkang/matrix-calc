[FALL 2013] MatrixCalculator
============================


DESCRIPTION
------------------------------------------
This is a python application that lets you compute basic matrix operations.

Current features include:
    -addition
    -subtraction
    -multiplication
    -scalar multiplication
    -transpose
    -determinant
    -inverse

CHANGES
------------------------------------------
v0.1.0, 2013/10/07 -- Initial release.

v0.1.1, 2013/10/07 -- Finished implementing all matrix functions and reorganized some code. Also added a changelog.

v0.1.2, 2013/10/07 -- Revised README file and put changelog within the README. Reworked some prompt_row function in matrixcalc_ui.py so that it doesn't break abstraction barriers.

v0.1.3, 2013/10/07 -- No changes. Trying to fix bug where pip installs wrong version.

v0.1.4, 2013/10/07 -- Fixed bugs and reuploaded package.

v0.1.5, 2013/10/07 -- Updated README to reflect accurate methods of installation.

v0.1.6, 2013/10/08 -- Added inverses! Fixed grammar and formatting errors.

v0.1.7, 2013/10/11 -- STARTED IMPLEMENTING A GUI! As of now, using tkinter to display a new interface to input matrices. Added error message if trying to invert a non-invertible matrix. Fixed bug where you can't invert a 2x2 matrix. 

INSTALLATION
------------------------------------------
Installation of MatrixCalculator requires pip-3.x. If you have Ubuntu 13.04 or newer, install it by typing in, "sudo apt-get install python3-pip". If you have an older version of Ubuntu, follow the instructions here: 

http://stackoverflow.com/a/11272201

If your OS doesn't work with these methods, download the source file on the PyPi site, extract it, cd into its location, and type in "sudo python3 setup.py install".

Before you install make sure your version of pip is at least 1.4.1 so that upgrading works. To install the program, type in the terminal: "sudo pip-3.x install MatrixCalculator". (replace "x" with your version of Python 3)

USING MATRIXCALCULATOR
-------------------------------------------
To run the program, type in, "matrixcalculator" into the terminal.

UNINSTALLATION
-------------------------------------------
To uninstall the program, type in, "sudo pip-3.x uninstall MatrixCalculator" (with x being the version of Python 3 you have).

MEETFLIP: Mechanical Evaluation of Esophageal Topography via FLIP
Overview: A MATLAB AppDesigner Application for Processing and Visualizing EndoFLIP Data
MEETFLIP (Mechanical Evaluation of Esophageal Topography via FLIP) is a custom MATLAB AppDesigner application created to support gastroenterology research in esophageal biomechanics, with a particular focus on eosinophilic esophagitis (EoE). The software provides a consistent framework for processing EndoFLIP® (Medtronic) impedance planimetry data, visualizing esophageal dynamics, and computing metrics relevant to luminal stiffness and distensibility. The application was originally developed in collaboration with clinical gastroenterologists seeking a platform to help interpret post-hoc data and identify regions of reduced esophageal compliance.

Input Requirements:
MEETFLIP expects .txt files exported from the EndoFLIP® system, formatted according to the standard Medtronic export structure:
Column 1: Timestamp (formatted dd-mmm-yyyy HH:MM:SS).
Columns 4–19: Diameters at electrodes (16 channels).
Column 20: Intrabag pressure (mmHg).
Column 21: Balloon volume (mL).
Note: This repository does not include real clinical data. Users must supply their own de-identified exports.

Installation Requirements:
MATLAB R2020b or newer.
No specialized toolboxes required.
AppDesigner-compatible environment.

Workflow details are outlined in the text.  
To get started, use "Search Folder" to select the directory containing your .txt file(s). Select the filename from the drop down menu and click "Start/Upload File".


# running_hysplit_storms
This repository contains the necessary Python and batch codes to analyze moisture content using the Papritz method. Additionally, it contains a manual to explain the code.

==== IN THIS REPOSITORY ====

main_code.ipynb: a python notebook with all the python functions with markdown explanations, the content of the markdown cells is very similar to this manual so you do not need to read both for a clear picture. Information about the batch files is not here. 

functions_code.py: a python file that holds just the functions but no markdown explanations. You can identify what sections of the code correspond to this manual using the comments.

code_manual.docx: a Word Document with information on how to run the code

run_hysplit_multilevel.bat: a batch file that allows HYSPLIT runs for multiple levels of one storm in succession

run_hysplit_singlelevel.bat: a batch file that allows HYSPLIT runs for a single level of a storm

ASCDATA.CFG: a ASCII file that contains gridded land-use, terrain, and roughness length data for HYSPLIT. 

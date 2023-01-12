## Vynnycky and White, summerepi2 validation
This repository is a validation of the summerepi2 package to the textbook:
"An Introduction to Infectious Disease Modelling" by Emilia Vynnycky and Richard G White.
The repository is intended to demonstrate equivalent epidemiological behaviours between
the summerepi2 package and the models described in the textbook.
This is intended primarily as a validation of the summerepi2 platform
(although could also be considered as a validation of the textbook outputs).
The validation was done using three approaches:
1. Validation of the figures that appear in the printed version of the textbook
2. Validation of the figures that appear in the Excel example files
3. Validation of the numeric outputs in the Excel example files
This repository contains the outputs for the first two validation approaches.
Visual inspection of the outputs from these two sets of notebooks is intended to
illustrate similar epidemiological dynamics between the two approaches.
The process of validation of the numeric results has been done through Python tests
which can then be run in continuous integration.
These tests are located within the summer2 repository (tests/text_external_data folder)
at https://github.com/monash-emu/summer2/tree/main/tests/test_external_data.
These tets formally check the numeric differences between the two approaches
and only pass where the difference remains below a certain tolerance value.

Textbook:
Several new hard copies of Vynnycky and White were ordered from amazon.com.au on 13th June 2022
(sold by Amazon Commercial Services Pty Ltd).
An image of the information from the details page of these books is provided in the `./supporting_docs/` folder.
The images were generated from a PDF version of the textbook found online.
This was found to be identical to the hard copy version of the textbook,
except for one figure, as described in the relevant notebook
(for which the difference pertains to the positioning of figures within panels).
These examples are illustrated in the notebooks in the `./text_figures/` folder.

Online examples:
The example spreadsheets in Excel were downloaded from the following URL:
https://anintroductiontoinfectiousdiseasemodelling.com/wp-content/uploads/2022/04/Model-Files-006-04-04-22.zip
on 5th December 2022.
All Excel spreadsheets were saved in the ./excel_examples/spreadsheets/ folder of this repository.
Many examples are also available from Vynnycky and White in Berkeley Madonna;
these implementations were not considered.
These examples are illustrated in the notebooks in the `./excel_examples/` folder.
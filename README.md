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
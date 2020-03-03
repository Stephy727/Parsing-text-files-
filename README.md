# Parsing-text-files-
Extracting data from semi-structured text files. 

This project touches the very first step of analyzing textual data, i.e., extracting data from semi-structured text files. 

Each data-set contains information about the unit, e.g., unit
code, unit title, synopsis, requirements, output, chief examiner, etc. ( see test.txt ). Task is to
extract the data and transform the data into the XML and JSON format with the following
elements:
1. Unit code: is a 7-character string (three uppercase letter followed by 4 digits).
2. Pre-requisites: only the unit codes of the units that are pre-requisite + co-requisite for
the current unit (‘NA’ if the value is Null).
3. Prohibitions: only the unit codes of the units that are prohibited to be taken with the
current unit (‘NA’ if the value is Null).
4. Synopsis: a string containing the synopsis of the unit (‘NA’ if the value is Null)
5. Requirements: the list of requirements of the current unit (‘NA’ if the value is Null).
6. Outputs: the list of outputs of the current unit (‘NA’ if the value is Null).
7. Chief-examiners: the list of the chief-examiners of the current unit (‘TBA’ if Null).

For this task, the re and the json packages in Python are the only packages
that are used to, 

● Designing efficient regular expressions in order to extract the data from your dataset

● Storing and submitting the extracted data into an XML file

● Storing and submitting the extracted data into a JSON file

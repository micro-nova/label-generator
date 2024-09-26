# Label Generator Scripts
## Script used to generate an AmpliPro label
### Usage
- Firstly, configure the label printer as a CUPS printer, and set the defaults to 
  - 300 dpi
  - 1.5x0.5 inch media size.
- make-label:
  - utility script to make an amplipro label
  - run make-label and it will prompt you for the necessary information and print a label
- label-gen:
  - script to generate the label with arbirary serial number and model number
  - takes in args as shown below:
      - `label_gen <serial_number> <model_number> [-s]`
      - `serial number` is the serial number of the unit e.g. 123
      - `model_number` is the model number of the unit e.g. AP1-S4Z6
      - `-s` will skip printing and deleting the label leaving you with a pdf, this is useful for testing
### Requirements
- Inkscape
- Barcode
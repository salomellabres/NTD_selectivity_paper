# FEP input files

Using ti.in as a template, an input file is generated for each lambda and the corresponding transformation.

The variables $LAMBDA, $MOL1-MASK and $MOL2-MASK should be changed accordingly for the following transformations:

- **$LAMBDA**
  From 0.00 to 1.00 in a 0.05 interval in this work.

- **C5N_CHL**
  $MOL1-MASK = ':1@C57,C58,C59,C60,C61,C62,H81,H82,H83,H84,H85,H86,H87,H88'
  $MOL2-MASK = ':2@C1,C2,C3,C4,C5,C10,O1,H1,H2,H3,H4,H5,H6,H7,H8'

- **CHL_C5N**
  Like above interchanging $MOL1-MASK and $MOL2-MASK.

- **C5N_ECL**
  $MOL1-MASK = ':1@C57,C58,C59,C60,C61,C62,H81,H82,H83,H84,H85,H86,H87,H88'
  $MOL2-MASK = ':2@C51,C52,C53,C54,C55,C56,O2,H71,H72,H73,H74,H75,H76,H77,H78'

- **ECL_C5N**
  Like above interchanging $MOL1-MASK and $MOL2-MASK.

- **CHL_ECL**
  $MOL1-MASK = ':1@C1,C2,C3,C4,C5,C10,O1,H1,H2,H3,H4,H5,H6,H7,H8'
  $MOL2-MASK = ':2@C51,C52,C53,C54,C55,C56,O2,H71,H72,H73,H74,H75,H76,H77,H78'

- **ECL_CHL**
  Like above interchanging $MOL1-MASK and $MOL2-MASK.

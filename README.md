# strainGauge
WIP Python scripts for processing the voltage data from our Arduino (make sure the readArduino.ino file is running before processData.py is run)

Calculates the Strain, the Theoretical Force applied to create this strain, and the Percentage Error relative to the actual force that produced this strain.

Provides live graph of our Voltage v. Calculated Quantities; writes data to a CSV file which we can import into Excel/Sheets afterwards.

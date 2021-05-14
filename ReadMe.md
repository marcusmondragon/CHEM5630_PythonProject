# **<ins>README<ins>**

The purpose of this code is to create individual spectra and an overlay of all spectra from multiple CSV files from an automatically generated file by the OMNIC software for FTIR spectroscopy. This code is designed to read automatically generated files, and therefore, any changes in filenames which differ from the automatically generated files will not work properly.

## **Automatically Generated File from OMNIC:**
When saving an OMNIC spectrum as a CSV file type, the program defaults the file name to, for example, “@Mon Nov 04 10-12-22 2019 (GMT-07-00)” . The order of the information  in the file name is: (Day of week, Month, Date, Time, Year, Time Zone). The contents of the file are comma separated values in two columns. The left column contains the wavenumber in which the absorbance was recorded. The right column contains the absorbance at said wavenumber.

## **Jupyter Notebook file:**
The code contained in the Jupyter Notebook file titled, “CHEM5630_MarcusMondragon_FinalProject”, is capable of extracting the date and time in which the spectra was recorded, as well as, generating plots for each individual spectrum and an overlay plot of all spectra. The code was designed for multiple file inputs and should be used accordingly. The purpose of each line of code is described as a comment in the Jupyter Notebook file.

## **Example Input Files:**
Contained in the git repository are 21 example input files needed to run the Jupyer Notebook File. These files contain the data for water absorbance on thin-film Phenothrin at different times for changes in relative humidity in a reaction chamber. These files should be contained in a sub-directory of the working directory. The sub-directory is named “Input Files”.

## **~RUN JUPYTER NOTEBOOK~**

## **Example Output Files:**
After running the Jupyter Notebook file, a sub-directory named “FullSpectra” is created containing the individual plots of the full spectrum for each file in the Input Files. The file name should be “Phenothrin_WaterAbsorbance_Time_ -date_time-.png”. An example of this is a file that is created titled “Phenothrin_WaterAbsorbance_Time_Nov 04 2019_10-12-22.png”. The overlay plot is generated as a file named, “Phenothrin_WaterAbsorbance Nov 04 2019.png” which is located in the main directory.

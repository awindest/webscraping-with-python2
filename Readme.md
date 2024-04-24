The Visual Component Tree reads in three files: 
//    const promises = [
//       d3.json('data/ComponentDescriptions.json'),
//       d3.csv('data/TalendComponents.csv'),
//       d3.json('data/translations.json')
//     ]
the translations.json file should not change but the ComponentDescriptions.json and TalendComponents.csv files change with the versions of the Talend Data Fabric (or Studio).
To create these files, first check that the output file names are correct and that the options for scraping the web site are appropriate for the version you are targeting.
(% jupyter notebook)
First run:
Web scrape Talendforge v8 and get icon images.ipynb
then run:
DataForTidyTreeD3.ipynb


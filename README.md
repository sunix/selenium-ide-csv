# selenium-ide-csv
A small script to import data from a CSV file to a CMS through its UI thanks to selenium IDE


## Requirements:
- Firefox
- Selenium IDE Firefox addon <https://addons.mozilla.org/fr/firefox/addon/selenium-ide/>
- Selblock <https://addons.mozilla.org/fr/firefox/addon/selenium-ide-sel-blocks/>
- CSV Reader, In Selenium IDE (Ctrl + alt + s), download <https://github.com/abhijain2618/csvreader/blob/master/CSVRead_Selenium-IDE.js> and install it as a Selenium extension: `Options` > `Options` > `Selenium Core extensions` > Select the downloaded file.

## Start the script

- Manually loggin into the site, close all the windows inside the application.
- Open Selenium IDE (Ctrl + alt + s )
- Open the test case `add_new_candidates_from_csv.html`
- Replace `line` value with the wanted start line
- Replace the while end value with the wanted end line
- Replace the location of the CSV file to process
- Run the test case


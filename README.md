# user-api-testing-jmeter
User Api Testing using jmeter.
1. Download the .jmx file
2. Open CMD or your CLI mode
Type the following commands:

```jmeter -n -t [path of the dot jmx file] -l [path of thr reports.csv file] -e -o [blank folder html path to generate html report] ```


3. here
``` -n ```  instruct jmeter run the test in non-GUI mode
``` -t ```  specify the path of .jmx file.
``` -l```    instruct to write into log file results
``` -e -o ```  location of the output folder

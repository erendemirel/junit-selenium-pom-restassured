This is a sample test project with JUnit 5 that performs UI tests on https://www.n11.com/ and API tests on demo sites http://dummy.restapiexample.com/ and http://thedemosite.co.uk/login.php using Selenium WebDriver and Rest-assured library. The project is setup using Page Object Model(POM) with Page Factory

#### Running the Tests
- **Change browser name and driver paths in** *config.properties* **under** */config*. Currently supported browsers: *Chrome* and *Firefox*
- **There's a single feature file:** *testfeature.feature*. All tests run via this feature. Also the API tests under *src/test/java/restapitests/APITests.java* class can run independently 
#### File Locations
- The project produces a log file and a txt file for general purpose. These files are produced under project directory by default. The paths are *src/main/resources/logfile.log* and *src/main/resources/productinfo.txt*
- The test data is kept inside and read from a JSON file. Path to this file is *testdata/testdata.json*

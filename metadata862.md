Preparing Test Run Test run on 14:57
Resolving Executable Test Suite dependencies
Preparing 3 Test Task:
 TestTask 1 (3f988aa1-66d9-4f1d-a507-e7ef3a05f904)
 will perform tests on Test Object 'csw-inspire.xml' by using Executable Test Suite 'LAZY.59692c11-df86-49ad-be7f-94a1e1ddd8da'
 with parameters: 
tests_to_execute = .*
files_to_test = .*
 TestTask 2 (9c26c071-5c00-4e51-aa1e-d601b851ad38)
 will perform tests on Test Object 'csw-inspire.xml' by using Executable Test Suite 'LAZY.e4a95862-9cc9-436b-9fdd-a0115d342350'
 with parameters: 
tests_to_execute = .*
files_to_test = .*
 TestTask 3 (3f24c487-cbd9-4aaa-b5ce-0ec08fdd86c6)
 will perform tests on Test Object 'csw-inspire.xml' by using Executable Test Suite 'Conformance Class 2: INSPIRE data sets and data set series interoperability metadata. (EID: 2be1480a-fe42-40b2-9420-eb0e69385c80, V: 1.0.1 )'
 with parameters: 
tests_to_execute = .*
files_to_test = .*
Test Tasks prepared and ready to be executed. Waiting for the scheduler to start.
Setting state to CREATED
Changed state from CREATED to INITIALIZING
Starting TestRun.844e60d3-d79d-48e6-877c-cf1cba80db4a at 2022-10-26T12:58:04Z
Changed state from INITIALIZING to INITIALIZED
TestRunTask initialized
Creating new tests databases to speed up tests.
Skipping schema validation because no schema file has been set in the test suite. Data are only checked for well-formedness.
Optimizing last database etf-tdb-3280effb-e86e-4d57-a65d-a96bb4fb8dbc-0 
Import completed
Validation ended with 0 error(s)
Compiling test script
Starting XQuery tests
Testing 1 records
Executing Test Suite: /etf/projects/inspire-ets-repository/ets-repository-2022.3/metadata/2.0/common/ets-md-common-bsxets.xml
Statistics table: 0 ms
Test Suite 'Common Requirements for ISO/TC 19139:2007 based INSPIRE metadata records.' started
Test Case 'General requirements' started
Test Assertion 'md common req C.1: XML Schema': FAILED#1684 ms
Test Assertion 'md common req C.2: Root Element': PASSED#0 ms
Test Assertion 'md common req C.5: Language Code': PASSED#0 ms
Test Assertion 'md common req C.6: Metadata Point of Contact': PASSED#0 ms
Test Assertion 'md common req C.7: Metadata Date': PASSED#23 ms
Test Case 'General requirements' finished: FAILED
Test Case 'Identification' started
Test Assertion 'md common req C.8: Resource Title': PASSED#0 ms
Test Assertion 'md common req C.9: Resource Abstract': PASSED#0 ms
Email Char: 1
Email Anch: 0
Test Assertion 'md common req C.10: Responsible Organization': PASSED#0 ms
Test Assertion 'md common req C.11: Temporal Reference': PASSED#7 ms
Test Assertion 'md common req C.12: Max One Date of Creation': PASSED#0 ms
Test Assertion 'md common req C.13: Not More than one Date of Last Revision': PASSED#0 ms
Test Assertion 'md common req C.14: Temporal Extent': PASSED#60 ms
Test Assertion 'md common req C.15: Keyword Originating CV': PASSED#0 ms
Test Assertion 'md common req C.16: Group Keywords by CV': PASSED#0 ms
Test Assertion 'md common req C.17: Limitations on Public Access': PASSED#0 ms
Test Assertion 'md common req C.18: Conditions for Access and Use': PASSED#0 ms
Test Assertion 'md common req C.19: Geographical Bounding Box': PASSED#0 ms
Test Case 'Identification' finished: PASSED
Test Case 'Data quality' started
Test Assertion 'md common req C.20: Dataset Conformity': PASSED#0 ms
Test Assertion 'md common req C.21: Dataset Conformity Specifications': PASSED#8 ms
Test Assertion 'md common req C.22: Conformity Degree': PASSED#0 ms
Test Case 'Data quality' finished: PASSED
Test Suite 'Common Requirements for ISO/TC 19139:2007 based INSPIRE metadata records.' finished: FAILED
Releasing resources
TestRunTask initialized
Recreating new tests databases as the Test Object has changed!
Skipping schema validation because no schema file has been set in the test suite. Data are only checked for well-formedness.
Optimizing last database etf-tdb-3280effb-e86e-4d57-a65d-a96bb4fb8dbc-0 
Import completed
Validation ended with 0 error(s)
Compiling test script
Starting XQuery tests
Testing 1 records
Executing Test Suite: /etf/projects/inspire-ets-repository/ets-repository-2022.3/metadata/2.0/datasets-and-series/ets-md-datasets-and-series-bsxets.xml
Statistics table: 0 ms
Test Suite 'Conformance Class 1: INSPIRE data sets and data set series baseline metadata.' started
Test Case 'General Metadata' started
Test Assertion 'md datasets-and-series 1.1: Resource Type': PASSED#0 ms
Test Case 'General Metadata' finished: PASSED
Test Case 'Identification' started
Test Assertion 'md datasets-and-series 1.2: Only One Data Identification': PASSED#0 ms
Test Assertion 'md datasets-and-series 1.3: Dataset UID': PASSED#1 ms
Checking URL: 'https://inspire.ec.europa.eu/theme/theme.bg.atom'
Checking URL: 'https://inspire.ec.europa.eu/theme/theme.cs.atom'
Checking URL: 'https://inspire.ec.europa.eu/theme/theme.da.atom'
Checking URL: 'https://inspire.ec.europa.eu/theme/theme.de.atom'
Checking URL: 'https://inspire.ec.europa.eu/theme/theme.et.atom'
Checking URL: 'https://inspire.ec.europa.eu/theme/theme.el.atom'
Checking URL: 'https://inspire.ec.europa.eu/theme/theme.en.atom'
Checking URL: 'https://inspire.ec.europa.eu/theme/theme.es.atom'
Checking URL: 'https://inspire.ec.europa.eu/theme/theme.fr.atom'
Checking URL: 'https://inspire.ec.europa.eu/theme/theme.hr.atom'
Checking URL: 'https://inspire.ec.europa.eu/theme/theme.it.atom'
Checking URL: 'https://inspire.ec.europa.eu/theme/theme.lv.atom'
Checking URL: 'https://inspire.ec.europa.eu/theme/theme.lt.atom'
Checking URL: 'https://inspire.ec.europa.eu/theme/theme.hu.atom'
Checking URL: 'https://inspire.ec.europa.eu/theme/theme.mt.atom'
Checking URL: 'https://inspire.ec.europa.eu/theme/theme.nl.atom'
Checking URL: 'https://inspire.ec.europa.eu/theme/theme.pl.atom'
Checking URL: 'https://inspire.ec.europa.eu/theme/theme.pt.atom'
Checking URL: 'https://inspire.ec.europa.eu/theme/theme.ro.atom'
Checking URL: 'https://inspire.ec.europa.eu/theme/theme.sk.atom'
Checking URL: 'https://inspire.ec.europa.eu/theme/theme.sl.atom'
Checking URL: 'https://inspire.ec.europa.eu/theme/theme.fi.atom'
Checking URL: 'https://inspire.ec.europa.eu/theme/theme.sv.atom'
Checking URL: 'https://inspire.ec.europa.eu/theme/theme.en.atom'
Test Assertion 'md datasets-and-series 1.4: INSPIRE Theme Keyword': PASSED#11473 ms
Test Assertion 'md datasets-and-series 1.5: Spatial Resolution': PASSED#1 ms
Test Assertion 'md datasets-and-series 1.6: Resource Language': PASSED#0 ms
Test Assertion 'md datasets-and-series 1.7: Topic Category': PASSED#0 ms
Test Case 'Identification' finished: PASSED
Test Case 'Distribution' started
Test Assertion 'md datasets-and-series 1.8: Resource Locator': PASSED#1 ms
Test Assertion 'md datasets-and-series 1.9: Data Quality Info Section': PASSED#0 ms
Code list value: Kommissionens fÃ¶rordning (eu) nr 1089/2010 av den 23 november 2010 om genomfÃ¶rande av Europaparlamentets och rÃ¥dets direktiv 2007/2/eg vad gÃ¤ller interoperabilitet fÃ¶r rumsliga datamÃ¤ngder och datatjÃ¤nster
Code list value: Kommissionens fÃ¶rordning (eu) nr 1089/2010 av den 23 november 2010 om genomfÃ¶rande av Europaparlamentets och rÃ¥dets direktiv 2007/2/eg vad gÃ¤ller interoperabilitet fÃ¶r rumsliga datamÃ¤ngder och datatjÃ¤nster
Code list value: publication
Code list value: publication
Test Assertion 'md datasets-and-series 1.10: Dataset Conformity': PASSED#29 ms
Test Assertion 'md datasets-and-series 1.11: Lineage': PASSED#0 ms
Test Case 'Distribution' finished: PASSED
Test Suite 'Conformance Class 1: INSPIRE data sets and data set series baseline metadata.' finished: PASSED
Releasing resources
TestRunTask initialized
Recreating new tests databases as the Test Object has changed!
Skipping schema validation because no schema file has been set in the test suite. Data are only checked for well-formedness.
Optimizing last database etf-tdb-3280effb-e86e-4d57-a65d-a96bb4fb8dbc-0 
Import completed
Validation ended with 0 error(s)
Compiling test script
Starting XQuery tests
Testing 1 records
Executing Test Suite: /etf/projects/inspire-ets-repository/ets-repository-2022.3/metadata/2.0/datasets-and-series/ets-md-isdss-bsxets.xml
Statistics table: 0 ms
Test Suite 'Conformance Class 2: INSPIRE data sets and data set series interoperability metadata.' started
Test Case 'General Metadata' started
Test Assertion 'md isdss 2.1: Coordinate Reference System': PASSED#0 ms
Test Assertion 'md isdss 2.2: Coordinate Reference System Identifiers': PASSED#0 ms
Test Assertion 'md isdss 2.3: Temporal Reference Systems': PASSED#0 ms
Test Case 'General Metadata' finished: PASSED
Test Case 'Identification' started
Test Assertion 'md isdss 2.4: Spatial Representation Type': PASSED#0 ms
Test Assertion 'md isdss 2.5: Character Encoding': PASSED#0 ms
Test Case 'Identification' finished: PASSED
Test Case 'Distribution' started
Test Assertion 'md isdss 2.6: Data Encoding': PASSED#0 ms
Test Case 'Distribution' finished: PASSED
Test Case 'Data Quality' started
Test Assertion 'md isdss 2.7: Topological Consistency Quantitative Results': PASSED#0 ms
Test Assertion 'md isdss 2.8: Topological Consistency Descriptive Results': PASSED#0 ms
Test Case 'Data Quality' finished: PASSED
Test Suite 'Conformance Class 2: INSPIRE data sets and data set series interoperability metadata.' finished: PASSED
Releasing resources
Changed state from INITIALIZED to RUNNING
Duration: 16sec
TestRun finished
Changed state from RUNNING to COMPLETED

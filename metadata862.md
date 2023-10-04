26.10.2022 12:58:02 - Preparing Test Run Test run on 14:57 - 26.10.2022 with test suite Conformance Class 2: INSPIRE data sets and data set series interoperability metadata. (initiated Wed Oct 26 12:58:02 UTC 2022)
26.10.2022 12:58:02 - Resolving Executable Test Suite dependencies
26.10.2022 12:58:02 - Preparing 3 Test Task:
26.10.2022 12:58:02 -  TestTask 1 (3f988aa1-66d9-4f1d-a507-e7ef3a05f904)
26.10.2022 12:58:02 -  will perform tests on Test Object 'csw-inspire.xml' by using Executable Test Suite 'LAZY.59692c11-df86-49ad-be7f-94a1e1ddd8da'
26.10.2022 12:58:02 -  with parameters: 
26.10.2022 12:58:02 - tests_to_execute = .*
26.10.2022 12:58:02 - files_to_test = .*
26.10.2022 12:58:02 -  TestTask 2 (9c26c071-5c00-4e51-aa1e-d601b851ad38)
26.10.2022 12:58:02 -  will perform tests on Test Object 'csw-inspire.xml' by using Executable Test Suite 'LAZY.e4a95862-9cc9-436b-9fdd-a0115d342350'
26.10.2022 12:58:02 -  with parameters: 
26.10.2022 12:58:02 - tests_to_execute = .*
26.10.2022 12:58:02 - files_to_test = .*
26.10.2022 12:58:02 -  TestTask 3 (3f24c487-cbd9-4aaa-b5ce-0ec08fdd86c6)
26.10.2022 12:58:02 -  will perform tests on Test Object 'csw-inspire.xml' by using Executable Test Suite 'Conformance Class 2: INSPIRE data sets and data set series interoperability metadata. (EID: 2be1480a-fe42-40b2-9420-eb0e69385c80, V: 1.0.1 )'
26.10.2022 12:58:02 -  with parameters: 
26.10.2022 12:58:02 - tests_to_execute = .*
26.10.2022 12:58:02 - files_to_test = .*
26.10.2022 12:58:02 - Test Tasks prepared and ready to be executed. Waiting for the scheduler to start.
26.10.2022 12:58:02 - Setting state to CREATED
26.10.2022 12:58:02 - Changed state from CREATED to INITIALIZING
26.10.2022 12:58:02 - Starting TestRun.844e60d3-d79d-48e6-877c-cf1cba80db4a at 2022-10-26T12:58:04Z
26.10.2022 12:58:04 - Changed state from INITIALIZING to INITIALIZED
26.10.2022 12:58:04 - TestRunTask initialized
26.10.2022 12:58:04 - Creating new tests databases to speed up tests.
26.10.2022 12:58:04 - Skipping schema validation because no schema file has been set in the test suite. Data are only checked for well-formedness.
26.10.2022 12:58:04 - Optimizing last database etf-tdb-3280effb-e86e-4d57-a65d-a96bb4fb8dbc-0 
26.10.2022 12:58:04 - Import completed
26.10.2022 12:58:04 - Validation ended with 0 error(s)
26.10.2022 12:58:04 - Compiling test script
26.10.2022 12:58:04 - Starting XQuery tests
26.10.2022 12:58:04 - "Testing 1 records"
26.10.2022 12:58:04 - "Executing Test Suite: /etf/projects/inspire-ets-repository/ets-repository-2022.3/metadata/2.0/common/ets-md-common-bsxets.xml"
26.10.2022 12:58:04 - "Statistics table: 0 ms"
26.10.2022 12:58:04 - "Test Suite 'Common Requirements for ISO/TC 19139:2007 based INSPIRE metadata records.' started"
26.10.2022 12:58:04 - "Test Case 'General requirements' started"
26.10.2022 12:58:06 - "Test Assertion 'md common req C.1: XML Schema': FAILED - 1684 ms"
26.10.2022 12:58:06 - "Test Assertion 'md common req C.2: Root Element': PASSED - 0 ms"
26.10.2022 12:58:06 - "Test Assertion 'md common req C.5: Language Code': PASSED - 0 ms"
26.10.2022 12:58:06 - "Test Assertion 'md common req C.6: Metadata Point of Contact': PASSED - 0 ms"
26.10.2022 12:58:06 - "Test Assertion 'md common req C.7: Metadata Date': PASSED - 23 ms"
26.10.2022 12:58:06 - "Test Case 'General requirements' finished: FAILED"
26.10.2022 12:58:06 - "Test Case 'Identification' started"
26.10.2022 12:58:06 - "Test Assertion 'md common req C.8: Resource Title': PASSED - 0 ms"
26.10.2022 12:58:06 - "Test Assertion 'md common req C.9: Resource Abstract': PASSED - 0 ms"
26.10.2022 12:58:06 - "Email Char: 1"
26.10.2022 12:58:06 - "Email Anch: 0"
26.10.2022 12:58:06 - "Test Assertion 'md common req C.10: Responsible Organization': PASSED - 0 ms"
26.10.2022 12:58:06 - "Test Assertion 'md common req C.11: Temporal Reference': PASSED - 7 ms"
26.10.2022 12:58:06 - "Test Assertion 'md common req C.12: Max One Date of Creation': PASSED - 0 ms"
26.10.2022 12:58:06 - "Test Assertion 'md common req C.13: Not More than one Date of Last Revision': PASSED - 0 ms"
26.10.2022 12:58:06 - "Test Assertion 'md common req C.14: Temporal Extent': PASSED - 60 ms"
26.10.2022 12:58:06 - "Test Assertion 'md common req C.15: Keyword Originating CV': PASSED - 0 ms"
26.10.2022 12:58:06 - "Test Assertion 'md common req C.16: Group Keywords by CV': PASSED - 0 ms"
26.10.2022 12:58:06 - "Test Assertion 'md common req C.17: Limitations on Public Access': PASSED - 0 ms"
26.10.2022 12:58:06 - "Test Assertion 'md common req C.18: Conditions for Access and Use': PASSED - 0 ms"
26.10.2022 12:58:06 - "Test Assertion 'md common req C.19: Geographical Bounding Box': PASSED - 0 ms"
26.10.2022 12:58:06 - "Test Case 'Identification' finished: PASSED"
26.10.2022 12:58:06 - "Test Case 'Data quality' started"
26.10.2022 12:58:06 - "Test Assertion 'md common req C.20: Dataset Conformity': PASSED - 0 ms"
26.10.2022 12:58:06 - "Test Assertion 'md common req C.21: Dataset Conformity Specifications': PASSED - 8 ms"
26.10.2022 12:58:06 - "Test Assertion 'md common req C.22: Conformity Degree': PASSED - 0 ms"
26.10.2022 12:58:06 - "Test Case 'Data quality' finished: PASSED"
26.10.2022 12:58:06 - "Test Suite 'Common Requirements for ISO/TC 19139:2007 based INSPIRE metadata records.' finished: FAILED"
26.10.2022 12:58:06 - Releasing resources
26.10.2022 12:58:06 - TestRunTask initialized
26.10.2022 12:58:06 - Recreating new tests databases as the Test Object has changed!
26.10.2022 12:58:06 - Skipping schema validation because no schema file has been set in the test suite. Data are only checked for well-formedness.
26.10.2022 12:58:06 - Optimizing last database etf-tdb-3280effb-e86e-4d57-a65d-a96bb4fb8dbc-0 
26.10.2022 12:58:06 - Import completed
26.10.2022 12:58:06 - Validation ended with 0 error(s)
26.10.2022 12:58:06 - Compiling test script
26.10.2022 12:58:06 - Starting XQuery tests
26.10.2022 12:58:06 - "Testing 1 records"
26.10.2022 12:58:06 - "Executing Test Suite: /etf/projects/inspire-ets-repository/ets-repository-2022.3/metadata/2.0/datasets-and-series/ets-md-datasets-and-series-bsxets.xml"
26.10.2022 12:58:06 - "Statistics table: 0 ms"
26.10.2022 12:58:06 - "Test Suite 'Conformance Class 1: INSPIRE data sets and data set series baseline metadata.' started"
26.10.2022 12:58:06 - "Test Case 'General Metadata' started"
26.10.2022 12:58:06 - "Test Assertion 'md datasets-and-series 1.1: Resource Type': PASSED - 0 ms"
26.10.2022 12:58:06 - "Test Case 'General Metadata' finished: PASSED"
26.10.2022 12:58:06 - "Test Case 'Identification' started"
26.10.2022 12:58:06 - "Test Assertion 'md datasets-and-series 1.2: Only One Data Identification': PASSED - 0 ms"
26.10.2022 12:58:06 - "Test Assertion 'md datasets-and-series 1.3: Dataset UID': PASSED - 1 ms"
26.10.2022 12:58:06 - "Checking URL: 'https://inspire.ec.europa.eu/theme/theme.bg.atom'"
26.10.2022 12:58:07 - "Checking URL: 'https://inspire.ec.europa.eu/theme/theme.cs.atom'"
26.10.2022 12:58:07 - "Checking URL: 'https://inspire.ec.europa.eu/theme/theme.da.atom'"
26.10.2022 12:58:08 - "Checking URL: 'https://inspire.ec.europa.eu/theme/theme.de.atom'"
26.10.2022 12:58:08 - "Checking URL: 'https://inspire.ec.europa.eu/theme/theme.et.atom'"
26.10.2022 12:58:09 - "Checking URL: 'https://inspire.ec.europa.eu/theme/theme.el.atom'"
26.10.2022 12:58:09 - "Checking URL: 'https://inspire.ec.europa.eu/theme/theme.en.atom'"
26.10.2022 12:58:10 - "Checking URL: 'https://inspire.ec.europa.eu/theme/theme.es.atom'"
26.10.2022 12:58:10 - "Checking URL: 'https://inspire.ec.europa.eu/theme/theme.fr.atom'"
26.10.2022 12:58:11 - "Checking URL: 'https://inspire.ec.europa.eu/theme/theme.hr.atom'"
26.10.2022 12:58:11 - "Checking URL: 'https://inspire.ec.europa.eu/theme/theme.it.atom'"
26.10.2022 12:58:12 - "Checking URL: 'https://inspire.ec.europa.eu/theme/theme.lv.atom'"
26.10.2022 12:58:12 - "Checking URL: 'https://inspire.ec.europa.eu/theme/theme.lt.atom'"
26.10.2022 12:58:13 - "Checking URL: 'https://inspire.ec.europa.eu/theme/theme.hu.atom'"
26.10.2022 12:58:13 - "Checking URL: 'https://inspire.ec.europa.eu/theme/theme.mt.atom'"
26.10.2022 12:58:14 - "Checking URL: 'https://inspire.ec.europa.eu/theme/theme.nl.atom'"
26.10.2022 12:58:14 - "Checking URL: 'https://inspire.ec.europa.eu/theme/theme.pl.atom'"
26.10.2022 12:58:15 - "Checking URL: 'https://inspire.ec.europa.eu/theme/theme.pt.atom'"
26.10.2022 12:58:15 - "Checking URL: 'https://inspire.ec.europa.eu/theme/theme.ro.atom'"
26.10.2022 12:58:16 - "Checking URL: 'https://inspire.ec.europa.eu/theme/theme.sk.atom'"
26.10.2022 12:58:16 - "Checking URL: 'https://inspire.ec.europa.eu/theme/theme.sl.atom'"
26.10.2022 12:58:17 - "Checking URL: 'https://inspire.ec.europa.eu/theme/theme.fi.atom'"
26.10.2022 12:58:17 - "Checking URL: 'https://inspire.ec.europa.eu/theme/theme.sv.atom'"
26.10.2022 12:58:18 - "Checking URL: 'https://inspire.ec.europa.eu/theme/theme.en.atom'"
26.10.2022 12:58:18 - "Test Assertion 'md datasets-and-series 1.4: INSPIRE Theme Keyword': PASSED - 11473 ms"
26.10.2022 12:58:18 - "Test Assertion 'md datasets-and-series 1.5: Spatial Resolution': PASSED - 1 ms"
26.10.2022 12:58:18 - "Test Assertion 'md datasets-and-series 1.6: Resource Language': PASSED - 0 ms"
26.10.2022 12:58:18 - "Test Assertion 'md datasets-and-series 1.7: Topic Category': PASSED - 0 ms"
26.10.2022 12:58:18 - "Test Case 'Identification' finished: PASSED"
26.10.2022 12:58:18 - "Test Case 'Distribution' started"
26.10.2022 12:58:18 - "Test Assertion 'md datasets-and-series 1.8: Resource Locator': PASSED - 1 ms"
26.10.2022 12:58:18 - "Test Assertion 'md datasets-and-series 1.9: Data Quality Info Section': PASSED - 0 ms"
26.10.2022 12:58:18 - "Code list value: Kommissionens fÃ¶rordning (eu) nr 1089/2010 av den 23 november 2010 om genomfÃ¶rande av Europaparlamentets och rÃ¥dets direktiv 2007/2/eg vad gÃ¤ller interoperabilitet fÃ¶r rumsliga datamÃ¤ngder och datatjÃ¤nster"
26.10.2022 12:58:18 - "Code list value: Kommissionens fÃ¶rordning (eu) nr 1089/2010 av den 23 november 2010 om genomfÃ¶rande av Europaparlamentets och rÃ¥dets direktiv 2007/2/eg vad gÃ¤ller interoperabilitet fÃ¶r rumsliga datamÃ¤ngder och datatjÃ¤nster"
26.10.2022 12:58:18 - "Code list value: publication"
26.10.2022 12:58:18 - "Code list value: publication"
26.10.2022 12:58:18 - "Test Assertion 'md datasets-and-series 1.10: Dataset Conformity': PASSED - 29 ms"
26.10.2022 12:58:18 - "Test Assertion 'md datasets-and-series 1.11: Lineage': PASSED - 0 ms"
26.10.2022 12:58:18 - "Test Case 'Distribution' finished: PASSED"
26.10.2022 12:58:18 - "Test Suite 'Conformance Class 1: INSPIRE data sets and data set series baseline metadata.' finished: PASSED"
26.10.2022 12:58:18 - Releasing resources
26.10.2022 12:58:18 - TestRunTask initialized
26.10.2022 12:58:18 - Recreating new tests databases as the Test Object has changed!
26.10.2022 12:58:18 - Skipping schema validation because no schema file has been set in the test suite. Data are only checked for well-formedness.
26.10.2022 12:58:18 - Optimizing last database etf-tdb-3280effb-e86e-4d57-a65d-a96bb4fb8dbc-0 
26.10.2022 12:58:18 - Import completed
26.10.2022 12:58:18 - Validation ended with 0 error(s)
26.10.2022 12:58:18 - Compiling test script
26.10.2022 12:58:18 - Starting XQuery tests
26.10.2022 12:58:18 - "Testing 1 records"
26.10.2022 12:58:18 - "Executing Test Suite: /etf/projects/inspire-ets-repository/ets-repository-2022.3/metadata/2.0/datasets-and-series/ets-md-isdss-bsxets.xml"
26.10.2022 12:58:18 - "Statistics table: 0 ms"
26.10.2022 12:58:18 - "Test Suite 'Conformance Class 2: INSPIRE data sets and data set series interoperability metadata.' started"
26.10.2022 12:58:18 - "Test Case 'General Metadata' started"
26.10.2022 12:58:18 - "Test Assertion 'md isdss 2.1: Coordinate Reference System': PASSED - 0 ms"
26.10.2022 12:58:18 - "Test Assertion 'md isdss 2.2: Coordinate Reference System Identifiers': PASSED - 0 ms"
26.10.2022 12:58:18 - "Test Assertion 'md isdss 2.3: Temporal Reference Systems': PASSED - 0 ms"
26.10.2022 12:58:18 - "Test Case 'General Metadata' finished: PASSED"
26.10.2022 12:58:18 - "Test Case 'Identification' started"
26.10.2022 12:58:18 - "Test Assertion 'md isdss 2.4: Spatial Representation Type': PASSED - 0 ms"
26.10.2022 12:58:18 - "Test Assertion 'md isdss 2.5: Character Encoding': PASSED - 0 ms"
26.10.2022 12:58:18 - "Test Case 'Identification' finished: PASSED"
26.10.2022 12:58:18 - "Test Case 'Distribution' started"
26.10.2022 12:58:18 - "Test Assertion 'md isdss 2.6: Data Encoding': PASSED - 0 ms"
26.10.2022 12:58:18 - "Test Case 'Distribution' finished: PASSED"
26.10.2022 12:58:18 - "Test Case 'Data Quality' started"
26.10.2022 12:58:18 - "Test Assertion 'md isdss 2.7: Topological Consistency Quantitative Results': PASSED - 0 ms"
26.10.2022 12:58:18 - "Test Assertion 'md isdss 2.8: Topological Consistency Descriptive Results': PASSED - 0 ms"
26.10.2022 12:58:18 - "Test Case 'Data Quality' finished: PASSED"
26.10.2022 12:58:18 - "Test Suite 'Conformance Class 2: INSPIRE data sets and data set series interoperability metadata.' finished: PASSED"
26.10.2022 12:58:18 - Releasing resources
26.10.2022 12:58:18 - Changed state from INITIALIZED to RUNNING
26.10.2022 12:58:18 - Duration: 16sec
26.10.2022 12:58:18 - TestRun finished
26.10.2022 12:58:18 - Changed state from RUNNING to COMPLETED
Preparing Test Run Test run on 12:39
Resolving Executable Test Suite dependencies
Preparing 5 Test Task:
 TestTask 1 (1d0e5ca8-2f9d-4387-8d75-5d0a9cf80d58)
 will perform tests on Test Object 'csw-inspire.xml' by using Executable Test Suite 'Common Requirements for ISO/TC 19139:2007 based INSPIRE metadata records. (EID: 59692c11-df86-49ad-be7f-94a1e1ddd8da, V: 1.0.13 )'
 with parameters: 
etf.testcases = *
 TestTask 2 (72bb19d9-eed9-440c-942d-f027eef4ec81)
 will perform tests on Test Object 'csw-inspire.xml' by using Executable Test Suite 'LAZY.e4a95862-9cc9-436b-9fdd-a0115d342350'
 with parameters: 
etf.testcases = *
 TestTask 3 (449afc74-8833-40c2-9764-00bdb54ecba5)
 will perform tests on Test Object 'csw-inspire.xml' by using Executable Test Suite 'Conformance Class 2: INSPIRE data sets and data set series interoperability metadata. (EID: 2be1480a-fe42-40b2-9420-eb0e69385c80, V: 1.0.1 )'
 with parameters: 
etf.testcases = *
 TestTask 4 (caf3feb8-ed47-4bbb-9613-d2c4843df3bf)
 will perform tests on Test Object 'csw-inspire.xml' by using Executable Test Suite 'Conformance Class 2b: INSPIRE data sets and data set series metadata for Monitoring (EID: 0b86f7a3-2947-4841-823d-6a00d8e06d70, V: 1.0.2 )'
 with parameters: 
etf.testcases = *
 TestTask 5 (8fddedbd-09ea-4781-8648-09fdd2a9a0c6)
 will perform tests on Test Object 'csw-inspire.xml' by using Executable Test Suite 'Conformance Class 2c: INSPIRE data sets and data set series metadata for IACS (EID: 1067d6b2-3bb1-4e71-8ce1-a744c9bd5a3b, V: 1.0.4 )'
 with parameters: 
etf.testcases = *
Test Tasks prepared and ready to be executed. Waiting for the scheduler to start.
Setting state to CREATED
Changed state from CREATED to INITIALIZING
Starting TestRun.d8c3db24-2634-4d3d-aba8-4a615599f236 at 2023-10-04T10:39:44Z
Changed state from INITIALIZING to INITIALIZED
TestRunTask initialized
Creating new tests databases to speed up tests.
Skipping schema validation because no schema file has been set in the test suite. Data are only checked for well-formedness.
Optimizing last database etf-tdb-da11a041-ce7f-4ab1-b1d8-389cc51967e2-0 
Import completed
Validation ended with 0 error(s)
Compiling test script
Starting XQuery tests
Testing 1 records
Executing Test Suite: /etf/projects/inspire-ets-repository/ets-repository-2023.3/metadata/2.0/common/ets-md-common-bsxets.xml
Statistics table: 445 ms
Test Suite 'Common Requirements for ISO/TC 19139:2007 based INSPIRE metadata records.' started
Test Case 'General requirements' started
Test Assertion 'md common req C.1: XML Schema': PASSED#330 ms
Test Assertion 'md common req C.2: Root Element': PASSED#0 ms
Test Assertion 'md common req C.5: Language Code': PASSED#0 ms
Test Assertion 'md common req C.6: Metadata Point of Contact': PASSED#0 ms
Test Assertion 'md common req C.7: Metadata Date': PASSED#136 ms
Test Case 'General requirements' finished: PASSED
Test Case 'Identification' started
Test Assertion 'md common req C.8: Resource Title': PASSED#0 ms
Test Assertion 'md common req C.9: Resource Abstract': PASSED#1 ms
Email Char: 1
Email Anch: 0
Test Assertion 'md common req C.10: Responsible Organization': PASSED#116 ms
Test Assertion 'md common req C.11: Temporal Reference': PASSED#22 ms
Test Assertion 'md common req C.12: Max One Date of Creation': PASSED#0 ms
Test Assertion 'md common req C.13: Not More than one Date of Last Revision': PASSED#0 ms
Test Assertion 'md common req C.14: Temporal Extent': PASSED#198 ms
Test Assertion 'md common req C.15: Keyword Originating CV': PASSED#1 ms
Test Assertion 'md common req C.16: Group Keywords by CV': PASSED#1 ms
Test Assertion 'md common req C.17: Limitations on Public Access': PASSED#0 ms
Test Assertion 'md common req C.18: Conditions for Access and Use': PASSED#0 ms
Test Assertion 'md common req C.19: Geographical Bounding Box': PASSED#1 ms
Test Case 'Identification' finished: PASSED
Test Case 'Data quality' started
Test Assertion 'md common req C.20: Dataset Conformity': PASSED#0 ms
Test Assertion 'md common req C.21: Dataset Conformity Specifications': PASSED#36 ms
Test Assertion 'md common req C.22: Conformity Degree': PASSED#1 ms
Test Case 'Data quality' finished: PASSED
Test Suite 'Common Requirements for ISO/TC 19139:2007 based INSPIRE metadata records.' finished: PASSED
Releasing resources
TestRunTask initialized
Recreating new tests databases as the Test Object has changed!
Skipping schema validation because no schema file has been set in the test suite. Data are only checked for well-formedness.
Optimizing last database etf-tdb-da11a041-ce7f-4ab1-b1d8-389cc51967e2-0 
Import completed
Validation ended with 0 error(s)
Compiling test script
Starting XQuery tests
Testing 1 records
Executing Test Suite: /etf/projects/inspire-ets-repository/ets-repository-2023.3/metadata/2.0/datasets-and-series/ets-md-datasets-and-series-bsxets.xml
Statistics table: 36 ms
Test Suite 'Conformance Class 1: INSPIRE data sets and data set series baseline metadata.' started
Test Case 'General Metadata' started
Test Assertion 'md datasets-and-series 1.1: Resource Type': PASSED#0 ms
Test Case 'General Metadata' finished: PASSED
Test Case 'Identification' started
Test Assertion 'md datasets-and-series 1.2: Only One Data Identification': PASSED#0 ms
Test Assertion 'md datasets-and-series 1.3: Dataset UID': PASSED#0 ms
Checking URL: 'http://inspire.ec.europa.eu/theme/theme.bg.atom'
Checking URL: 'http://inspire.ec.europa.eu/theme/theme.cs.atom'
Checking URL: 'http://inspire.ec.europa.eu/theme/theme.da.atom'
Checking URL: 'http://inspire.ec.europa.eu/theme/theme.de.atom'
Checking URL: 'http://inspire.ec.europa.eu/theme/theme.et.atom'
Checking URL: 'http://inspire.ec.europa.eu/theme/theme.el.atom'
Checking URL: 'http://inspire.ec.europa.eu/theme/theme.en.atom'
Checking URL: 'http://inspire.ec.europa.eu/theme/theme.es.atom'
Checking URL: 'http://inspire.ec.europa.eu/theme/theme.fr.atom'
Checking URL: 'http://inspire.ec.europa.eu/theme/theme.hr.atom'
Checking URL: 'http://inspire.ec.europa.eu/theme/theme.it.atom'
Checking URL: 'http://inspire.ec.europa.eu/theme/theme.lv.atom'
Checking URL: 'http://inspire.ec.europa.eu/theme/theme.lt.atom'
Checking URL: 'http://inspire.ec.europa.eu/theme/theme.hu.atom'
Checking URL: 'http://inspire.ec.europa.eu/theme/theme.mt.atom'
Checking URL: 'http://inspire.ec.europa.eu/theme/theme.nl.atom'
Checking URL: 'http://inspire.ec.europa.eu/theme/theme.pl.atom'
Checking URL: 'http://inspire.ec.europa.eu/theme/theme.pt.atom'
Checking URL: 'http://inspire.ec.europa.eu/theme/theme.ro.atom'
Checking URL: 'http://inspire.ec.europa.eu/theme/theme.sk.atom'
Checking URL: 'http://inspire.ec.europa.eu/theme/theme.sl.atom'
Checking URL: 'http://inspire.ec.europa.eu/theme/theme.fi.atom'
Checking URL: 'http://inspire.ec.europa.eu/theme/theme.sv.atom'
Checking URL: 'http://inspire.ec.europa.eu/theme/theme.en.atom'
Test Assertion 'md datasets-and-series 1.4: INSPIRE Theme Keyword': PASSED#1608 ms
Test Assertion 'md datasets-and-series 1.5: Spatial Resolution': PASSED#0 ms
Test Assertion 'md datasets-and-series 1.6: Resource Language': PASSED#1 ms
Test Assertion 'md datasets-and-series 1.7: Topic Category': PASSED#0 ms
Test Case 'Identification' finished: PASSED
Test Case 'Distribution' started
Test Assertion 'md datasets-and-series 1.8: Resource Locator': PASSED#1 ms
Test Assertion 'md datasets-and-series 1.9: Data Quality Info Section': PASSED#0 ms
Code list value: Kommissionens fÃ¶rordning (eu) nr 1089/2010 av den 23 november 2010 om genomfÃ¶rande av Europaparlamentets och rÃ¥dets direktiv 2007/2/eg vad gÃ¤ller interoperabilitet fÃ¶r rumsliga datamÃ¤ngder och datatjÃ¤nster
Code list value: Kommissionens fÃ¶rordning (eu) nr 1089/2010 av den 23 november 2010 om genomfÃ¶rande av Europaparlamentets och rÃ¥dets direktiv 2007/2/eg vad gÃ¤ller interoperabilitet fÃ¶r rumsliga datamÃ¤ngder och datatjÃ¤nster
Code list value: publication
Code list value: publication
Test Assertion 'md datasets-and-series 1.10: Dataset Conformity': PASSED#714 ms
Test Assertion 'md datasets-and-series 1.11: Lineage': PASSED#0 ms
Test Case 'Distribution' finished: PASSED
Test Suite 'Conformance Class 1: INSPIRE data sets and data set series baseline metadata.' finished: PASSED
Releasing resources
TestRunTask initialized
Recreating new tests databases as the Test Object has changed!
Skipping schema validation because no schema file has been set in the test suite. Data are only checked for well-formedness.
Optimizing last database etf-tdb-da11a041-ce7f-4ab1-b1d8-389cc51967e2-0 
Import completed
Validation ended with 0 error(s)
Compiling test script
Starting XQuery tests
Testing 1 records
Executing Test Suite: /etf/projects/inspire-ets-repository/ets-repository-2023.3/metadata/2.0/datasets-and-series/ets-md-isdss-bsxets.xml
Statistics table: 31 ms
Test Suite 'Conformance Class 2: INSPIRE data sets and data set series interoperability metadata.' started
Test Case 'General Metadata' started
Test Assertion 'md isdss 2.1: Coordinate Reference System': PASSED#0 ms
Test Assertion 'md isdss 2.2: Coordinate Reference System Identifiers': PASSED#1 ms
Test Assertion 'md isdss 2.3: Temporal Reference Systems': PASSED#1 ms
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
TestRunTask initialized
Recreating new tests databases as the Test Object has changed!
Skipping schema validation because no schema file has been set in the test suite. Data are only checked for well-formedness.
Optimizing last database etf-tdb-da11a041-ce7f-4ab1-b1d8-389cc51967e2-0 
Import completed
Validation ended with 0 error(s)
Compiling test script
Starting XQuery tests
Testing 1 records
Executing Test Suite: /etf/projects/inspire-ets-repository/ets-repository-2023.3/metadata/2.0/datasets-and-series/ets-md-monitoring-bsxets.xml
Statistics table: 19 ms
Test Suite 'Conformance Class 2b: INSPIRE data sets and data set series metadata for Monitoring' started
Test Case 'Monitoring requirements' started
Checking URL: 'http://inspire.ec.europa.eu/metadata-codelist/SpatialScope/SpatialScope.bg.atom'
Checking URL: 'http://inspire.ec.europa.eu/metadata-codelist/SpatialScope/SpatialScope.cs.atom'
Checking URL: 'http://inspire.ec.europa.eu/metadata-codelist/SpatialScope/SpatialScope.da.atom'
Checking URL: 'http://inspire.ec.europa.eu/metadata-codelist/SpatialScope/SpatialScope.de.atom'
Checking URL: 'http://inspire.ec.europa.eu/metadata-codelist/SpatialScope/SpatialScope.et.atom'
Checking URL: 'http://inspire.ec.europa.eu/metadata-codelist/SpatialScope/SpatialScope.el.atom'
Checking URL: 'http://inspire.ec.europa.eu/metadata-codelist/SpatialScope/SpatialScope.en.atom'
Checking URL: 'http://inspire.ec.europa.eu/metadata-codelist/SpatialScope/SpatialScope.es.atom'
Checking URL: 'http://inspire.ec.europa.eu/metadata-codelist/SpatialScope/SpatialScope.fr.atom'
Checking URL: 'http://inspire.ec.europa.eu/metadata-codelist/SpatialScope/SpatialScope.hr.atom'
Checking URL: 'http://inspire.ec.europa.eu/metadata-codelist/SpatialScope/SpatialScope.it.atom'
Checking URL: 'http://inspire.ec.europa.eu/metadata-codelist/SpatialScope/SpatialScope.lv.atom'
Checking URL: 'http://inspire.ec.europa.eu/metadata-codelist/SpatialScope/SpatialScope.lt.atom'
Checking URL: 'http://inspire.ec.europa.eu/metadata-codelist/SpatialScope/SpatialScope.hu.atom'
Checking URL: 'http://inspire.ec.europa.eu/metadata-codelist/SpatialScope/SpatialScope.mt.atom'
Checking URL: 'http://inspire.ec.europa.eu/metadata-codelist/SpatialScope/SpatialScope.nl.atom'
Checking URL: 'http://inspire.ec.europa.eu/metadata-codelist/SpatialScope/SpatialScope.pl.atom'
Checking URL: 'http://inspire.ec.europa.eu/metadata-codelist/SpatialScope/SpatialScope.pt.atom'
Checking URL: 'http://inspire.ec.europa.eu/metadata-codelist/SpatialScope/SpatialScope.ro.atom'
Checking URL: 'http://inspire.ec.europa.eu/metadata-codelist/SpatialScope/SpatialScope.sk.atom'
Checking URL: 'http://inspire.ec.europa.eu/metadata-codelist/SpatialScope/SpatialScope.sl.atom'
Checking URL: 'http://inspire.ec.europa.eu/metadata-codelist/SpatialScope/SpatialScope.fi.atom'
Checking URL: 'http://inspire.ec.europa.eu/metadata-codelist/SpatialScope/SpatialScope.sv.atom'
Checking URL: 'http://inspire.ec.europa.eu/metadata-codelist/SpatialScope/SpatialScope.en.atom'
Test Assertion 'M.1: Spatial scope keyword': PASSED#1011 ms
Checking URL: 'http://inspire.ec.europa.eu/metadata-codelist/PriorityDataset/PriorityDataset.bg.atom'
Checking URL: 'http://inspire.ec.europa.eu/metadata-codelist/PriorityDataset/PriorityDataset.cs.atom'
Checking URL: 'http://inspire.ec.europa.eu/metadata-codelist/PriorityDataset/PriorityDataset.da.atom'
Checking URL: 'http://inspire.ec.europa.eu/metadata-codelist/PriorityDataset/PriorityDataset.de.atom'
Checking URL: 'http://inspire.ec.europa.eu/metadata-codelist/PriorityDataset/PriorityDataset.et.atom'
Checking URL: 'http://inspire.ec.europa.eu/metadata-codelist/PriorityDataset/PriorityDataset.el.atom'
Checking URL: 'http://inspire.ec.europa.eu/metadata-codelist/PriorityDataset/PriorityDataset.en.atom'
Checking URL: 'http://inspire.ec.europa.eu/metadata-codelist/PriorityDataset/PriorityDataset.es.atom'
Checking URL: 'http://inspire.ec.europa.eu/metadata-codelist/PriorityDataset/PriorityDataset.fr.atom'
Checking URL: 'http://inspire.ec.europa.eu/metadata-codelist/PriorityDataset/PriorityDataset.hr.atom'
Checking URL: 'http://inspire.ec.europa.eu/metadata-codelist/PriorityDataset/PriorityDataset.it.atom'
Checking URL: 'http://inspire.ec.europa.eu/metadata-codelist/PriorityDataset/PriorityDataset.lv.atom'
Checking URL: 'http://inspire.ec.europa.eu/metadata-codelist/PriorityDataset/PriorityDataset.lt.atom'
Checking URL: 'http://inspire.ec.europa.eu/metadata-codelist/PriorityDataset/PriorityDataset.hu.atom'
Checking URL: 'http://inspire.ec.europa.eu/metadata-codelist/PriorityDataset/PriorityDataset.mt.atom'
Checking URL: 'http://inspire.ec.europa.eu/metadata-codelist/PriorityDataset/PriorityDataset.nl.atom'
Checking URL: 'http://inspire.ec.europa.eu/metadata-codelist/PriorityDataset/PriorityDataset.pl.atom'
Checking URL: 'http://inspire.ec.europa.eu/metadata-codelist/PriorityDataset/PriorityDataset.pt.atom'
Checking URL: 'http://inspire.ec.europa.eu/metadata-codelist/PriorityDataset/PriorityDataset.ro.atom'
Checking URL: 'http://inspire.ec.europa.eu/metadata-codelist/PriorityDataset/PriorityDataset.sk.atom'
Checking URL: 'http://inspire.ec.europa.eu/metadata-codelist/PriorityDataset/PriorityDataset.sl.atom'
Checking URL: 'http://inspire.ec.europa.eu/metadata-codelist/PriorityDataset/PriorityDataset.fi.atom'
Checking URL: 'http://inspire.ec.europa.eu/metadata-codelist/PriorityDataset/PriorityDataset.sv.atom'
Checking URL: 'http://inspire.ec.europa.eu/metadata-codelist/PriorityDataset/PriorityDataset.en.atom'
Test Assertion 'M.2: Priority datasets keyword': PASSED_MANUAL#3245 ms
Test Case 'Monitoring requirements' finished: PASSED_MANUAL
Test Suite 'Conformance Class 2b: INSPIRE data sets and data set series metadata for Monitoring' finished: PASSED_MANUAL

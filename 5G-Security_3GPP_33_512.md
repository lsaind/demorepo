![Image from file](Spirent_logo_full_1.png=300x90)

## Introduction
This is a sample automated test suite for testing 5G Security test cases complying 3GPP 33.512. 
In this library, a 5G Security gets tested for features, functions & adherence to specifications of 3GPP.

A sample list of few test cases have been chosed for demonstrative purposes. 
Look into the topology to gather more details on nodes being emulated & likewise tested.

## Test Steps
* Login to Landslide
* Refer to the topology and pick the respective test case. 
* Determine the network connections and map the test cases to their respective ports such that every emulated network function and the node that is being tested is reachable. 
* Configure the desired test case & RUN them
* Observe the test case reported statistics to conclude on the test case behaviour and accodingly the criteria's defined to determine pass/fail criteria for a specific test case. 

## Reference to 3GPP Standards
[3GPP Security standards 33 512][3gpp]
[3gpp]: <https://www.etsi.org/deliver/etsi_ts/133500_133599/133512/16.03.00_60/ts_133512v160300p.pdf>

## Test case automated with iTest & Velocity
* 4.2.2.3.1 Replay protection of NAS signalling messages -> TC_NAS_REPLAY_AMF
* 4.2.2.3.2 NAS NULL integrity protection -> TC_NAS_NULL_INT_AMF
* 4.2.2.4.1 Bidding down prevention in Xn-handover -> TC_BIDDING_DOWN_XN_AMF
* 4.2.2.6.1 Invalid or unacceptable UE security capabilities handling -> TC_UE_SEC_CAP_HANDLING_AMF
* 4.2.2.3.3 NAS integrity algorithm selection and use  -> TC_NAS_INT_SELECTION_USE_AMF
* 4.2.2.1.2 RES* verification failure handling -> TC_RES*_VERIFICATION_FAILURE
* 4.2.2.1.1 Synchronization failure handling -> TC_SYNC_FAIL_SEAF_AMF

## Access to the Solution presentation
[PowerPoint][PPT]
[PPT]: <https://spirent1-my.sharepoint.com/:p:/g/personal/gokul_ragupathy_spirent_com/Ebqk-nz5WD5EolxQlNDmKUMBrBZz50oNkediqfoY5OkGuQ?e=pJcEmY>

## Video Tutorial:
[![IMAGE ALT TEXT HERE](https://img.youtube.com/vi/6-Gg2uXb39k/0.jpg)](https://www.youtube.com/watch?v=6-Gg2uXb39k)

## Topology for testing the scenario
![Topology](5G-Security_33-512_AMF.png=900x400)
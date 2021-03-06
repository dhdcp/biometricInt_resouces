# Resources for Biometric (Fingerprint) Integration in survey and Other systems 

This repository will contain the resouces to understand Different approaches to integrate Biometric in survey and other systems of Depatment .


## Approaches we can follow:
**A. Purchase the services and harwares like Simprint** 

Simprint used in Nepal by Possible Health with commcare, and medic mobile in their fork of odk collect. It uses bluetooth device, and two major apps for control "simprint ID" and "simprint client app". 

*Procedure* 
1. Buy hardware and service from simprint
2. they will provide api token, usernames and other credentials 
3. install ODK collect/commcare or any javarosa based sruvey application in mobile 
4. install "simprint client app" and "Simprint ID" app. 
5. Create a XLS forms as in example provided in following [link](https://docs.google.com/spreadsheets/d/1z-hBSwQ646KnL7tz3GPt8PH0WLWL0H1RzcouqFhThgA/edit#gid=1591872452)

*How it is implemented*

![Technical Process Flow Digram of simprints](/images/simprint_1.jpg?raw=true, "Danel et. al 2015") 

source: ML Danel et. al "Biometric Fingerprint System to Enable Rapid and Accurate Identification of Beneficiaries" (2015),135-137; DOI: [10.9745/GHSP-D-15-00010]( https://doi.org/10.9745/GHSP-D-15-00010)

**B. Develop our own system based on openANDID** 

we can build our own fingerprint scanning app with support for avaliable devices in nepal, this will provide us freedom to use it in multiple projects and multiple devices. Which will support our longterm vision. 
There had been similar implementations, one of such example with its focus on ODK, commcare, and javarosa based survey tools is cims-print. you can find [Department's fork at following link](https://github.com/dhdcp/cims-prints) and [orginal at this link](https://github.com/cims-bioko/cims-prints) 

*Procedure*
1. Make list of fingerprint scanners avaliable in Nepal which provide andorid SDK
2. Review feasibility and estimate the cost and time 
3. get a interns or developer for short-time (2 weeks to 4 weeks) or task based with full project controlled by Data manager of Department 
4. test the app and develop a usecase documentations 
5. training for researchers and other department members 
6. integration all projects


## Intresting links

1. simprint's github repository [https://github.com/SimPrints](https://github.com/SimPrints)
2. simprint's detailed analysis : [https://www.engineeringforchange.org/solutions/product/simprints/](https://www.engineeringforchange.org/solutions/product/simprints/)
3. Campaign information Management System(CIMS)'s github repository : [https://github.com/cims-bioko](https://github.com/cims-bioko)
4. Touchless alterntives:

	- [NEC](), 
	- [Right Patient](https://www.rightpatient.com/medical-identity-theft/)
	- [Lifemed ID](https://lifemedid.com/our-solutions/patient-identification)

A Simple Turning Move - README.md
James DeSoucey January 2020

What is my dApp, why did I build it, and what is it intended to do?

The concept of this dApp is to be a platform or base to start where other more complicated apps can begin their processes.
It is not a very complicated concept but one that seems very much in need.
It is based on concepts similar to "Personal Sovereignty" where the user is the owner of all information related to themselves but using a very simple and basic starting point.

It will provide a means to create a secure and immutable means to enter and keep basic information (Name, Rank, Serial Number) profiles on a blockchain, public or otherwise, correct and spelled correctly every time in a standardized format.

This record will include nothing more than is considered public now, like driver's license for example, so private and sensitive information will not be used.

It is to be designed to be publicly searchable so the information should be easy to find.

Sensitive, personal, or not-intended-for-public information would need multi entity involvement for any information to be released to anyone other than the owner and would potentially require something similar to a multi-signature process. This would include the medical facility, the doctor(s), associated as well as the owner of the information as the permission grantor. 

This would also create a record based on blockchain events of everyone involved with this data and it's chain of custody, making right to privacy concepts such as GDPR and CCPA easier to manage. 

In the overall process, this methodology would also allow for any data or information created or stored in any manner, that is related to the owner, to have a reference to this owner for management of all of their data.

Ideally, the more mature versions of this app would use upgradeable contracts to avoid version issues amongst various facilities, to be able to change location in case of breach, and be able to use named aliases with the ENS (Ethereum Naming Service) to make searching easier and more human.

Later versions would also include a "revert" or "refund" process that can be enacted at any time to be able to remove access or request removal of data similar to GDPR and CCPA processes) - If the emit process or logging process works correctly, there will be no need to hunt for where the owner's data may reside.

-
How would this work?

Although this could potentially be used as a starting point for a great many processes, the original target has been the initial point of contact with a medical facility because of the unneeded frustration of having to fill out the forms, (sometimes over ten of them), by hand. Then, someone else manually enters this information into a system potentially misspelling or entering the information incorrectly.

When visiting a medical facility for the first time, or for verifying identity on subsequent visits, the basic ID information can be transferred by a variety of methods old or new such as magnetic stripe cards, chipped cards, NFC like "Tap To Pay", QR code, or methods not deployed yet to create membership in medical facility by giving their BC (blockchain) contract address related to their basic ID information. This could potentially be even more secure and confirmed by a 'smart phone's secure element and biometric identification as to ownership of this information like current payment methods, to fill out their "onboarding process forms". (Simple Bank example method)

Once related or onboarded to the facility system, an "on behalf of" method (Inter Contract Example Method) could be used granting access to more "Advanced", "Priviledged", or "Private" information/data stored in/at any or many of the EMR/EHR repository vaults such as MS Healthvault, Google Health, AthenaHealth, Epic, CareCloud, etc., on a private blockchain, or even on the IPFS (InterPlanetary File System) if encrypted. Keeping this much data on a public Blockchain may become cost prohibitive as well as difficult to manage. Leaving it in the different systems allows each facility to manage the data they collect and/or manage the best way they see fit while still allowing access to the owner or Sovereign person.

Each time the contract is touched, an event and/or emit process will run allowing for logging of all attempts to access information related to this owner and for reports to be able to be created .	
-
All procedures, Tests, Examination results, consultations, reports, etc. done by medical facilities or personnel no matter what method or service being used to store these EHR records, will include the blockchain contract reference to the owner's basic personal information address for future reference, and access to establish and/or gaurantee ownership of this personal information to the Sovereign Person.
*** A law or agreement process is needed here but out of scope for this dApp and initiative for now.***
		
--------------------------------------------
-Create User Stories 
How would potential users interact with this dApp?

Part One - The Sovereign Person (User)

A user can use the app to create their basic identity on any platform to create an entry on the Ethereum blockchain.

This user fills out their basic identification information possibly uploading some unique data (pictures/video/other as an aid to proof of existence) to the blockchain entry through this app.

The user is now the sovereign person or owner of their own information.

The dApp reads the user’s address and can now show all of the data that they have previously uploaded or had uploaded on their behalf by medical facilities.
 
Users can retrieve necessary reference data about uploaded items related to them to allow medical facilities or other medical personnel to access the data and verify the data's authenticity.
-
Part Two - The Medical Facility

A medical facility associate opens the web app. The web app recognizes their address and identifies them as a medical facility and a potentially allowed accessor of sovereign person's (client) information.

The user presents his contract location to the medical faciltity associate through his dApp. The facility's app reads the user’s address and populates the necessary fields for the onboarding process. 

The medical facility or doctor can now potentially, once approved or permissioned by the data's owner, be shown all of the data that has previously been recorded or uploaded or had uploaded on their behalf by medical facilities.
 
Once permissioned the app will present an available information page where the medical facility's representatives would be able to see a list of collected information gathered by each EMR/EHR service or store.

If a non approved requester of the Sovereign Person's information attempts to request this information, all they will be able to see is the public information that anyone can access and an event will be triggered and a log entry emitted.

# W3plus
Ramblings on the new internet
Literally.
I'm very jacked about web3 and what it can bring to people all over the world.
I think the overall issue is going to be time to market for an acutla user interface that is easy and on-boarding is as easy as getting a new iphone.

Along those lines I think there are some needs which are challenging to be met, so should be undertaken sooner rahter than later.

- Meta-currency: A currency-tool that consolidates all other currencies,(i.e. BTC), and what I thnk of as service currencies. For example billing currencies  (Contract enabled ETH,ADA), service-IOT-Data currencies (HNT,DHX,MXC), service-security (DPR),STORJ for decentralized files., etc.  This would have feature to simply toss any currency into the "wallet". From the user point of view those all go into the background and they are shown whatever the choose as the native/primary indicator, USD, Some sort og GLOBAL generic coin, etc).  
  Behind the scenes ideally we could get individual blockchains to implement a built in funds locking feature - this would make txns cheaper for the end user instead of incurring full txns costs.  For example on ethereum it would be an intergrated feature.  Where you can lock funds ETH or any ERC-20 (perhaps - with user approval of course), into the meta-wallet.
  Built in mechanism for pooling funds from multiple people into different paymetn timeframes.  For example - a store may allow a 24 reconcilliation payment window.  When you transact with that store, the meta-wallet has your pool of locked coins.  
  The payment that is done moves a % of the current funds,( + float?), into a waiting recon status. The store has guarentee that they will get paid as wallet has assigned the funds, over the 24 horu time frame the wallet service pools across walletts to lower txn costs.  Basically the store agrees to sell now, transact later.
is this whart polkadot does =- gotta read more on that.

- A updated and unified messaging protocol - if we step back and look at the web stack as a whole, it looks like a huge code base that has a lot of duct-tape.  Don't get me wrong , lot's of great things exist in the stack, (as I understand it). However HTTP/HTML/XML started with a narrow view of what messages would look like or be sending.  I think we should take a look with fresh eyes from TCP/IP all the way up to javascript and unify, standardize and simpllyify the entire development and creation process.

- updated backend decentralized web "host" - bi-protocol browser.  Existing basic http/html browser + new Web3 Plus proptocol same code language/ide interface as the front end. Decentralized tool.

- Anonymous Authorizations - I know we all see blockchain as a global effort regardless of boundaries.  But the fact is that they existing and the annonymity of web3/blockchain scares them. Loss of control , even for the most noble of people is hard.  So there needs to be a system where we can adhere to the web3 values of anonymity , but also allow the information from outside vetting agencies to be 'passed' through "the block chain".  To that end I propose an anonymous authorization system.
-- System is blockchain contract based.  There is the concept of a vetting agency, and an approved question list. Might be easiest to explain by example of thew process I imagine.
Anonymous Authorization Example - Drivers License.
Step 1 - If the authorizing agency is not yet in the system, it would petition to be added and undergoe a vetting process TBD.  All 10000% transparent to people.

Step 2 - Athorizing agency publishes a list of questions it is capable of answering.   In our example this could be Texas DMV with questions such as "Authorized passenger vehicle", "Authorized CDL xxx".  But - there is no need for information such as name, sex, etc to be shared necessarily.  it makes sense in a minute... i hope.

Step 3 - Person goes through the texas DMV drivers license process. Via the Anon Auth service the DMV now records to a data-blockchain,(storj like), the public key that was presented by that person along with the answers to it's list of questions. The data stored in the database is actually encrypted by using a muilti-sig/auth type transaction.  This ensures that for each vetting agency , for each person , there is a unique pair encryption of the data for that person.  Have to explain that in more detail....

step 4 - The person get a notification in their wallet that the texas DMV is adding them to it's system. review the data, accept it. - encryption keys shared.  now in the wallet, there is the key to read the data about that key-agency only.  from the agency side they can read the data of all thier clients/customers , but no other agencies info.

How it's used:
Proof of Age
  Person goes to a bar, when asked for proof of age the bar can scan QR code.  Person has to approve the authorization request (can approve 1-time, forever, etc).  The authorized transaction is sent to Anon Auth with enough data to answer "is old enough to drink alcohol?".  This does not stop the bar from having additional was of checking.  They can use multiple agencies, require a photo-id.  Also agencies might indicate that before the person authorize the question the have to pass biometric scan associated with the key. That, or phot ids, will be out of our control.  We just need to give better, easier alternatives.
  
  Pulled over for speeding
  Same basic scneario.  the interaction through the contract can send back to an officer is allowed to drive, any tickets already, arrest warrents.
  
  In the grand scheme it anopnymous authorizaation allows people to say "I only wqant you to know this much'. they can reject requests for information.  We can't be responsible for the actions of the authorizaing agencies if they do, all we can do is start the process to a system which gives as much privacy and social/govenerment servicess in the same package.

- 

- Front end "browser" is complete IDE and version control system for the new protocal and scirpting langauges.  A unified and simplified way to create and code.  Has full front end UI to low level txn management built in and simplified.   There is tons of code that doens't need to be rewritten and should be absorbed into the overall product of web3 decentrlized browsing. 


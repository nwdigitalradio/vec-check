# vec-check
Volunteer examiner check list for amateur radio test sessions

## Requirements
* Minimum of 3 VE's, 4 is better
* A Windows laptop with the Laurel VEC software installed
* Minimum 2 mobile devices with _ZipGrade_ installed
  * Need to provide group code to activate and load answer sheets
* Printer - See [tub inventory](https://github.com/nwdigitalradio/vec-check/blob/master/tub-inventory.md)
* phone to contact Cory
* Stand to organize manila folders
* File back up location for Laurel critical files.
* SAT Certified calculater
* _The Tub_

#### Items in _The Tub_
* [Tub Inventory](https://github.com/nwdigitalradio/vec-check/blob/master/tub-inventory.md)

## Time Line

##### Commitment of 3 or more VE's schedule
#####  Reserve a room for testing
* Lopez: Library Common Room
* SJ: Friday Harbor Commons building
  * Old FH Fire Station

##### Enter Testing Session in Laurel Site
* Required for testing session
  * automatically puts announcement on Laurel Site

##### Advertise X weeks before exam session
* Lopez Rocks
* The Islands' Weekly
* Laurel VEC session announcement - occurs when entering testing session
  * Optional: ARRL VEC announcement

##### VE Team to-do
* Set the time when VE's should arrive
* Assign exam session leader (person running computer)
* Assign tester leader (team interacting with testers and grading tests)

##### Exam classes or not

##### __IMPORTANT__ Testees should pre-register
* Need to fill-in & return a sign up form located [here](https://github.com/nwdigitalradio/vec-check/blob/master/signin_form.md)
  * Verify that they have filled in their email address.

###### Each testee should get an FRN number before session day
* [Getting
an FCC Registration Number (FRN) in the Universal Licensing System
(ULS)](https://www.fcc.gov/wireless/support/universal-licensing-system-uls-resources/getting-fcc-registration-number-frn)
* [Youtube FCC User Profile and FRN Registration for New Radio Operators](https://youtu.be/7a4doKEPN5M) (4:21)
* Alliviates SSN requirement
* Includes new testees without an Amateur license

###### Walk-ins should get an FRN number at session
* Need process for getting walk-ins FRN, how-to and laptop?

### Day of Session
* VEs should show up half hour in advance
* Testees should be given paperwork to fill out as soon as they arrive
* VEs
  * One VE inputs data on the computer
  * Two VEs have ZipGrade on their mobile devices and are availabe for
  questions.

###### Testees need to:
* Sign in & show ID
* General & Extra testees need to bring a copy of their current
license or CSCE if upgraded license hasn't been issued yet.

###### Exam session Check list
* All initial paper work completed, hand out exams to testees
  * Testees need to put the correct exam number on their exam and element
  * VE should walk around & confirm correct exam number is on their
  exam
  * Tell everone else to __PLEASE BE QUIET__
  * Make sure all phones are off the table and no programable calculators used.
  * Remind testees to not write on the test booklet. Use back of answer sheet for scratch paper.
* Testees that passed their exam need to have their CSCE
* Testees need to have signatures match what they printed
  * No smiley faces

* print the 605/CSCE and __NOT__ 'close out' the testee until the 605
has been received and signature checked.
  * Make sure the testee VERIFIES their name/address on 605 when they sign it.
* If testee fails an exam, another exam may be given. (Max of three tries if getting closer to passing)
* On the 605, don't need candidate to initial top section, unless they are requesting callsign change
* If testee passes an exam __be sure they get their CSCE__

* Order of Events
  * Fill out form
  * Take test
  * Grade test
  * Enter results into Session Software
  * Check if wants to take next test, else continue
  * Print CSCE and 605
  * Have tester sign CSCE (they keep) and sign 605 (we keep)
  * Give 605 back to session lead, they check it off in software and file (staple) items in this order
     * 605
     * Answer sheet (pass first, then any fails)
     * Sign in sheet and/or copy of license

### Day after exam (Or just after exam)

* Review test booklets to make sure nobody wrote in them.
* Check results match paperwork
* Send kenny/cory the .enc file (generated by FCC file upload tab in software)
  * Needs to be pushed to Laurel site, under session. Will automatically be scheduled to send to FCC
* Assemble packet
  * Summary Report (from software)
  * List of Applicant (from software, Tool/Print List of Applicants)
  * signed in form of VE's
  * packet of tester papers (605,Answer Sheet,SignInSheet,copy of license)
  * Assemble all artifacts in single PDF and upload to Laurel site as part of the session

#### List of files required to send to Kenny in a tar.xz file

* If Kenny is not present be sure to exclude his name from VE roster
* Packet content files
  * From each testee
    * Answer sheet
    * 605.pdf
    * csce.pdf
  * SessionSummary.pdf
  * VESignIn.pdf
  * BYSJCARS220622A0.enc (example file name) 

* Create tar.xz file for VEC session on June 22
```
tar --xz -cvf LopezVESession0622.tar.xz AnswerSheetBob.pdf AnswerSheetDoug.pdf 605Bob.pdf 605Doug.pdf csceBob.pdf csceDoug.pdf SessionSummary.pdf BYSJCARS220622A0.enc
```

* Verify contents of tar.xz file
```
tar -tvf LopezVESession0622.tar.xz
```

### Other notes
* VEs auditing the session need to __PLEASE BE QUIET__



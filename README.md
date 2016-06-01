# .NET-Developer-Challenge

`version 1.0`
`challenge status: open`

Welcome! We've been expecting you. Holmusk is a big data based high tech company specializing in healthcare in Singapore and the United States. 

If you're someone who bleeds code and aches to make a difference in the world, then you are at the right place. You will be part of a world-class team working on the most exciting ground-breaking technology in an inspiring and collaborative environment.

## Basics

This is the Holmusk .NET developer challenge. The rules of the challenge are very simple and are as follows

* You are required to code in C#
* You will be able to submit the challenge anytime you are ready provided the challenge is still open
* Your code should be neatly commented
* Please complete the code in your local repository and email a patch file or link to dean.atchley@mindlinc.com, hongtrieu.le@holmusk.com and hoangphuoc.truong@holmusk.com 
* Please note that you will also be judged on the elegance of your code, level of abstraction and technical skills presented in the implementation. For more details, refer to the Judging Criteria section below.

## The Challenge 

### What You'll need to build
* You'll need to build a FHIR based application  ([FHIR](https://www.hl7.org/fhir/) ).
* A Windows Forms based UI.
* A data access layer using Entity Framework to handle persistence.
* The UI will allow CRUD operations using a "Patient" resource against a sql server express instance.
* The UI must also allow querying patients from a public FHIR test server and allow the import of selected patients into the local database. ([FHIR Test Servers](http://wiki.hl7.org/index.php?title=Publicly_Available_FHIR_Servers_for_testing)) 
* Unit tests
* Logging of user activity
* Use [The Reactive Extensions (Rx)](https://msdn.microsoft.com/en-us/data/gg577609) where possible
 

### Bits and Pieces to take note of

#### UI
* Include what you think are the important attributes of patient as per the FHIR specification
* For any patient attribute that is constrained by a value set such as "gender", please use an appropriate UI construct to restrict those selections
* In the case of the CRUD "D", just make the patient inactive, we don't like deleting clinical data

## Judging Criteria 
* What you have produced will determine your final outcome. You will be scored based upon your coding style and the ability to follow "good code" [See: Microsoft C# Coding Conventions](https://msdn.microsoft.com/en-us/library/ff926074.aspx)
* More than your ability to code we want to see your ability to learn. So you are encouraged to ask questions. [Dean](mailto:dean.atchley@mindlinc.com)

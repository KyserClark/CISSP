# Security Models

*Remember*
* Simple = Reading
* Star or * = Writing

## Bell-LaPadula Model
### Enforces Confidentiality
* Simple security rule 
   * no write up
* *-property (star property) rule 
   * no read down
* Strong star property rule

## Biba Model
### Enforces Integrity
* *-integrity axiom 
   * no read down
* Simple integrity axiom 
   * no write up
* Invocation property

## Clark-Wilson Model
### Enforces Integrity
* Users Active agents
* Transformation procedures (TPs) Programmed abstract operations, such as read, write, and modify
* Constrained data items (CDIs) Can be manipulated only by TPs
* Unconstrained data items (UDIs) Can be manipulated by users via primitive read and write operations
* Integrity verification procedures (IVPs)

## Noninterference Model
* implemented to ensure any actions that take place at a higher security level do not affect, or interfere with, actions that take place at a lower level.

## Brewer and Nash Model
### AKA Chinese Wall Model
* States that a subject can write to an object if, and only if, the subject cannot read another object that is in a different dataset.

## Graham-Denning Model
### Defines a set of basic rights in terms of commands that a specific subject can execute on an object 
* How to securely create an object
*	How to securely create a subject
*	How to securely delete an object
*	How to securely delete a subject
*	How to securely provide the read access right
*	How to securely provide the grant access right
*	How to securely provide the delete access right
*	How to securely provide transfer access rights

## Harrison-Ruzzo-Ullman Model
* Deals with access rights of subjects and the integrity of those rights
* A subject can carry out only a finite set of operations on an object

## Reference
* All-in-One CISSP Exam Guide Ninth Edition by Fernando Maymi and Shon Harris
   * Pages 398 - 402

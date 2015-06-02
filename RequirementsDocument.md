# **Requirements Document -- Mark Jeffrey**
CS6300 Spring 2015 
<br>Mark Jeffrey – mjeffrey6.
<br>2 June 2015
Project 1 - Average Sentence Length (ASL)


##1 User Requirements

This program is designed for students who write essays and are concerned about  the sentence length or the number of words in each sentence.  Average Sentence Length (ASL) will calculate the average sentence length and present that to the user so that they may perfect their writing style.

###1.1 User Characteristics

The expected user of this program may have little to no experience with computers or programming or may be very experienced. <br>
Various types of machines will be used to run this program. This java application will be executed as a command line application and expects certain parameters.

###1.2 System's functionality

ASL will count all of the sentences within a given document and calculate and present the average sentence length as output.<br>

This java application will be executed as a command line application and expects certain parameters.<br>
If the syntax does not match, error text shall summarize the expected Syntax. <br>

The first parameter will be the name of the plain text file to process.  A fully qualified path is required to read any file outside of the local directory.
Any parameter with a –d will be recognized as a delimiter used to break up sentences.  Multiple delimiters are not supported during this version.


###1.3 User Interfaces

As noted, ASL is a command line application and utilizes a terminal user interface.

##2 System Requirements

There are several functional and non-functional requirements for ASL.  At a high level, ASL will count all of the words within each sentence of a document and provide the average number of words for all sentences.  
 
###2.1 Functional Requirements

1. Reporting Requirements
	1. The programs output shall be the average sentence length rounded down to the nearest integer.
	2. The program shall report syntax errors and provide guidance if improper syntax is provided.
2. Business Rules
	1. The word length is customizable. 
	2. sentence structure variability accounted for delimiter assignment.
3. Transaction corrections, adjustments and cancellations
	1. Helpful message provides guidance for improper usage. 



###2.2 Non-Functional Requirements

1. Usability<br>
	1. The system shall use Java with no special libraries
	2. The system shall be executable from the command line,
	3. The user shall specify a file path for the text file to be checked.
	2. The user shall specify the sentence delimiter using the flag -d preceding the desired delimiter.
	3. The user shall specify a lower limit for a word length.
2. Interoperability<br>
	1. ASL shall read in a file specified.
	2. The file shall be plain text format. 
3. Environmental
	1. ASL shall run on a wide variety of platforms





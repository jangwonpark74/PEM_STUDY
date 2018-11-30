#2018 12 01

- IETF RFC 1421 Privacy Enhancement for Internet Electronic Mail
  Part I: Message Encryption and Authentication Procedures

1. Executive Summary

   This document defines message encryption and authentication procedure for privacy-enhanced mail(PEM) service.
   
   Privacy enhancement services :
     - confidentiality
     - authentication
     - message integrity assurance
     - non-repudiation of origin

2. Terminology 
   
    a user is a person or a computer application.
    a user is referred to as either an originator or a receipient.

    An originator prepares message with the assistance of his or her User Agent (UA).
    A UA is an application process that interacts with the Message Transfer System (MTS) to submit messages.
    The MTS delivers to one or more receipient UAs the message submitted to it.
    The MTS is composed of a number of Message Transfer Agents (MTAs)
  
    The collection of UAs and MTAs is called the Message Handling System (MHS).
    The MHS and all of its users are collectively referred to as the Message Handling Environment.

3. Services, Constraints, and Implications
  
4. Processing of Messages

   Types of Keys :
   1. Data Encrypting Keys (DEKs) are used for encryption of message text for computation of message integrity check (MIC) quantities.
   2. Interchange Keys (IKs) are used to encrypt DEKs for transmission within messages.
 



<!--
author:   Dan Taube

email:    djtaube@ilstu.edu

version:  0.0.1

language: en

narrator: US English Female

comment:  Guidance for electronic signature use in compliance with Illinois UETA.
-->

# Electronic Signature Guidance

## Before You Begin
In 2021, the state of Illinois adopted the Uniform Electronic Transaction Act (UETA) with a state act by the same name. UETA is one of many United States Uniform Acts that states can individually adopt and enact into law. UETA specifically provides a legal framework for electronic signatures that allow them to be used in a manner that is equivalent to traditional paper signatures.

Review the following information to learn more about these acts and electronic signature use.

### UETA and ESIGN
In addition to UETA, there is the Electronic Signatures in Global and National Commerce Act (ESIGN Act). The ESIGN Act is federal regulation that addresses discrepancies between individual state laws for electronic signature and in cases where no state law exists. Its primary purpose is to establish that electronic signatures are legally valid.

University departments and employees requesting and using electronic signatures should primarily refer to the Illinois act. However, when the University itself interacts with other agencies/entities, especially at an international level, ESIGN Act may apply instead. Inquire with the Office of General Counsel if you need confirmation for your situation.

### Electronic Signatures Defined
According to UETA and the ESIGN Act, an electronic signature is defined as an "electronic sound, symbol, or process attached to or logically associated with a record and executed or adopted by a person with the intent to sign the record."

The most common form used is an electronic symbol. Examples include but are not limited to a form field to type, draw, or otherwise mark a signature or interactive buttons labeled with "I agree" or "I accept."

### Digital Signatures
Digital signatures are a type of electronic signature the utilizes digital certificates provided by certificate authorities. This type of electronic signature often requires additional software and an identity verification process by the certificate provider. An example would be the [State of Illinois Digital ID service](https://doit.illinois.gov/services/catalog/security/what-is-pki.html).

This type of electronic signature provides the greatest level of technical assurance but is also more complex to implement/leverage at an individual or departmental level. Currently, the University has not formally established technology or processes to leverage this type of electronic signature. If you have a need to utilize digital signatures, contact the Information Security Office to request a consultation.

### Assess Risk
When developing an electronic signature process, you must consider risk to ensure your approach is appropriate. The primary risk would be that the process does not result in a legally valid electronic signature. In such a scenario, an invalid signature could result in the record itself, and whatever it covers, being invalid as well. The impact of such requires careful consideration before proceeding.

The next section provides information about the key requirements for legally valid electronic signature use under the acts.

## Requirements for E-Sign
Under the UETA and ESIGN Act, there are four key requirements for any electronic signature use to be legally valid.

### Consent to do business electronically
The parties to an electronic transaction must either display or reasonably imply their consent to transmit information electronically before doing so.

---

**Example: Adobe Acrobat Sign**

^By signing, I agree to the agreement, the ~~Consumer Disclosure~~, and to do business electronically with for\@example.com.^

**Example: DocuSign**

^Please read the ~~Electronic Record and Signature Disclosure~~.^<br>^☐ I agree to use electronic records and signatures.^

### Intent to sign
Like paper-based equivalents, electronic signatures are only valid when a signer displays a willful intent to sign. A standard approach is to ensure that signature lines have a statement that specifically indicates agreement to the terms as well as the choice to sign electronically.

### Association of electronic signature with the record
An electronic record or electronic signature is attributable to a person if it was the act of the person. The act of the person may be shown in any manner, including a showing of the efficacy of any security procedure applied to determine the person to which the electronic record or electronic signature was attributable.

Design a process that is appropriate to the risk level of the transaction or record. You should include greater technical assurance capabilities when there would be a greater likelihood and impact.

### Record retention
In the context of electronic signature, this includes the completed final record as well as the records of evidence for the prior requirements (e.g. documentation of consent being provided). Refer to record retention regulation and policy to determine the required length of retention.

## Prepare for Electronic Signature Use
Work through the following steps to prepare yourself for any electronic signature use you may pursue.

### Step 1: Familiarize yourself with the requirements
Before using electronic signatures, it is important to understand the provisions of the UETA and University policy, including what constitutes an electronic signature and how it can be used to sign contracts and other legal documents.

[Illinois Uniform Electronics Transaction Act (815 ILCS 333/)](https://www.ilga.gov/legislation/ilcs/ilcs3.asp?ActID=4165&ChapterID=67)

### Step 2: Create a secure electronic signature process
Implement a secure process for creating and verifying electronic signatures. This may include using secure authentication methods, such as multi-factor authentication, to verify the identity of the signer. The process must fulfill the legal requirements for electronic signature as well as be appropriate for the risk level associated with the record being electronically signed.

If feasible, use a reliable electronic signature service provider that has been certified by a reputable third-party organization, and that implements appropriate security measures to protect the authenticity and integrity of electronic signatures.

### Step 3: Obtain consent from the recipient
Before a document can be signed electronically, the signer must provide consent to use an electronic signature. The consent to use an electronic signature can be and is often obtained electronically itself.

In order for the consent to be legally valid, it must meet the following requirements:

1. The consent must be presented in a clear manner so that the individual can easily understand what they are consenting to.
2. A record must be captured and retained that demonstrates the consent was presented and how the individual responded.
3. The consent given must be unambiguous and reflect that they clearly understood what they are consenting to (in this case, collection and use of their signature in an electronic form).
4. The individual must be able to revoke their consent at any time.

A common practice is to present a consent prior to the form or document to be signed that meets these requirements. Should an individual decline to consent to electronic signature use, it is recommended that you provide an alternative method that enables a traditional "wet" signature to be received.

### Step 4: Keep records of electronic signatures
Keep records of all electronic signatures, including the date and time of the signature, the identity of the signer, and any supporting documentation. This information should be securely stored and easily accessible for later reference.

By following this guidance, individuals can use electronic signatures in a manner that is compliant with the UETA and have a reliable and secure alternative to traditional paper signatures. 

## Example Electronic Signature Use Scenarios
This section provides example scenarios with relation to the guidance provided above.

These examples are provided to assist in understanding how electronic signature can be used with consideration of risk and legal requirements.

### Scenario 1: Event Space Reservation Agreement
Moderate Risk.

* Terms include responsibilities for safety, prohibitions, and liabilities.
* You could require the use of authentication prior to signing of the agreement. Authentication with a username and password would provide greater assurance than just emailing a document with a signature mark.
* The process documentation, technical configuration, and the records of authentication would be associated with the record to reasonably demonstrate it was the act of the individual.
* A risk is that basic authentication of username and password is known to be weak to compromise through phishing attacks. If the agreement warranted a greater assurance, multi-factor authentication could be additionally required.

### Scenario 2: Annual Performance Evaluation
Moderate Risk.

* The document reflects performance and whether improvement is necessary.
* You could require the use of individual organization email to send the document with a marked signature. The assumption is that authentication is required to access and send email.
* The process documentation and email messages exchanged would be associated with the record to reasonably demonstrate it was the act of the individual.
* A risk is that the performance evaluation documents are downloaded from email and filed in separate storage which no longer has the evidence associated with the record. Since performance evaluations can be central to formal improvement or disciplinary processes, the process should either leverage an alternative method or include steps to capture and retain the email messages with the record.

### Scenario 3: Employee Time Sheet
Low Risk.

* The time sheet reflects the reported time worked by an employee to be approved/signed by their supervisor.
* You could require the use of authentication prior to signing of the agreement. Authentication with a username and password would provide greater assurance than just emailing a document with a signature mark.
* The process documentation, technical configuration, and the records of authentication would be associated with the record to reasonably demonstrate it was the act of the individual.
* A risk is that basic authentication of username and password is known to be weak to compromise through phishing attacks. However, there is a low likelihood that such an attack would target time sheet approval and even if it did, the impact would be low and likely to be easily corrected.

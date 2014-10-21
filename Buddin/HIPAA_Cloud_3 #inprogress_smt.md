Title:				HIPAA in the Cloud - 3: Let's Get Digital
Author:				W. Howard Buddin, Jr., Ph.D. & S. Marc Testa, Ph.D.
Date:				09/04/2013 
Tags:				Backup, Clinical, Cloud, Data, HIPAA, HITECH, Information, Network, PHI, Practice, Storage


## Things to Not Do ##
The following list of practices will probably **NOT** help you if you are audited:

* Storing your patients' PHI on: 
	* Google Docs
	* SkyDrive
	* equivalent service. 
This is just asking for trouble.

* Making your password easy to guess. 
	* See [Dictionary Attack](http://en.wikipedia.org/wiki/Dictionary_attack "Dictionary attack - Wikipedia, the free encyclopedia"). More likely to occur than a Sharknado.
* Using File Transfer Protocol or FTP (use SFTP instead - see below). 

## Things to do: Protecting PHI in Other Ways ##

* Use a network secured with WPA2/PSK at your office **AND** home 
* Use Secure File Transfer Protocol (SFTP)
* Passwords
	* Use strong passwords. 
		* There are applications out there that you can use to generate and save secure passwords (see [1Password](https://agilebits.com/), for instance)
	* Use DIFFERENT passwords for EVERY account you have. No, this is not as easy as what you're used to. Yes, you will thank yourself for putting in the extra work now
	* Your computer should be password protected. Several applications are available to help you both create and manage strong passwords. Here are a few of them to help get you started:
		* [example1]()
		* [example2]()
		* [example3]()
* Harder To Implement, Better Security
	* Verify downloads using SHA5, PGP, or other [Public-Key encryption/authentication software]
	* Create a partition or use a separate volume for PHI (?). 
	    * This would actually be a really sweet idea. You could encrypt that drive and lock it up in a fireproof safe. Use of a scanner to convert all records to .pdf would have you in the clear right away. 
	    * This idea would not just *save* physical storage space, it would obviate the need for it altogether. 
	    * WHAT IF you had your patients fill out their information on a tablet computer while they were in the waiting room. Something easy. Basically, the idea would have to be that if they could fill out a form, they could type this in. Probably no good for several reasons, but just brainstorming. 
	* Use SFTP for file transfers whenever possible

{>> Here's Some Text That Was Cut From Other Articles <<}

Maybe add the entirety of my links note from notational velocity 

## The Mission

{==Various links to use in the main body text:==}

The HIPAA [Security Rule Guidance Material](http://www.hhs.gov/ocr/privacy/hipaa/administrative/securityrule/securityruleguidance.html) page contains links to all the information necessary to get your security up to compliance standards. 

[The HIPAA Privacy Rule and Health IT](http://healthit.hhs.gov/portal/server.pt?open=512&objID=1174&parentname=CommunityPage&parentid=26&mode=2&in_hi_userid=10732&cached=true) 

## The Security Standards

The HIPAA security standards are divided up into four sections (links below will redirect to a downloadable PDF). Even if you're familiar with the guidelines, it may help to get reacquainted with the [overarching principles of covered entities](http://www.hhs.gov/ocr/privacy/hipaa/administrative/securityrule/security101.pdf) before going over those.

1. [Administrative Safeguards](http://www.hhs.gov/ocr/privacy/hipaa/administrative/securityrule/adminsafeguards.pdf)
2. [Physical Safeguards](http://www.hhs.gov/ocr/privacy/hipaa/administrative/securityrule/physsafeguards.pdf)
3. [Technical Safeguards](http://www.hhs.gov/ocr/privacy/hipaa/administrative/securityrule/techsafeguards.pdf)
4. [Organizational Safeguards](http://www.hhs.gov/ocr/privacy/hipaa/administrative/securityrule/pprequirements.pdf)

* A lot has been covered in this post. In part two, the main points of the HIPAA guidelines will be covered. Afterward, we'll outline how can you get your practice or department up to HIPAA compliance standards.

This specific topic is addressed in [*The Nationwide Privacy and Security Framework for Electronic Exchange of Individually Identifiable Health Information*](http://www.healthit.gov/policy-researchers-implementers/standards-interoperability-si-framework) portion of HIPAA. Relatively simplified fact sheets can be found [here](http://www.hhs.gov/ocr/privacy/hipaa/understanding/special/healthit/index.html) To state things conservatively, health care entities now *must* implement full EMR/EHR systems. In 2003, [The Kaiser Permanante Healthcare System](https://healthy.kaiserpermanente.org/html/kaiser/index.shtml) was one of the first in the nation to introduce a way for patients to access and manage many aspects of their healthcare, beyond just their records. Their [EMR system](http://thrive.kaiserpermanente.org/healthy-innovations) affords scheduling appointments and more (the web site is functional and *extremely* well-designed, too). 

The point is not about keeping up with trends or living up to aspirational guidelines, though. The take home message is knowledge and compliance with these standards, and there's good reason for it. The office of Health and Human Services has increased the frequency and size of the fines it will implement for entities that are not compliant. Visiting their website (insert link here) reveals all of the settlements that have recently occurred. Any breach of PHII must be reported.

As we noted in the second part of this series, many of the factors that can get you in trouble can be easily avoided.




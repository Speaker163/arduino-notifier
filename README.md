Arduino Notifier (<http://git.io/arno>)
=======================================
*Library for Arduino (+Ethernet) for iOS app Linux Notifier by OchoCoco (<http://ochoco.co/lino>)*

Installation
============

Add the `/arno/` directory to your Arduino libraries directory.

Usage
=====

Setup:
	
	include '/arno/arno.h';
	
	setup()	
	{
		(…)
		
		arno_setup('TOKEN');
		
		(…)
	}
	
Usage in loop:	
	
	loop()
	{
    	(…)
    	
    	if(something=happened)
    	{
    		arno("I Can't Let You Do That, Dave");
    	}
    	
    	(…)
    }
    
That's it!
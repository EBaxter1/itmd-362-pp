# Production Problem 10: A/B Testing on the Cheap

## The Problem

Locate an interface component on a website that you use frequently that you think could be improved. The improvement should be minor.

Take a screenshot of the interface on both a mobile and desktop device. Then, sketch or illustrate your alternate/"b" test. Finally, describe modification and the HTML, CSS, and JavaScript that you would need to write in order to conduct the test.

## Deliverables

* Screenshots of the interface component on mobile and desktop, placed in this directory (`pp-10/`)

* Sketch or illustrate (e.g., in Photoshop) your alternate/"b" test, placed in this directory (`pp-10/`)

* A text description of the modification, and a description of the HTML, CSS, and JavaScript that you would need to write for the test (you do *not* have to write the actual HTML, CSS, and JavaScript, however)

I would want to change the log out button to be more clear vs using a power button symbol and also make it so the nav bar on mobile screen doesn't cross over the logo

HTML: I would change the label for logout to just say logout instead of the image in desktop view
	  Also change the fact that the logo is in a table tag that the nav bar sits on top off and just place the image directly to the section 
CSS: I would add a media query that made the log out text show otherwise in mobile views show image of people leaving door to show log out in order to save of space. Also make image of logo smaller/make new logo that goes on two lines so that on mobile views wouldn cross behind nav bar with out usering needing to scroll right 
JS: Not needed for this change
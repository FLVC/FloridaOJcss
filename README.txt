This repository has stylesheets related to Florida Online Journals (Florida OJ).  Florida OJ is a journal publishing services hosted by the Florida Virtual Campus (FLVC) and Florida Academic Library Services Cooperative (FALSC).  It is free of charge and open to all institutions in the State University System and Florida College System.  For more information about the service and information about how to request, visit http://falsc.libguides.com/FloridaOnlineJournals .

FALSC currently supports the "Default Theme" in OJS 3.

The Default Theme allows you to upload a custom stylesheet to change the look and feel of a journal.

To select and set up a theme in Florida OJ:
1.  Log into the software, and go to the admin page for your journal.  This is https://journals.flvc.org/yourjournalurl/management .
2.  In the left hand column, click to "Settings", then "Website".  This takes you to the main page with your site's color and banner image.
3.  Look at the drop down menu for "Theme".  At this time, 4 themes are available for OJS 3.  All are anticipated to be available on the production site at the time of the upgrade.  Try out different themes, save the changes, then go to the journal's public view ( https://journals.flvc.org/yourjournalurl/ ) and press CTRL+F5 to refresh the page.
4.  Each theme will have a color picker area. This is labeled "Colour".  You can click on the colored box under the "Colour" heading, and then select a color that you would like to use with the theme.  Try saving a new color, then go to the journal's public view ( https://journals.flvc.org/yourjournalurl/ ) and press CTRL+F5 to refresh the page.
5.  Each theme has a banner image.  This is labeled "Logo".  Try out uploading a logo for the theme you'd like, then go to the journal's public view ( https://journals.flvc.org/yourjournalurl/ ) and press CTRL+F5 to refresh the page.
	Here are recommended banner image sizes for each theme:
		Default Theme:  Banner image should be 80 pixels high.  There is no recommended width, but 600 pixels seems to look good on most browsers.
		Health Sciences Theme:  Banner image should be 80 pixels high.  There is no recommended width, but 600 pixels seems to look good on most browsers.
		Immersion Theme:  Banner image should be 135 pixels high.  There is no recommended width, but 600 pixels seems to look good on most browsers.
		Classic Theme:  Banner image should be 50 pixels high.  There is no recommended width, but 600 pixels seems to look good on most browsers.
		Additionally, we recommend that you keep a larger version of your banner image handy in your records, in case you would like to change to a new theme and resize the image.

To upload a custom css to the Default Theme:
* Look under the heading for "Journal style sheet", and click to "Upload" a .css file.
* Save changes.
* Go to your journal's homepage and press ctrl+F5 on the keyboard to refresh the page.



Using this repository:

This repository has tweaks you can upload or modify, in order to change the Default Theme.

* TemplateStyleSheet_DefaultTheme_JournalHomepageImageChanges.css
** Includes changes to modify the display of the Homepage Image.  The default display in the Default Theme is that the image is sized to fit the width of the page, so very large, and does not have padding between the Homepage Image and the banner area.
** This template style sheet has individual changes, which are indicated by comments in the .css which allow you to:
*** Resize the Homepage Image to be smaller.
*** Add some space between the Homepage Image and the banner area.
*** Center the Homepage Image on the screen.

* TemplateStyleSheet_DefaultTheme_BannerImageChanges.css
** Includes changes to modify the display of the banner image in the Default Theme.  The default display in the Default Theme is that the banner image is resized to 80 pixels talls.  In response to requests from journals, this stylesheet allows a journal to make the banner image larger.
.. ==================================================
.. FOR YOUR INFORMATION
.. --------------------------------------------------
.. -*- coding: utf-8 -*- with BOM.

.. include:: ../Includes.txt


For Administrators
================

Install the latest version of "sd_lightbox" from the TER
--------------------------------------------------------

1. Switch to the module "Extensions"
2. Select "Get Extensions"
3. Search for "sd_lightbox"
4. Download and install "sd_lightbox"


Include static template
-----------------------

In your root template add the static template of "sd_lightbox"


Configuration
-------------

All configurations of "sd_lightbox" can be done via the "Constant Editor"


Add class to links
------------------

Finally you just need to add the class "sd-lightbox" to your lightbox links.
An Example configuration for "fluid_styled_content" is the following:

::
	styles {
	  content {
	    textmedia {
	      linkWrap {
	        lightboxCssClass = sd-lightbox
	        lightboxRelAttribute = sd-lightbox[{field:uid}]
	        lightboxEnabled = 1
	      }
	    }
	  }
	}

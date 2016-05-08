## [From Gentoo wiki]
With the addition of **layman-2.2.0** a new utility was added to assist users in this process that goes by the name of layman-overlay-maker. As long as the overlay information has been properly added via the prompts, layman-overlay-maker will create a XML defined overlay and save into /etc/layman/overlays or the specified in the layman configuration file for overlay_defs.

**layman-overlay-maker** can become a useful tool in assisting users who would like to submit a patch to have their overlays added to the official repositories.xml file.

To use the utility simply invoke it by name:
>**root #**layman-overlay-maker

and go through its prompts until completion.  
When finished run:
>**root #**layman-updater -R

Followed by
>**root #**layman -a <name>

where <name> is the name of the overlay you just created.

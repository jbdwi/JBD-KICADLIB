A. Licenses
This repository is a collection of my private KiCad libraries, and-or modification of the official Kicad Library, and-or from other open sources which refer to the GNU/PL. 

A number of libraries in the repository have been pushed to the official Kicad github repository, though not always been assessed and accepted by official KiCad librarians.

You can freely use or modify as long as following with the GNU/PL's  procedures, protocols and clauses.  Although not a necessity, it is most appreciated if you mention the sources.



B. The Libraries
The KiCad libraries I fit in this repository are :
1. E-ESchema Component (*.LIB and *.DCM)
2. Component Footprint (*.KICAD_MOD)
3. Component 3dmodels VRML ( *.WRL )
4. Component 3dmodels ( *.WINGS )
5. Related Documents in PDF format or Bitmap (jpg, png, bmp ).




C. Library Folder Hierarchy
The folder structure of this repository is exactly the same as the arrangement official KiCad folder. However, you may set it in accordance with your own folder structure. What needs to do is, fitting  properly the 3dmodels path of a footprint file  by text editing the *. KICAD_MOD or by editing the footprint with KiCad PCB Footprint Editor.
jbd-kicadlib
	library
		abc.lib
		abc.dcm

		libraries_doc			// this folder doesn't exist in the official KiCad library
			abc.jpg			// simplified component specs and-or its 2d image
			abc.pdf		// detail technical specs, whenever available
	modules
		xxx.pretty
			yyy.KICADMOD	// footprint files

		packages3d
			xxx.3dshapes
				yyy.WRL	// 3d model files
				yyy.WINGS	// 3d model files

			footprints_doc
				yyy.jpg	// simple  footprint dimensions and its 3d shape
				yyy.pdf	// detail technical specs, whenever available
	


D. Corrections and Suggestions
I do realize that the library style in this repository does not always fit with the your 'taste' or 'style'. You can always able to edit or modify it by editing the library files. And of course, there are possibly some unintentionally errors, improper, inappropriate, lacking of  precision, typo error, etc. I did make.  So, please let me know and let me have your correction, criticism,  suggestions, advices or proposals. And if there is any demand for a specific library that does not exist yet in this repository, please let me know. If it is available in my libraries I will gladly put it in this repository. If not ready in my libraries, especially for 3dmodels and footprint, then happily I will make it as long as you send me the detail component's document. As soon as my time is available, I will push it in this repository for you.


E. Communication / Contact
Communication can be done by writing an issue in this repository. But since I do not always monitor to this repository, please don't hesitate to contact me via my email or Facebook account.
e-mail		: jbdwiyono@gmail.com
Facebook	: Josef B. Dwiyono (jbdwiyono@facebook.com)


Hope this useful !

September 27, 2015

Regards,
JBD

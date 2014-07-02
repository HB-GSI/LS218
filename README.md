LS218 extends the CSPP_Core package of the CS++-Project. 

It contains derived actor classes of the CS++DeviceActor base class for the LakeShore 218 Temerature Monitor.

Refer to https://github.com/HB-GSI/CSPP for CS++ project overview, details and documentation.

LabVIEW 2013 is currently used development.

Related documents and information
=================================
- README.txt
- Release_Notes.txt
- EUPL v.1.1 - Lizenz.pdf
- Contact: H.Brand@gsi.de or D.Neidherr@gsi.de
- Download, bug reports... : http://github.com/HB-GSI/LS218
- Documentation:
  - Refer to Documentation Folder
  - Project-Wiki: https://github.com/HB-GSI/CSPP/wiki
  - NI Actor Framework: https://decibel.ni.com/content/groups/actor-framework-2011?view=overview

You can use this package as GIT Submodule.

External Dependencies
=================================
- CSPP_DeviceBase: http://github.com/HB-GSI/CSPP_Core
- LS218 instruemnt driver: http://sine.ni.com/apps/utf8/niid_web_display.model_page?p_model_id=1171
  tested with 042109|Model:218S|S/N:21SAH8.

Getting started:
=================================
- Add LS218-Content.vi into your own LabVIEW project. You can drag the desired libraries from the dependencies into your virtual project folder structure.
- You need to extend your project specific ini-file.
  - Sample ini-file should be available for all classes, either in the LV-Project or on disk in the corresponding class or package folder.
- You need to create and deploy your project specific shared Variable libraries.
  - Sample shared Variable libraries should be available for all concerned classes on disk in the corresponding class or package folder.
- Check MAX for VISA Resource Name of your LS218.


Author: H.Brand@gsi.de, D.Neidherr@gsi.de

Copyright 2013  GSI Helmholtzzentrum f�r Schwerionenforschung GmbH

Planckstr.1, 64291 Darmstadt, Germany

Lizenziert unter der EUPL, Version 1.1 oder - sobald diese von der Europ�ischen Kommission genehmigt wurden - Folgeversionen der EUPL ("Lizenz"); Sie d�rfen dieses Werk ausschlie�lich gem�� dieser Lizenz nutzen.

Eine Kopie der Lizenz finden Sie hier: http://www.osor.eu/eupl

Sofern nicht durch anwendbare Rechtsvorschriften gefordert oder in schriftlicher Form vereinbart, wird die unter der Lizenz verbreitete Software "so wie sie ist", OHNE JEGLICHE GEW�HRLEISTUNG ODER BEDINGUNGEN - ausdr�cklich oder stillschweigend - verbreitet.

Die sprachspezifischen Genehmigungen und Beschr�nkungen unter der Lizenz sind dem Lizenztext zu entnehmen.
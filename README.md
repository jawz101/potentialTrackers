# potentialTrackers
investigating potential trackers for consideration as definitions for Exodus ETIP.
https://etip.exodus-privacy.eu.org

Sources:
- data already in [Exodus ETIP](https://etip.exodus-privacy.eu.org)
- [Marketing Technology Landscape Supergraphic (2019): Martech 5000 (actually 7,040)](https://chiefmartec.com/2019/04/marketing-technology-landscape-supergraphic-2019/)
- 3rd party domains gathered from mobile device traffic
- unclassified class names found in Android applications
and various other public literature


Tips for tracker investigation:

Visit the company website of the potential tracker.  Look for indicators of the type of business, products, and descriptions that may serve as excerpts for tracker description.

Finding SDK Integration Documentation
Review the site for any developer/support/help/documentation links on the site.
Take note of the link to the instructions to add their code libraries to an Android application.

Review the documentation on that page for keywords such as "build.gradle", "maven", "import" to find potential code signatures.

*other tricks to find code library documenation and examples might be to
  - search github for https://github.com/ <company>
  - https://bintray.com/ <company>
  - do a search on VirusTotal for any support/help/developer subdomains https://www.virustotal.com/#/domain/ and see if they reveal a support site containing information.

  - download a copy of [this hosts file](https://raw.githubusercontent.com/jawz101/MobileAdTrackers/master/hosts) for any potential network signatures
  - download a copy of [this huge file](https://github.com/Exodus-Privacy/exodus/issues/40#issuecomment-377795965) of class names previously found in apps scanned by the Exodus project.

...Open both in a text editor such as Notepad++ and search to see if the company name is a part of a class name or domain that was previously seen.

If you found a tracker with at least documentation and a code signature, add it to ETIP!

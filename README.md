# Semi-Automated FAST Reconciliation for Hyrax-based Repositories

This is the Github repo for my (Tiffany Chan's) presentation at *Open Repositories 2023: Repositories unlocked for discovery and interoperability*. Here is [the abstract](https://www.conftool.net/or2023/index.php?page=browseSessions&form_session=475&presentations=show):

>OCLC FAST is a widely-used subject heading schema/authority that is interoperable with Samvera software applications such as Hyrax. However, FAST is also a moving target: OCLC frequently adds new headings, deprecates obsolete ones, modifies other headings, and splits one subject heading into multiple headings. This creates a maintenance/labour problem for Hyrax-based repositories, for which FAST changes must be manually tracked and reconciled with existing metadata. This presentation describes some software, called FASTupdater, and a workflow for automatically parsing and applying changes to such repositories.
 
>Put simply, FASTupdater downloads and parses Excel spreadsheet files from the FAST Changes page (http://fast.oclc.org/fastChanges/), and then searches the repository for URIs or human-readable labels that require updates. Where possible, FASTupdater changes records automatically. Changes that cannot be completely automated, such as split or obsolete headings, are aggregated and forwarded to staff who can take the appropriate action.

I built the slide deck using a combination of [reveal.js](https://github.com/hakimel/reveal.js) and [slides.com](https://slides.com/tiffchan).
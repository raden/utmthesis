# Contributors Wanted!! #

**Major Update: The utmthesis project is now at [version 3.13](http://www.fke.utm.my/postgraduate/wp-content/uploads/2014/11/utmthesis-template-v3.13.zip).** See below to read the list of changes. It is now 99.99% compliant to the UTM thesis format, and should be accepted by SPS without any issues. We have also recently released a LyX layout for those who prefer to use that.

Like any free and open source software (FOSS) project, we welcome your contributions, including bugfixes, bug reports, code sharing, helping new users, giving classes, suggesting solutions, and coffee. ~~We like hot coffee.~~ Please stop giving us coffee, we cant sleep at night.

You can also contribute by thanking us in your **acknowledgement** section like this: _I would also like to thank the developers of the utmthesis LaTeX project for making the thesis writing process a lot easier for me. Those guys are unbelievably awesome!_

Report bugs at the [issues page](http://code.google.com/p/utmthesis/issues/list). If you are good at ironing out LateX bugs, send us your bugfixes for the _utmthesis.cls_ file, and we will merge it into the project and name you as a contributor.

Contact us anytime at [utmthesis-discuss](http://groups.google.com/group/utmthesis-discuss), do send us an email.

# The Utmthesis Project #

The Utmthesis Project provides and maintains a LaTeX class and BibTeX styles (for both authordate and number citation styles) to typeset your thesis according to the Universiti Teknologi Malaysia (UTM) thesis formatting rules. It is currently the most time saving and efficient way to write a UTM compliant thesis.

This is an ongoing project that has received support and official recognition by UTM for use in thesis publication. It a free software project licensed under the New BSD License.

Even though you just spent 1-2 days writing the content of your thesis (because you are lazy), you can instantly generate the entire thesis in PDF with fully formatted table of contents, references, appendix, front cover, etc. This results in a beautifully written shiny magical thesis with no errors that will bedazzle your supervisors and examiners, guaranteeing you an A+. Maybe not.

There are tutorials, tips & examples on how to use LaTeX provided in the downloads and wiki section.

~~Download the latest version of utmthesis (both in LaTeX and LyX)
[here](http://code.google.com/p/utmthesis/downloads/list)!~~
Due to upload limitation imposed by Google, we could not upload new updates here. Temporarily, we provide download links from [FKE Postgraduate Website](http://www.fke.utm.my/postgraduate/wp-content/uploads/2014/11/utmthesis-template-v3.13.zip) while we are trying to resolve the upload restriction here.


# Required Software #

You will need to download and install certain software in order to start writing your thesis, journals, and papers with LaTeX:
  1. A good LaTeX compiler. [ProTeXt](http://www.tug.org/protext/) (download [here](http://mirror.ctan.org/systems/windows/protext/)) is highly recommended in Windows. In Linux, install [TeX Live](http://www.tug.org/texlive). **Note: If you install a minimal/basic version of a Latex compiler, you will face problems. Go for the full download.**
  1. A good LaTeX editor such as [TeXstudio](http://texstudio.sourceforge.net/) or [Texmaker](http://www.xm1math.net/texmaker), available for both Windows and Linux.
  1. You may also opt for [LyX](http://www.lyx.org) front-end. Highly recommended for those incline to WYSWYG-like.
  1. (Optional) A good reference managing software to manage your _.bib_ file. [Mendeley](http://www.mendeley.com) and [Jabref](http://jabref.sourceforge.net) comes highly recommended.

For Linux users, specifically [Ubuntu](http://www.ubuntu.com) (or Debian based distros) type the following command in your shell to auto-magically install all the above software like a boss:
```
sudo apt-get install texlive-full texmaker jabref
```


# Thesis Printing Guide #

To guarantee that your thesis is properly printed, ensure that the following settings are set in your printer job options:
  * Paper type : **A4** (_The paper used for the thesis is A4. Sometimes this is incorrectly set at the printer itself._)
  * Page Scaling : **None** (_It is a common mistake to select "Fit to printable area", or "Shrink to printable area", or similar. Leave it at "None"._)
  * Scale : **100%** (_This causes the page to zoom in/out. Leave it at 100%._)

Failing to set these printer job options will result in a printout that is out of scale/margin.

# What's New? #

  * Major release, includes many bugfixes that caused the previous version to fail the formating check done by SPS. The release for this version of utmthesis is done with cooperation with SPS officers.
  * UTM thesis formatting bugfixes include:
    * Centering the word "TITLE" (in all ToC) to the center of the paper.
    * Moved table/figure/appendix/algo numbers flush to the left in their respective tables in the ToC.
    * Moved table/figure/appendix/algo captions 2.5cm to the right in their respective tables in the ToC.
    * Bolded page number for the main chapters and reference chapter in the main ToC. This is not in the thesis manual (2007), but is enforced by SPS.
    * List of Appendices was incorrectly capitalizing all appendix titles.
    * List of Abbreviation and Symbols was incorrectly spaced.
    * The award declaration of page was incorrectly parsed, it should be properly broken into 3 sentences.
    * The listing of appendices in the main ToC was incorrectly positioned.
    * All bugfixes are compatible with both English and Malay versions of the thesis.
  * This version also includes a guide for properly printing the generated PDF thesis in the README.
  * The example thesis included now uses (and recommends) PDFLaTeX instead of regular LaTeX.

# Core Features #

  * 99.99% compliant with the formatting requirements in UTM Thesis Manual (July 2007) and SPS requirements.
  * Support thesis written in Malay.
  * Support for LyX (~~still in beta stages, but~~ very functional).
  * Minimal package dependency (required packages: parskip, setspace, acronym, times).
  * Support BibTeX users.
    * Provide BibTeX styles for both UTM authordate and number citation systems.
    * Support natbib package.
    * More BibTeX entry examples in tests/bibtex/ directory.
    * Finally, no more referencing headaches.
  * Support hyperref package to generate inter-page links/bookmarks in PDF.
  * Support acronym package to generate List of Symbols/Abbreviations page.
  * Includes two thesis samples for new users:
    * A LaTeX version
    * A LyX version
  * Added an optional list of algorithms.
  * Support hyperref
  * Support up to **FIVE supervisors** (I am not kidding, added this due to requests from users)
  * Support manual splitting of titles up to three lines.
  * Includes two pages showing "insert XXX form here" for ease of replacing with official forms after printing out the thesis:
    * Cooperation declaration form.
    * PSZ 19:16 form.


# Bugs/Issues #

If you have any basic problems or need help, please discuss it at [utmthesis-discuss](http://groups.google.com/group/utmthesis-discuss) group.

If you have found any legitimate bugs or issues, please report and discuss it at the [issues page](http://code.google.com/p/utmthesis/issues/list). We will take a look at the problem and try to fix it if possible. However, this is not the place to ask for help, use [utmthesis-discuss](http://groups.google.com/group/utmthesis-discuss) for that.

Please also report broken links on this homepage and anything else that is inconsistent.

If you think LaTeX and the utmthesis project is full of bugs and is a waste of your time, then we apologize. Please take this [free coupon](http://www.amillionlives.net/wp-content/uploads/2011/05/Internet-Coupons.gif) for your troubles, and accept our apology.
------------------------------------------------------------------------------------------
Notes on US-ELTP KSP template (version 1.3)
1 November 2018, M. Dickinson
------------------------------------------------------------------------------------------

LaTeX template for writing US ELT Program Key Science Program Description Documents
(aka "proposals").

Please fill in all sections.

The Scientific Justification should be limited to 4 pages including figures (but not including
references.) There are no strict page limits for other sections, or for the document as a whole, 
but we suggest a guideline of 8 to 10 pages (excluding cover page and investigators) for the 
whole document.

------------------------------------------------------------------------------------------
LaTeX template (copy & edit):  template_useltp_ksp.tex
Style file:                    useltp_ksp_1.3.sty
Title page banner graphic:     USELTP_KSP_header_crop.pdf
This file:                     README.txt
------------------------------------------------------------------------------------------

SCIENTIFIC CATEGORIES (\sciencecategory{})

Please select a scientific category that best describes your program by uncommenting only 
ONE of the selections below.  
NOTE:  We will probably change this in a future update to allow multiple topical areas.


TITLE (\title{})

Give a descriptive title for the proposal in the \title{} command.

Note that a title can be quite long; LaTeX will break the title into separate lines 
automatically.  If you wish to indicate line breaks yourself, do so with a `\\' command at 
the appropriate point in the title text.  Use both upper and lower case letters (NOT ALL CAPS).


ABSTRACT (\begin{abstract} \end{abstract})

Give a general abstract of the scientific justification appropriate for a non-specialist.
Write between the \begin{abstract} and \end{abstract} lines.


TEAM MEMBER INFORMATION BLOCKS (\begin{team_member} \end{team_member})

Please give names, affiliations, and e-mail addresses of team members here.
DO NOT remove the \teammembers, \begin{team_member} and \end{team_member} tags.
Only one individual's name per \name field is allowed.

NOTE: We will likely improve the formatting of this section in a future version of this template.


SCIENTIFIC JUSTIFICATION (\sciencejustification)

Describe the scientific context for this Key Science Program, the specific research question(s)
to be addressed, and the overall significance to astronomy.  The Scientific Justification 
should be limited to 4 pages including figures.


TELESCOPES AND INSTRUMENTS (\telinstreq)

Discuss the program requirements for the telescope(s) (GMT and/or TMT), instrumentation, 
and adaptive optics systems.  Use of both TMT and GMT in an integrative fashion merits 
particular attention.  If the program can be carried out using instruments planned for the 
GMT/TMT early-light suites, discuss what particular capabilities (e.g., spectral resolution, 
angular resolution, AO performance, etc.) are required.  If new capabilities beyond the 
defined early-light instruments are needed, describe the requirements in a suitable level 
of detail.


EXPERIMENTAL DESIGN (\expdesign)

Describe the details of the observational program, including:
 o Target/sample selection.  This may be a description of a target selection strategy that would be 
   appropriate in the future when the project would be executed. Specific targets may be specified, 
   particularly if they demonstrate the value of a 2-telescope, 2-hemisphere system.
 o A description of the required observations.
 o Signal-to-noise requirements and exposure time estimates.  Because the detailed parameters of future
   instruments may not be precisely known now, this section should discuss the assumptions adopted.
 o Special requirements for observing conditions (if appropriate), in particular with regard to 
   image quality and adaptive optics, precipitable water vapor, or other special conditions.
 o Scheduling requirements (as appropriate), including lunar phase, observing cadence, 
   and/or timing constraints.


OBSERVING PROGRAM SUMMARY (\obssum)

Summarize the overall observing program.  This should include: 
 o A high-level review of the program as it would be executed, potentially over several years, 
   including the sequence of observations if relevant.
 o The total observing time required for each telescope, instrument, and instrument mode used, 
   based on the detailed information from the Experimental Design.


LEGACY VALUE (\legacyvalue)

Discuss the legacy value of these observations and the data they would generate for the broader 
scientific community, including a description of potential data products and the ancillary 
science that might be enabled by this dataset.


ANALYSIS PLAN (\analysisplan)

Describe the program requirements for data analysis and interpretation.  This may include:
 o Data management and software needed for data reduction and analysis.
 o Simulations needed to interpret the data.
 o Other resources (e.g., computational, user support) that may be necessary.


SYNERGY WITH OTHER FACILITIES OR RESOURCES (\otherfacilities)

If relevant, describe how the proposed TMT/GMT observations complement data from other facilities. 
This may include: 
  o Required coordination between the proposed GMT/TMT program and observations or data resources 
    from other facilities in space or on the ground. 
  o Preparatory or ancillary datasets that will be required to carry out this Key Science Program.


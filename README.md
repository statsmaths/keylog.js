# keylog.js: An Open Source Pedagogical Tool

Keystroke logging, or keylogging, consists of recording the time and
identity of the keys that a user types on a keyboard. When run without
a user's consent, malicious applications of keylogging include stealing
private login credentials and other personal data. It is also possible,
through the analysis of relatively short samples, to use keylogging 
information as a method for tracking and surveillance across websites.
This also happens largely without a user's knowledge or consent. However,
not all applications of keylogging are  pernicious. Keylogging
data is an important and comparitively unobtrusive source of data for
academic applications in fields such as linguistics, psychology,
cognitive science, medicine, and human-computer iteraction. The
power and simplicity of keylogging techniques that make them very
popular for a wide range of applications also make keylogging an 
excellent pedagogical tool for building awareness of the ethical and
social aspects of emerging technologies.

`keylog.js` is a minimal javascript-based tool that
provides privacy-focused, client-side keylogging software served
through a static website. No programming knowledge is needed to use the
software. The static website and all of the code are hosted on an open
GitHub repository. The site consists of a short disclaimer about the
collection of data, a text entry box, a link to the source code, a button
to clear the form, and a buttons to save the data being produced. 
The software records every keystroke and mouse click done inside of the
text entry box. However, the data never leaves a user's local computer
and never includes anything done outside of the text entry box. The 
dataset produced by the software is formated as a CSV file that can be
opened by any standard spreadsheet software or programming language.


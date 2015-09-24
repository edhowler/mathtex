Mathtex is a parser and renderer for LaTeX math expressions. Based off of the Mathtex component of the Python plotting library, matplotlib.

## News ##
  * **17th August 2009:** Version 0.3 released. Tarballs can be found on the **Downloads** page.
  * **11th August 2009:** Version 0.3 RC 1 released. Tarballs can be found on the **Downloads** page. There was no final 0.2 release.
  * **5th August 2009:** Version 0.2 RC 1 released. Tarballs can be found on the **Downloads** page.
  * **31st July 2009:** Version 0.1 released. Tarballs can be found on the **Downloads** page.
  * **28th July 2009:** Version 0.1 RC 2 released. Tarballs can be found on the **Downloads** page.
  * **28th July 2009:** Version 0.1 RC 1 released. Tarballs can be found on the **Downloads** page.
  * **27th July 2009:** Matplotlib updated to use mathtex; work available in the mathtex branch of matplotlib.
  * **16th July 2009:** Externalisation from matplotlib mostly complete; API documentation in-progress.

## Downloads ##
The most recent stable release of mathtex is 0.3. It can be downloaded here: http://mathtex.googlecode.com/files/mathtex-0.3.tar.gz.

## Features ##
Although much work is still needed mathtex currently supports a reasonable subset of the LaTeX math grammar using either _computer modern_, _STIX_, or unicode fonts.

In addition to a native Python interface, mathtex also includes a command line utility, which can often replace the traditional latex + dvipng work-flow for rendering math.

Currently two backends are provided: Image and Cairo. While the Image backend is limited to bitmap output the Cairo backend is able to render equations to any of the formats supported by the cairo library. This includes: SVG, PDF and PostScript.
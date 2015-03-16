Download the compiled pdf version [here](https://github.com/Debdut/vala-guide/blob/master/downloads/The-Vala-Guide.pdf?raw=true)

To compile this project download the entire source tree and run

$make

You will need to have the following installed for the system to generate the document correctly.

	* XeteX
	* Pygments
	* The following Tex packages
		* Minted
		* ifplatform
		* The fancyvrb
		* color

On Ubuntu/Debian the necessary Latex packages can be installed with the command
sudo apt-get install texlive-xetex texlive-latex-recommended texlive-latex-extra

You can installed the pygments source code highlighter with the following command.
sudo apt-get install python-pygments

Be warned however as this downloads nearly 400 MB of packages.

Download Minted package [minted.sty](https://code.google.com/p/minted/downloads/list) and copy it to /usr/share/texmf-texlive/tex/latex/, and then to update TEX:

$sudo texhash
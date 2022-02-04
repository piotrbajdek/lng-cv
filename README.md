# WHAT IS LNG-CV

lng-cv may stand for _"language converter"_, _"linguistic converter"_, _"lenguaje convertido"_, and the like.

lng-cv constitutes a set of linguistic tools which allow **(a)** displaying pronunciation of a phrase and **(b)** converting between different (e.g., regional) norms of orthography when a word or some piece of text is provided as an argument directly from the command line.

Multiple modern and ancient languages are (projected to be) supported.

# END OF LIFE

lng-cv is considered deprecated in favor of lngcnv, which has been completely rewritten from Pascal into Rust. Please, install lngcnv: https://github.com/piotrbajdek/lngcnv

Since the sister project lngcnv (in Rust) is where the further development occurs, lng-cv (in Pascal) will no longer be maintained.

# SUPPORTED LANGUAGES

**1. English:** orthography

**2. Latin:** pronunciation & orthography

**3. Quechua:** orthography

**4. Tikuna:** pronunciation & orthography

Support for more languages (including **Polish**, **Spanish**) is under active development (**lngcnv**).

# INSTALLATION

**1a.** Download the binary "lng-cv" for Linux x86_64.

**1b.** Alternatively, lng-cv can be compiled from sources by Free Pascal:

fpc ./lng-cv.pas

**2a.** If access is denied, make the file executable:

sudo chmod +x ./lng-cv

**3a.** Install lng-cv via copying the binary to /usr/bin/

sudo cp lng-cv /usr/bin/

**3b.** On Fedora Silverblue / Kinoite:

sudo cp lng-cv /var/usrlocal/bin/

# CHECK OUT THE LNG-CV WIKI:

https://github.com/piotrbajdek/lng-cv/wiki

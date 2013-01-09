This is built apon
CTAN:support/vc
# The original files can be found at CTAN:support/vc.
# Theses file are Public Domain.

USE
Place complete folder alongside .git

Include line where VC Information required.

\input{vc-reporting/revisioninfo.tex}

Inserted page layout can be changed within revisioninfo.tex

NOTE
\write18 support is required within the Latex engine.

ABOUT
This allows you to run vc for tex from a folder within the directory so is cleaner than the normal method.

TODO (Though I have no intention of doing so)
Add support to other VCs (other than GIT)

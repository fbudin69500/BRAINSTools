When updating BRAINSTools in Slicer, follow these steps:

* Create a new branch. For branch naming convention, see http://wiki.slicer.org/slicerWiki/index.php/Documentation/Nightly/Developers/Versioning#Project_fork
* Commit required and new patches
** COMP: Address MacOSX packaging issue. (47dc8e6) -> is always required
** DOC: Addition of README.Slicer.md -> is always required
** commit new patches
* Push new branch to https://github.com/Slicer/BRAINSTools.git
* Update BRAINSTools tags in https://github.com/Slicer/BRAINSTools.git (this is necessary as BRAINSTools configuration searches for the most
recent tagged version to configure the version number at configuration time).

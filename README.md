# semiconductorDefects

This is an attempt at creating a collection of all the defect parameters of semiconductors in plain text. The information about the defects is contained in both the file structure and the end files. The finial files are written with [yaml](https://en.wikipedia.org/wiki/YAML) syntax.
At the moment the database contains:

1. The Shockey Read Hall defect parameters, stored in .srh files:
  * Et: The defects energy level
  * &sigma;~e~: The electron capture cross section
  * &simga;~h~: The hole capture cross section
  * k: The ratio of &sigma;~e~/&sigma;~h~. This is recorded as lifetime spectroscopy measurements only provide a measure of the ratio of the capture cross sections and not the total capture cross sections.

The database is currently formatted in the following manner:


* database folder

    * folder representing the bulk material

         * folder representing the element in the defect

             * file containing the defect, with a .srh extension.

# Changes in mirtCAT 0.3

- graded response model Fisher information matrix added

# Changes in mirtCAT 0.2

- temporary files can now be saved while the GUI is running, and restored at a later time

- more estimation options can be passed to `fscores()` via the ... argument

- sensitive objects are now removed from the package namespace when the `mirtCAT()` finishes 
  unsuccessfully 

- categories are always returned with based 1 for first response in the GUI

- add content balancing option

- various bug fixes, and update documentation

- new `findNextItem()` input for users to locate the next item to administer (likely for custom
  CAT interfaces that do not use the Shiny package). Can be updated with the `updateDesign()` 
  function
  
- moved 'Next' button in the web interface to the left panel box so that it will always remain in 
  the same location
  
- support CSS customization

- switch multidimensional selection criteria to use analytical expressions rather than numerical.
  Several multivariate Fisher information matrix computation currently not supported analytically,
  but will be steadily added.
  
- add classification capabilities to `design` list input
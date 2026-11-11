---
output: pdf_document
fontsize: 12pt
colorlinks: true
---

\thispagestyle{empty}
\today

Emi Tanaka  
Editor-in-Chief     
The R Journal  
\bigskip

Dear Dr. Tanaka,
\bigskip

Thank you for the opportunity to revise our manuscript entitled "DrivePlotR: 
Shareable Linked Plot Maps for Multivariate High-Resolution Spatio-Temporal 
Data" (RJournal 2026-79) for consideration for publication in the R 
Journal. We appreciate the valuable feedback we received from you and the 
reviewers.

We carefully examined all comments and revised our manuscript and package to 
address the concerns mentioned. A summary of the key modifications is given 
below:

* We updated `DrivePlotR`'s default tile provider for the maps and added the
`tileprovider` argument to the `driveplot` and `driveplot_map` functions to 
prevent the problems the reviewers experienced with the map tiles not 
rendering properly.

* We improved `DrivePlotR`'s support for visualizing multiple vehicle 
trajectories by adding the `group` argument to the main functions. We added an 
example with multiple vehicle trajectories to the manuscript in Section 4.4 
(Comparison of driving behaviors).

* We explained why data format requirements mean that `DrivePlotR` cannot accept 
`LINESTRING` data.

We include a complete point-by-point response to all comments in the 
accompanying document. Our edits in response to these insightful comments have 
further improved the manuscript and package.

The updated version of `DrivePlotR` may be downloaded from GitHub using the 
following code: `pak::pak("hardtme/DrivePlotR")`.

We have not yet resubmitted `DrivePlotR` to CRAN in case further changes to the
package are suggested. We will resubmit to CRAN after we address any potential 
further changes to `DrivePlotR`.

Thank you for your time and consideration of our work. We look forward to 
hearing from you soon.
  

\bigskip
\bigskip

Sincerely,
    
    
    
    
Marie Hardt  
Department of Statistics  
Iowa State University  
Ames, Iowa, USA  


\bigskip



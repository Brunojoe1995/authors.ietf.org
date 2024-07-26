---
title: References
description: 
published: true
date: 2024-07-25T00:18:53.317Z
tags: 
editor: markdown
dateCreated: 2024-07-25T00:18:53.317Z
---

> THIS PAGE IS UNDER CONSTRUCTION
{.is-warning}

RFC 7322 Section 4.8.6 provides details on the output formats of references in RFCs.  It is 

# Referencing RFCs
References to RFCs are automatically generated by most author tools chains. If you choose to manually add an RFC reference, then please note that this will be replaced with a generated reference if your I-D is approved for publication.

For information on how to create references to RFCs, including to specific sections, see [References in RFCXML](/references-in-rfcxml), which explains this for RFCXML authors.

## Published format
For one author or editor, references to RFCs appear as follows: 
```
[RFCXXXX]  Last name, First initial., Ed. (if applicable), “RFC Title”,
           Sub-series number (if applicable), RFC number, DOI, 
           Date of publication, <https://www.rfc-editor.org/info/rfc#>.
```
Example:
```
[RFC3080]  Rose, M., “The Blocks Extensible Exchange Protocol Core”, 
           RFC 3080, DOI 10.17487/RFC3080, March 2001, 
           <https://www.rfc-editor.org/info/rfc3080>.
```
This is a change to Section 4.8.6.2 of RFC 7322 as the Digital Object Identifier (DOI) is now listed in each reference to an RFC.

# Referencing STDs and BCPs
References to STDs and BCPs are automatically generated by most author tools chains. If you choose to manually add an STD or BCP reference, then please note that this will be replaced with a generated reference if your I-D is approved for publication.

As STDs and BCPs may consist of a single RFC or multiple RFCs, if you wish to refer to a specific RFC that is part of an STD or BCP then your text should refer to the specific RFC number as part of the text, not as a citation, and immediately follow that with a citation for the subseries number. For example:

```
    See RFC 3552 [BCP72].
```

## Publication format
An STD reference entry will include ALL of the RFCs comprising that subseries, formatted as follows:
```
[STDXXX]  Internet Standard XXX, <https://www.rfc-editor.org/info/std#>. 
          At the time of writing, this STD comprises the following:

          Last name, First initial., Ed. (if applicable), “RFC Title”, 
          STD XXX, RFC number, DOI number, Date of publication, 
          <https://www.rfc-editor.org/info/rfc#>.
          
          (The above is repeated for all the RFCs in the subseries)
```
Example:
```
[STD80]  Internet Standard 80, <https://www.rfc-editor.org/info/std80>. 
         At the time of writing, this STD comprises the following:

         Cerf, V., “ASCII format for network interchange”, STD 80, 
         RFC 20, DOI 10.17487/RFC0020, October 1969, 
         <https://www.rfc-editor.org/info/rfc20>.
         
         (The above is repeated for all the RFCs in the subseries)
```
A BCP reference entry will include ALL of the RFCs comprising that subseries, formatted as follows:
```
[BCPXXX]  Best Current Practice XXX, <http://www.rfc-editor.org/info/bcp#>.
          At the time of writing, this BCP comprises the following:

          Last name, First initial., Ed. (if applicable) and First initial. 
          Last name, Ed. (if applicable), “RFC Title”, BCP XXX, 
          RFC number, DOI number, Date of publication, 
          <https://www.rfc-editor.org/info/rfc#>.
          
          (The above is repeated for all the RFCs in the subseries)
```
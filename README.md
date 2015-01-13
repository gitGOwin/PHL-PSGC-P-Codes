# PHL-PSGC-P-Codes
Some of my projects require me to work through various iterations of the PSGC. The irksome thing with it is that codes assigned to a geographic entity are subject to change from one year to another. Although it doesn't happen very often my use case still requires me to use P-codes that are applicable for any given year. 

Philippine Place code (P-Code) matrix from 1990-2014, from the [Philippine Standard Geographic Codes](http://www.nscb.gov.ph/activestats/psgc/default.asp)

##Changelog
2015-01-13 - Added column "note." Fixed typograhical errors
2015-01-10 - First commit.

##Column description

   - GC2014 - Last 4 digits indicate year version of PSGC code
   - GC2013 
   - GC2011
   - GC2010
   - GC2009
   - GC2008
   - GC2007
   - GC2006
   - GC2005
   - GC2004
   - GC2003
   - GC2002
   - GC2001c - modified(corrected) version of 2001 PSGC codes
   - GC1995c - modified(corrected) version of 1995 PSGC codes
   - GC1990x - modified version of 1990 PSGC codes, without the regional codes
   - EntityType - R-egion, P-rovince, M-unicipality, C-ity, D-istrict (only applies to City of Manila)
   - EntityClass - Urban or Rural for type B. C-component, I-ndependent, H-ighly-urbanized for EntityType C.
   - Name - are the tidy and simplified version of the names found in the PSGC database, stripped of  old and alternate names. Partial values may be found in name_Alt or name_Old, as applicable.
   - name_Alt - Alternative name
   - name_Old - old name of entity (often found in parenthesis in original data set)
   - capital - values: 1 - National capital, 2 regional capital , 3 provincial capital; multiple values separated by pipes
   - poblacion - The "Poblacion" designation of a barangay entity are often indicated by a  "(Pob.)" suffix, or as part of the barangay name is flagged as "1" in this column. "0" for non-designated barangays.
   - name_GC2014
   - name_GC2000
   - name_GC2001c modified(corrected version) of entity names from 2001


##
Encoding: UTF-8
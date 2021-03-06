========================
Reporting Missing Values
========================

The International Nucleotide Database Collaboration (INSDC) have a standardised missing/null value reporting
language to be used where a value of an expected format for sample metadata reporting **can not** be provided.

The controlled vocabulary takes into account different type of constraints. Submitters are **strongly** encouraged
to always provide true values. However, if missing/null value reporting is required,
submitters are asked to use a term with the finest granularity for their situation. See the table below for
accepted missing value reporting terms.

.. note::
   If your sample metadata does not provide enough context for your data to be easily interpreted, you may
   be requested to update your samples, so it is important to ensure you provide any metadata available and
   only use missing value terms when necessary.

INSDC Missing Value Reporting Terms
===================================

+----------------------------+------------------------------+-----------------------------------------------+
| **INSDC term (top level)** | **INSDC term (lower level)** | **Definition**                                |
+----------------------------+------------------------------+-----------------------------------------------+
| not applicable             |                              | | information is inappropriate to report, can |
|                            |                              | | indicate that the standard itself fails to  |
|                            |                              | | model or represent the information          |
|                            |                              | | appropriately                               |
+----------------------------+------------------------------+-----------------------------------------------+
| missing                    | not collected                | | information of an expected format was not   |
|                            |                              | | given because it has not been collected     |
|                            +------------------------------+-----------------------------------------------+
|                            | not provided                 | | information of an expected format was not   |
|                            |                              | | given, a value may be given at the later    |
|                            |                              | | stage                                       |
|                            +------------------------------+-----------------------------------------------+
|                            | restricted access            | | information exists but can not be released  |
|                            |                              | | openly because of privacy concerns          |
+----------------------------+------------------------------+-----------------------------------------------+

Usage of INSDC Missing Value Reporting Terms
============================================

Please use the above standardised missing value vocabulary **only if a true value of an expected format for a**
**mandatory field is missing**. If a true value is missing for a **recommended** or an **optional** field, then these fields
should not be used for reporting at all. For any use cases, we discourage the usage of the top level term 'missing'
and encourage to use a lower level term with a higher granularity to declare the reason for the absence of a true
value.

Example of usage:

Checklist: `GSC MIxS soil <https://www.ebi.ac.uk/ena/browser/view/ERC000022>`_

geographic location (elevation): not collected

geographic location (country and/or sea): restricted access

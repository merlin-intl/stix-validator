# STIX Document Validator (sdv) BETA
A python tool used to validate STIX v1.0 instance documents. For more information about the
Structured Thread Information eXpression, see http://stix.mitre.org.

## Dependencies
The STIX Document Validator has the following dependencies:
* Python v2.7 http://python.org/download
* lxml >= v3.2.0 http://lxml.de/index.html#download
  * libxml2 >= v2.9.1 http://www.xmlsoft.org/downloads.html

## Use
The STIX Document Validator can validate a STIX v1.0 instance document against STIX v1.0 schemas
found locally or referenced remotely through the schemaLocation attribute.

Validate against local schemas:
`python sdv.py --input-file stix_foo.xml --schema-dir schema`

Validate using schemaLocation:
`python sdv.py --input-file <stix_document.xml> --use-schemaloc`

Validate a directory of STIX documents:
`python sdv.py --input-dir <stix_dir> --schema-dir schema`


## Terms
BY USING THE STIX DOCUMENT VALIDATOR, YOU SIGNIFY YOUR ACCEPTANCE OF THE 
TERMS AND CONDITIONS OF USE.  IF YOU DO NOT AGREE TO THESE TERMS, DO NOT USE 
THE STIX DOCUMENT VALIDATOR.

For more information, please refer to the LICENSE.txt file

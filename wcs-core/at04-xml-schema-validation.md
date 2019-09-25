# XML schema validation

**Purpose**: Test that the XML capabilities document is schema valid.

**Prerequisites**

**Test method**

* Send a GetCapabilities request.

	* Validate response against XML schema located in http://inspire.ec.europa.eu/schemas/inspire_dls/1.0/inspire_dls.xsd

**Reference(s)**

* [INS TG WCS](https://inspire.ec.europa.eu/id/document/tg/download-wcs), Requirement 4

**Test type**: Automated

**Notes**

## Contextual XPath references

The namespace prefixes used as described in [README](http://inspire.ec.europa.eu/id/ats/download-wcs/1.0/wcs-core/README#namespaces).

| Abbreviation                                               |  XPath expression (relative to /wcs:Capabilities) |
| --------------------------------------------------- | -------------------------------------------------------------- |

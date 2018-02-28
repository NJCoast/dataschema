# Metadata templates for storm surge computational model

This directory contains the JSON-LD contexts for NJCoast Storm Surge Computational Model input and output.

catalog.jsonld is contains the metadata template that conforms to the Federal Geographic Data Committee (FDGC) and [Data.gov](https://project-open-data.cio.gov/v1.1/schema/) guidelines.

The following is the Required keys to be conformant with Data.gov guidelines.
Catalog Fields:
- [] Schema Version: "URI that identifies the version of the Project Open Data schema being used"
- [] Dataset: "A container for the array of Dataset objects."
Dataset Fields:
- [] title: "	Human-readable name of the asset. Should be in plain English and include sufficient detail to facilitate search and discovery."
- [] description: "Human-readable description (e.g., an abstract) with sufficient detail to enable a user to quickly understand whether the asset is of interest."
- [] keyword: "Tags (or keywords) help users discover your dataset; please include terms that would be used by technical and non-technical users."
- [] modified: "Last Update	Most recent date on which the dataset was changed, updated or modified."
- [] publisher: "The publishing entity and optionally their parent organization(s)."
- [] contactPoint: "Contact person’s name and email for the asset."
- [] identifier: "A unique identifier for the dataset or API as maintained within an Agency catalog or database."
- [] accessLevel: "The degree to which this dataset could be made publicly-available, regardless of whether it has been made available. Choices: public (Data asset is or could be made publicly available to all without restrictions), restricted public (Data asset is available under certain use restrictions), or non-public (Data asset is not available to members of the public)."
- [] bureauCode: "000:000 for non federal government."
- [] license: "The license or non-license (i.e. Public Domain) status with which the dataset or API has been published"
- [] rights: "This may include information regarding access or restrictions based on privacy, security, or other policies. This should also serve as an explanation for the selected “accessLevel” including instructions for how to access a restricted file, if applicable, or explanation for why a “non-public” or “restricted public” data asset is not “public,” if applicable. Text, 255 characters."
- [] spatial: "The range of spatial applicability of a dataset. Could include a spatial region like a bounding box or a named place."
- [] temporal: "The range of temporal applicability of a dataset (i.e., a start and end date of applicability for the data)."
- [] distribution: "A container for the array of Distribution objects. See Dataset Distribution Fields below for details."
Magento Integrity Service - Hashes Collection
==============================================================================

The Magento Integrity Service is a service we've created in order to help identify potential threats and reduce
the amount of time spend of verifying _of the shelf_ software. It basically is an enourmous and detailed collection
of software. Modules, themes, plugins, source code, anything you might find in a store.
All this software has ben processed into several types of file hashes and combined in a blazing fast database to help verify
the origin of a store's source code. If it's not in our database it is:

1. Custom code / files
2. Temporary / cache files
3. Malware

__Currently Indexed__

Satis packages: 1881
Magento connect packages: 16527
Magento source code (EE/CE): 97

__Purpose of this repo__

This repo only contains the generated hashes, no source code, no code to generate it etc.
It's is meant for safe keeping.

__What's next__

!Elasticsearch
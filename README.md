# InvenTree Demo Dataset

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
![Build](https://github.com/karlorz/demo-dataset/actions/workflows/import_data.yaml/badge.svg)

This repository contains demo data for the InvenTree project.

The demo dataset can be used to populate an InvenTree database for demonstration purposes. It may also be useful if you are developing and/or testing new features for InvenTree.

## Login Details

Multiple default accounts are provided, as detailed below. Each account is afforded a different set of permissions, so users can see the InvenTree roles/permission system in action

| Username | Password | Description |
| --- | --- | --- |
| allaccess | nolimits | View / create / edit all pages and items |
| reader | readonly | Can view all pages but cannot create, edit or delete database records |
| engineer | partsonly | Can manage parts, view stock, but no access to purchase orders or sales orders |
| admin | inventree | Superuser account, access all areas plus administrator actions |


## Contribute

Contributions to the demo dataset are encouraged! A richer dataset provides a better demo experience and helps to showcase the various features available in InvenTree.

To contribute back to the InvenTree demo dataset:

### Import Data

Follow the directions above to create an InvenTree instance using the latest demo dataset

### Git Branch

Create a git branch for the demo-dataset repository

### Edit Data

Create / edit / update the InvenTree database and media files as required

### Export Data

Export the updated data, overwriting the original data file:

```
invoke export-records -f ~/inventree-data/inventree_data.json
```

### Create Pull Request

Create a pull request on the [demo-dataset repository](https://github.com/karlorz/demo-dataset) with the changes you have made.

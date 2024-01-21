# LILA Camera Traps Dataset

## Overview

LILA Camera Traps is an aggregate dataset of images captured by camera traps, automated devices used in ecological research to photograph wild animals. This dataset marks the first effort to consolidate various camera trap datasets into a unified training environment with a single taxonomy.

The broader LILA website includes additional datasets related to biology and conservation, aiming to serve both machine learning (ML) researchers and those leveraging ML for these topics.

## Included Datasets

- Caltech Camera Traps
- ENA24
- Missouri Camera Traps
- North American Camera Trap Images (NACTI)
- WCS Camera Traps
- Wellington Camera Traps
- Island Conservation Camera Traps
- Channel Islands Camera Traps
- Idaho Camera Traps
- Snapshot Serengeti
- Snapshot Karoo
- Snapshot Kgalagadi
- Snapshot Enonkishu
- Snapshot Camdeboo
- Snapshot Mountain Zebra
- Snapshot Kruger
- SWG Camera Traps
- Orinoquia Camera Traps

## Dataset Structure

### Data Instances

- Annotations provided in COCO Camera Traps format
- Common category taxonomy defined on the [LILA website](#link-to-lila-website)

### Data Fields

- `file_name`: the file name
- `width` and `height`: dimensions of the image
- `study`: research study the image is part of
- `location`: name of the location where the image was taken
- `annotations`: information about image annotation (taxonomy, bounding box, etc.)
- `image`: path to download the image and additional information

### Data Splits

No predefined train/test split.

## Dataset Creation

### Curation Rationale

Datasets provided by organizations, projects, and researchers who collected them.

### Annotations

Annotations by domain experts in biology and ecology.

### Personal and Sensitive Information

Some original datasets had a "human" class label; removed for privacy reasons. Contact LILA maintainers for access under an alternative license.

## Using the Data

### Common Names to Taxonomy Mapping

Common names of animals are available in `common_names_to_tax.json`.

### Image Count Information

Image counts for each species across datasets are in `lila_wi_mapping_table.csv`.

## Considerations

### Social Impact

Machine learning benefits from labeled data, particularly in biology and conservation. This dataset facilitates collaboration between biologists, conservation scientists, and ML researchers.

### Biases

These datasets represent local ecosystems and animals, not global diversity.

---

**Note**: For the latest updates and additional resources, refer to the [LILA website](#link-to-lila-website).

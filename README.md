# SFDA Product Categories Reference

This repository contains the latest product category classification system used by the Saudi Food and Drug Authority (SFDA). It aims to provide an easily accessible reference for suppliers, procurement teams, and other stakeholders who need to correctly categorize products according to SFDA guidelines.

## Overview

The SFDA recently updated their product categorization system on their website. This update requires suppliers and procurement personnel to manually update product categories in their systems. This repository serves as a centralized, version-controlled reference to make this process more efficient.

## Repository Contents

- `sfda_categories.csv`: The main data file containing the complete hierarchical structure of SFDA product categories and subcategories


## Data Structure

The main CSV file (`sfda_categories.csv`) contains two columns:
1. **Main Category**: The top-level product category
2. **Subcategory**: The specific subcategory under the main category

The hierarchical structure is represented through blank cells in the "Main Category" column, where consecutive rows with blank main categories belong to the previous non-blank main category.

### Example Structure:

```
Main Category,Subcategory
Cereals & grains products,"Grains & whole grains, flours, wheat, rice, maize, barley, corn, sorghum"
,"Cereal products (breads, pasta, noodles, tortillas, etc.)"
,"Biscuits, cakes, doughs, pastries"
```

In this example, all three subcategories belong to the "Cereals & grains products" main category.

## Usage Guidelines

### For Suppliers

1. Reference this repository to ensure your products are correctly categorized according to the latest SFDA classification
2. Use the exact category and subcategory names as they appear in this repository for compliance
3. Star or watch this repository to receive updates when SFDA categories change

### For Procurement Teams

1. Use this repository as the source of truth for product categorization
2. Reference the specific subcategory when requesting information from suppliers
3. Consider integrating the JSON version of these categories into your procurement systems


## Updating Process

This repository will be maintained to reflect the latest SFDA categorization system (NOT OFFICIAL). Updates will be clearly documented through:


## Contributing

If you notice discrepancies between this repository and the official SFDA website, please:

1. Create an issue describing the discrepancy
2. Submit a pull request with the corrected information, ideally with a reference to the official source

## License

This data is shared under [appropriate license] for public use. Note that the official source of truth is always the SFDA website, and this repository is maintained as a convenience for the community.

## Disclaimer

This repository is maintained as a community resource and is not officially affiliated with or endorsed by the Saudi Food and Drug Authority. Always verify critical regulatory information with the official SFDA website or representatives.

---

Last updated: April 30, 2025 12:01:31 PM

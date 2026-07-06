<p align="center">
  <img src="https://raw.githubusercontent.com/ComputationalPathologyLab/VeSpA/main/src/main/resources/images/vespa_logo.png" width="160" alt="VeSpA logo"/>
</p>

<h1 align="center">ComputationalPathologyLab QuPath Extension Catalog</h1>

<p align="center">
  <em>Custom QuPath catalog distribution for ComputationalPathologyLab extensions, including VeSpA</em>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/QuPath-catalog-1a6e8e?style=flat-square"/>
  <img src="https://img.shields.io/badge/extensions-VeSpA-f2c14e?style=flat-square"/>
  <img src="https://img.shields.io/badge/status-active-3ba07a?style=flat-square"/>
  <a href="https://doi.org/10.64898/2026.06.15.732366"><img src="https://img.shields.io/badge/DOI-10.64898%2F2026.06.15.732366-2f6db3?style=flat-square" alt="DOI"/></a>
</p>

---

This repository provides a custom QuPath extension catalog for extensions maintained by **ComputationalPathologyLab**.

At present, the catalog includes:

- **VeSpA** — a QuPath extension for automatic vessel segmentation and morphometric quantification in whole-slide and region-based histological image analysis.

## Catalog URL

Use the following catalog URL in QuPath:

```text
https://raw.githubusercontent.com/ComputationalPathologyLab/qupath-extension-catalog/main/catalog.json
```

## Available extension

### VeSpA

- Repository: <https://github.com/ComputationalPathologyLab/VeSpA>

VeSpA supports vessel segmentation inside QuPath with annotation-based, TMA-core, and whole-image workflows, along with morphometric measurement import and configurable preprocessing.

## How to add this catalog in QuPath

1. Open **QuPath**.
2. Go to **Extensions → Manage extensions**.
3. Click **Manage extension catalogs**.
4. Add the following catalog URL:

   ```text
   https://raw.githubusercontent.com/ComputationalPathologyLab/qupath-extension-catalog/main/catalog.json
   ```

5. Return to the Extension Manager.
6. Locate **VeSpA** in the catalog list.
7. Choose the version to install and complete the installation.

## How to install VeSpA

Once the catalog has been added, VeSpA should appear in the QuPath Extension Manager under the ComputationalPathologyLab catalog. Select the desired version and install it through the normal QuPath extension workflow.

## Troubleshooting

- **VeSpA does not appear in QuPath**
  - Confirm that the catalog URL is correct.
  - Restart QuPath after adding the catalog.
  - Check that the repository release contains the expected installable JAR asset.

- **Installation fails or no version is available**
  - The catalog entry depends on GitHub Releases hosting the installable JAR.
  - Confirm that the expected release asset is still available if installation fails unexpectedly.

- **QuPath reports a compatibility issue**
  - Confirm the QuPath version meets the extension requirements.

## Adding future extensions

To add another ComputationalPathologyLab extension in the future:

1. Add a new extension entry to `catalog.json`.
2. Point it to a GitHub repository with release-hosted installable JAR assets.
3. Commit and push the updated catalog.

## References

- VeSpA repository: <https://github.com/ComputationalPathologyLab/VeSpA>
- QuPath extension documentation: <https://qupath.readthedocs.io/en/latest/docs/intro/extensions.html>
- QuPath extension catalog model: <https://github.com/qupath/extension-catalog-model>


---

## Citation

If you use **VeSpA** through this QuPath extension catalog, please cite the VeSpA preprint:

**Grion G, Hussain R, Colella FE, Roufail K, Uccella S, Frapolli R, Matteo C, Mintemur O, Pennati F, Renne SL.** *Vessel Spatial Analysis (VeSpA): a tool for whole slide image segmentation, morphometry, and QuPath extension.* bioRxiv. 2026. DOI: [10.64898/2026.06.15.732366](https://doi.org/10.64898/2026.06.15.732366)

Preprint:
- <https://www.biorxiv.org/content/10.64898/2026.06.15.732366v1>

### BibTeX

```bibtex
@article{grion2026vespa,
  title   = {Vessel Spatial Analysis (VeSpA): a tool for whole slide image segmentation, morphometry, and QuPath extension},
  author  = {Grion, Giulia and Hussain, Rash and Colella, Filippo Emanuele and Roufail, Kirollos and Uccella, Silvia and Frapolli, Roberta and Matteo, Cristina and Mintemur, {"O}mer and Pennati, Francesca and Renne, Salvatore Lorenzo},
  journal = {bioRxiv},
  year    = {2026},
  doi     = {10.64898/2026.06.15.732366},
  url     = {https://www.biorxiv.org/content/10.64898/2026.06.15.732366v1}
}
```

### DOI

```text
10.64898/2026.06.15.732366
```

# Log Tools Collection

A collection of `lnav` format files and Elasticsearch Grok parsers designed for parsing logs that I read day to day (especially XCP-NG related ones).

## Project Structure
* `/lnav` - `lnav` configurations
* `/elasticsearch` - Elasticsearch Grok parsers
* `/vendors` - External repositories included as Git submodules to reference projects I use

## Installation & Setup
To clone this repository with all external submodules included:
```bash
git clone --recursive https://github.com/your-username/your-repo-name.git
```

If you have already cloned the repository, you can initialize the submodules at their specific paths using:
```bash
git submodule update --init --recursive
```

---

## Licensing

### Main Project License
The original content, organization, and custom formats provided in this repository are licensed under the **MIT License**. See the `LICENSE` file in the root for full details.

### Third-Party "Vendor" Licensing
This repository includes external projects located in the `vendors/` directory via Git submodules. 
* **Separate Ownership:** These external projects are **not** covered by this repository's MIT license.
* **Individual Licenses:** Each project within the `vendors/` folder maintains its own licensing terms.
* **Compliance:** Users must refer to the specific `LICENSE` or `README` files within each individual submodule directory for the terms governing those specific files.

---

### Contribution
If you have a Grok parser or `lnav` format, feel free to open a PR!

# ENA Checklists to SWATE Template

This project generates SWATE templates from ENA checklists for samples, raw reads, and data analyses.

## Description

The ENA Checklists to SWATE Template project is a web-based tool that allows users to generate SWATE templates based on the checklists provided by the European Nucleotide Archive (ENA). The tool fetches the checklists for samples, raw reads, and data analyses from the ENA server and provides an intuitive interface for users to select the desired checklist and generate a corresponding SWATE template. The SWATE template generation uses ARCtrl.

## Features

- Fetches ENA checklists for samples, raw reads, and data analyses
- Allows users to search and select the desired checklist
- Generates SWATE templates based on the selected checklist and user preferences (mandatory, recommended, optional fields)
- Provides options to download the generated SWATE templates

## Usage

1. Open the web application in a compatible browser.
2. Select the desired checklist (samples, raw reads, or data analyses) from the dropdown or search for a specific checklist.
3. Choose the desired fields to include in the template (mandatory, recommended, optional).
4. Click the corresponding "Download" button to generate and download the SWATE template.

## Installation

1. Clone the repository:
   ```
   git clone https://github.com/xiaoranzhou/ena2swate.git
   ```
2. Open the `index.html` file in a web browser.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

## License

This project is licensed under the GNU General Public License v3.0 (GPL-3.0). See the [LICENSE](LICENSE) file for more information.

```
ENA Checklists to SWATE Template
Copyright (C) [year] [Xiaoran Zhou]

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program. If not, see <https://www.gnu.org/licenses/>.
```

## Acknowledgements

- [ENA (European Nucleotide Archive)](https://www.ebi.ac.uk/ena)
- [SWATE (Excel Add-In for annotation of experimental data and computational workflows.)](https://swate-alpha.nfdi4plants.org/)
- [ARCtrl (Library for management of Annotated Research Contexts (ARCs) using an in-memory representation and runtime-agnostic contract systems.)](https://github.com/nfdi4plants/ARCtrl/)

## Contact



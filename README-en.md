# Garage Cover — Palmeira Azul Condominium

*Leia isto em outros idiomas: [Português](README.md)*

---

Static interactive web page created to present a conceptual study for a continuous garage-cover solution for the parking spaces at Palmeira Azul Condominium in Palmas, Tocantins, Brazil. The project uses a three-dimensional GLB model so the proposal can be visually inspected from different angles.

## Features

- interactive visualization of the published 3D model in `modelo.glb`;
- controls for initial, front, and top views;
- optional automatic model rotation;
- zoom and navigation using a mouse or touch gestures;
- local opening of another `.glb` file without replacing the published model;
- loading messages and error handling in the viewer;
- explicit presentation of the study as conceptual and subject to technical review before any possible implementation;
- CSV and XLSX files containing companies and suppliers identified for quotation inquiries.

## Technologies and main files

- **HTML5, CSS, and JavaScript** in a single main file, `index.html`;
- **`<model-viewer>` 4.0.0**, loaded from a CDN, for 3D rendering and interaction;
- **GLB** for the proposal's three-dimensional model;
- **CSV/XLSX** for the company and supplier survey.

### Repository structure

- `index.html` — main page and viewer logic;
- `modelo.glb` — three-dimensional model loaded by default;
- `Empresas_para_Orcamento_Cobertura_Garagens.csv` — company survey in CSV format;
- `Empresas_para_Orcamento_Cobertura_Garagens.xlsx` — spreadsheet version of the same survey.

## Usage

Open `index.html` in a browser with internet access so that the `model-viewer` library can be loaded from the CDN. The `modelo.glb` file must remain in the same directory as the page to be loaded automatically.

After loading, the model can be dragged to rotate it, while the mouse wheel or touch gestures can be used to zoom in and out. Preset views are also available. The **Open another model** control allows a GLB file from the user's device to be viewed temporarily. That file remains only in the browser and does not modify the content published in the repository.

## Limitations and study scope

The content presented is a **conceptual study**. The model dimensions are provisional, and the final solution depends on checking the architectural drawings, preparing a technical design, evaluating costs, and obtaining any applicable approvals. The repository does not document structural validation, construction-level engineering design, or technical approval of the proposed solution.

## 👤 Authorship and development

Interactive 3D visualization web page independently developed by **Pablo Phillipe Cândido dos Santos** to support the presentation and discussion of a conceptual garage-cover proposal for Palmeira Azul Condominium, including navigation through different model views and complementary consultation of a survey of potential suppliers.

Generative artificial intelligence tools were used as auxiliary resources during development, while responsibility for the project's conception, implementation, integration, and verification remained with the author.

Lattes CV: [http://lattes.cnpq.br/9500873674712528](http://lattes.cnpq.br/9500873674712528)

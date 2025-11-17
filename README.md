```markdown
# 🌞 SUNCAST GitHub Pages Website

This repository hosts the source code for the **SUNCAST community website**, available at:

👉 https://suncast-org.github.io/

The site is built using **MkDocs** with the **Material for MkDocs** theme. It provides:

- Community governance documentation  
- Contribution guidelines  
- Maintainer responsibilities  
- Code of Conduct  
- A growing overview of SUNCAST projects and workflows  
- Links to core software packages  

---

## 🧱 Repository Structure

suncast-org.github.io/
│
├── mkdocs.yml # Site configuration
├── docs/ # All website pages
│ ├── index.md
│ ├── governance.md
│ ├── contributing.md
│ ├── maintainers.md
│ ├── code_of_conduct.md
│ └── projects.md
└── LICENSE # CC-BY-4.0 license for documentation

## 🚀 Building the site locally

To preview or modify the site, install the required packages:

```bash
pip install mkdocs-material
````

Then build and serve the site locally:

```bash
mkdocs serve
```

This launches a local development server (usually [http://127.0.0.1:8000](http://127.0.0.1:8000)).

---

## 📤 Deploying the site

To deploy updates to GitHub Pages:

```bash
mkdocs gh-deploy
```

MkDocs will automatically build the static site and push it to the `gh-pages` branch used by GitHub Pages.

---

## 🤝 Contributing

Website content is located in the `docs/` directory.
Please refer to:

* [Governance Model](docs/governance.md)
* [Contributing Guide](docs/contributing.md)
* [Maintainers Policy](docs/maintainers.md)
* [Code of Conduct](docs/code_of_conduct.md)

for guidelines on participating in the SUNCAST community.

---

## 📄 License

All website text and documentation are released under the **CC-BY-4.0** license.

```

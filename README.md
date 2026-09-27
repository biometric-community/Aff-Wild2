# Aff-Wild2

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-green?logo=creativecommons&logoColor=white)](https://creativecommons.org/licenses/by/4.0/)
[![GitHub](https://img.shields.io/badge/GitHub-biometric--community%2FAff--Wild2-181717?logo=github)](https://github.com/biometric-community/Aff-Wild2)
[![Access: register](https://img.shields.io/badge/access-register-important.svg)](https://ibug.doc.ic.ac.uk/resources/aff-wild2/)

**Aff-Wild2** — tbiom catalog packaging for `aff-wild2` (expression; access `register`). Docs/helpers only; obtain data via upstream registration.

- **Dataset repository**: https://github.com/biometric-community/Aff-Wild2
- **Upstream source**: https://ibug.doc.ic.ac.uk/resources/aff-wild2/
- **License (helpers / docs)**: CC BY 4.0 (see [`LICENSE`](LICENSE))
- **License (data)**: upstream terms — this packaging does **not** relicense or redistribute gated data

| Field | Value |
|-------|-------|
| Catalog id (tbiom) | `aff-wild2` |
| Category | `expression` |
| Access | `register` |
| Upstream homepage | https://ibug.doc.ic.ac.uk/resources/aff-wild2/ |

## TL;DR

- **Access**: **register** — obtain data from the upstream homepage / license process
- **This mirror**: documentation + download helpers only (no bulk payload in git)
- **Notes**: Aff-Wild2 ABAW challenge data.

## Download

### Clone this repository

```bash
git clone git@github.com:biometric-community/Aff-Wild2.git
cd Aff-Wild2
```

### tbiom monorepo helper

```bash
bash projects/datasets/scripts/download_aff_wild2.sh
```

Place licensed archives under `projects/datasets/aff-wild2/` (gitignored).

## Dataset structure

```text
Aff-Wild2/
├── README.md
├── LICENSE
├── .gitignore
└── extracted/   # local only after you obtain upstream data
```

## License

Helpers/docs: CC BY 4.0. Dataset files: upstream license / registration agreement.

## Contact

- Upstream: https://ibug.doc.ic.ac.uk/resources/aff-wild2/
- Packaging: https://github.com/biometric-community/Aff-Wild2/issues

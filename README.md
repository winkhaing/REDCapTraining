# REDCap for Researchers: From First Project to Confident Practitioner

A self-paced, bilingual (English and Burmese) course of 20 modules on REDCap, from first project to confident practice. Each module has explained concepts, a step-by-step walkthrough, three exercises with answer keys, a quiz, downloadable data dictionary samples and career guidance. All data in the course are synthetic.

## Audience

Clinicians, nurses, public health staff, students, research coordinators and postdocs. Experience ranges from none to intermediate with electronic data capture. Learners do not need a live REDCap project: every exercise has a Track A (live REDCap practice project) and a Track B (no access).

## How to use

Read the modules on GitHub, or import each module `.md` file into Notion (Import, then Text & Markdown) and attach its CSV files to the page. Work through the modules in order.

## Module index

| No. | Module | Level | Time | Status |
|-----|--------|-------|------|--------|
| 1 | [EDC concepts, REDCap ecosystem, data management lifecycle](modules/01_edc_redcap_lifecycle/Module_01_edc_redcap_lifecycle.md) | Beginner | 45 to 60 min | Published |
| 2 | [Planning before building](modules/02_planning_before_building/Module_02_planning_before_building.md) | Beginner | 45 to 60 min | Published |
| 3 | Creating a project, Online Designer, instruments and field types | Beginner | 45 to 60 min | Planned |
| 4 | Field validation, branching logic, calculated fields | Beginner to Intermediate | 45 to 60 min | Planned |
| 5 | Piping, Smart Variables, action tags, field embedding | Intermediate | 45 to 60 min | Planned |
| 6 | Data dictionary workflow, Project XML, Shared Library, templates, version control | Intermediate | 45 to 60 min | Planned |
| 7 | Data entry, record status, data quality | Intermediate | 45 to 60 min | Planned |
| 8 | Longitudinal projects | Intermediate | 45 to 60 min | Planned |
| 9 | Repeating instruments and repeating events | Intermediate | 45 to 60 min | Planned |
| 10 | Surveys | Intermediate | 45 to 60 min | Planned |
| 11 | Alerts, notifications, automated survey invitations, data entry triggers | Intermediate | 45 to 60 min | Planned |
| 12 | Randomisation module and trial design | Intermediate | 45 to 60 min | Planned |
| 13 | MyCap | Intermediate | 45 to 60 min | Planned |
| 14 | Multi-Language Management and External Modules | Intermediate | 45 to 60 min | Planned |
| 15 | Clinical Data Interoperability Services (CDIS) | Intermediate to Advanced | 45 to 60 min | Planned |
| 16 | User rights, roles, Data Access Groups, multi-site set-up | Intermediate | 45 to 60 min | Planned |
| 17 | Compliance, security and change control | Intermediate | 45 to 60 min | Planned |
| 18 | Reports, dashboards, data export and import | Intermediate | 45 to 60 min | Planned |
| 19 | API, tokens, R and Python integration | Intermediate to Advanced | 45 to 60 min | Planned |
| 20 | Capstone, SOPs and career portfolio | All levels | 45 to 60 min | Planned |

## Repository structure

```text
REDCapTraining/
├── README.md
├── index.md
├── LICENSE
├── .gitignore
├── .gitattributes
├── _config.yml
└── modules/
    ├── 01_edc_redcap_lifecycle/
    │   ├── Module_01_edc_redcap_lifecycle.md
    │   ├── data/
    │   │   ├── M01_fever_cohort_baseline.csv
    │   │   └── M01_hhkap_consent_demo.csv
    │   └── images/
    │       ├── M01_fig01_my_projects.png
    │       ├── M01_fig02_project_home.png
    │       └── M01_fig03_project_setup.png
    └── 02_planning_before_building/
        ├── Module_02_planning_before_building.md
        ├── data/
        │   ├── M02_fever_cohort_planned.csv
        │   └── M02_htn_app_draft_flawed.csv
        └── images/
            ├── M02_fig01_data_dictionary_upload.png
            └── M02_fig02_designer_variable_names.png
```

Each module folder holds the module file, a `data/` folder when the module has CSV files, an `images/` folder when it has figures, and a `scripts/` folder when it has runnable code.

## Licence

Course content: Creative Commons Attribution 4.0 International (CC BY 4.0), https://creativecommons.org/licenses/by/4.0/

Code snippets and scripts: MIT Licence, https://opensource.org/license/mit

See `LICENSE` for details.

## Citing REDCap

If you report a study that used REDCap, please cite:

- Harris PA, et al. J Biomed Inform 2009;42(2):377-381.
- Harris PA, et al. J Biomed Inform 2019;95:103208.

## Author

Win Khaing

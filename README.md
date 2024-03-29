# EHR group template for Stata

## Purpose

A template to begin a project with Stata. [Click here](https://github.com/ehr-lshtm/template-stata/generate) to use this template, then replace this text with a desription of your project.

## Untracked files
Repositories should only contain non-disclosive files, that is, code without file paths, and summary statistics. This template is set up so only files that are safe to upload to Github, such as code, are uploaded by default. This means all files ending in `.csv`, all Stata output, and all files in the `data/` and `paths/` folders (except README) are untracked, i.e. they will not be uploaded to GitHub. Edit the `.gitignore` file to ignore or allow (with `!`) specific files or file types. 

## File tree
We recommend that you use this file structure as the `.gitignore` is set up to ignore specific folders. You can add subfolders as needed, for example for different types of outputs (logs, images, tables), or remove folders that are not used. 


```
template-stata/
├── codelists/
│   ├── README.md
│   ├── codelist_1.csv
│   └── codelist_1_metadata.txt
├── data/
│   ├── README.md
│   ├── cleaned_data_1.csv (untracked)
│   └── cleaned_data_2.csv (untracked)
├── docs/
│   ├── README.md
│   ├── document1.docx
│   ├── document1.html
│   └── document1.Rmd
├── paths/
│   ├── README.md
│   └── paths.do (untracked)
├── results/
│   ├── README.md
│   └── result_1.csv
├── do-files/
│   ├── README.md
│   ├── script1.do
│   └── script2.do
├── logs/
│   ├── README.md
│   ├── log1.log
│   └── log2.log
└── README.md
```

## Publishing the repository
Once you are ready to make the contents of this repository public:
1. Create a new repository, e.g. "study_name_public"
2. Copy the contents of this private repository to the new repository (make sure to copy the .gitignore file, but do not copy the hidden .git folder; what is hidden may vary by operating system)
3. Before publishing the new repository make sure it doesn't contain:
	* any raw data
	* any derrived data (e.g. cleaned intermediate data)
	* any disclosive results
	* any file paths to locations on secure network drives
4. Commit the changes and publish the new repository (e.g. in Github Desktop first "Commit to main", then "Publish repository" and untick "Keep this code private"
5. See [this guide](https://docs.github.com/en/repositories/archiving-a-github-repository/referencing-and-citing-content) on issuing a DOI and making your new public repository citable 

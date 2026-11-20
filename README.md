Code for processing the data.

The structure is as follows:
- Clone the repository onto your local device/nimoy
- Create a directory named data/ inside the repo
- Place your data in this data/ directory. I am not tracking it with Git, since Git has a file size limit, and is not meant to be used for data.
- After you have your data in there, follow this format:
```
$ tree -d
.
└── data
    ├── reduced
    ├── slash
    │   ├── 02nov26
    │   │   ├── nov02_26
    │   │   │   └── raw
    │   │   └── nov02_26_w
    │   ├── 03nov26
    │   │   ├── nov03_26
    │   │   │   └── raw
    │   │   └── nov03_26_w
    │   ├── 16oct26
    │   │   ├── oct16_2026
    │   │   │   └── raw
    │   │   └── oct16_2026_w
    │   ├── rflat3
    │   └── SN.raw
    └── text_files
```

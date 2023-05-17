# img2prompt

### Directory structure
img2prompt/
├── data
│   ├── data-card.json
│   └── working
│       ├── test.csv
│       └── update_diffusiondb.csv
├── models
│   ├── approach_one
│   │   ├── resnet152
│   │   │   ├── modified_resnet152.ipynb
│   │   │   └── resnet152_updated.pth
│   │   └── vit
│   │       ├── modified_ViT.ipynb
│   │       └── vit_base_patch16_224.pth
│   └── approach_two
│       ├── blip
│       │   └── blip_eval.ipynb
│       ├── clip_interrogator
│       │   └── clipinterrogator_eval.ipynb
│       └── git
│           └── git_eval.ipynb
└── requirements.txt

`data/` - all the data needed for running our models
`models/` - code for the models defined in the report with their weights

### Steps to run the notebooks
0. Please download all the data mentioned in `data/data-card.json` into the `data/` folder with the same sub-folder names as the last part of their URL. For eg., data from "https://kaggle.com/data/abc123" should be stored in the folder `abc123/`.
1. `pip install -r requirements.txt`
2. Each model can be run from its notebook.

## Acknowledgement
We sincerely thank Prof. Hegde, and the course assistants for providing us the opportunity to work on this project.
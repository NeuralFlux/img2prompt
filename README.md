# img2prompt

### Directory structure
img2prompt/ <br>
├── data <br>
│   ├── data-card.json  <br>
│   └── working  <br>
│       ├── test.csv  <br>
│       └── update_diffusiondb.csv  <br>
├── models <br>
│   ├── approach_one <br>
│   │   ├── resnet152 <br>
│   │   │   ├── modified_resnet152.ipynb <br>
│   │   │   └── resnet152_updated.pth <br>
│   │   └── vit <br>
│   │       ├── modified_ViT.ipynb <br>
│   │       └── vit_base_patch16_224.pth <br>
│   └── approach_two <br>
│       ├── blip <br>
│       │   └── blip_eval.ipynb <br>
│       ├── clip_interrogator <br>
│       │   └── clipinterrogator_eval.ipynb <br>
│       └── git <br>
│           └── git_eval.ipynb <br>
└── requirements.txt <br>

`data/` - all the data needed for running our models
`models/` - code for the models defined in the report with their weights

### Steps to run the notebooks
0. Please download all the data mentioned in `data/data-card.json` into the `data/` folder with the same sub-folder names as the last part of their URL. For eg., data from "https://kaggle.com/data/abc123" should be stored in the folder `abc123/`.
1. `pip install -r requirements.txt`
2. Each model can be run from its notebook.

## Acknowledgement
We sincerely thank Prof. Hegde, and the course assistants for providing us the opportunity to work on this project.

# :beginner: Product Engineer Test
This README is the document which will explain the Code Challenge for the Scientist position.


## **Structure of the Project:**

### :raising_hand: **Name** 
Soybean Crop Vizzuality test

### :baby: **Status**
This is the first release of the project. In future times it will be modified and changed as needs from the developers and the customer needs.

### :computer: **Technology stack**
In this case, the technologies used are based on Python.

- :bar_chart: The libraries included are the ones needed for spatial analysis: Geopandas, Pandas and Numpy, Matplotlib

## :nut_and_bolt: **Deployment**
### :key: Prerequisites
1. To have installed `conda`
2. To have installed `git`

### :one: Installation instructions
The installation process is the next:

1. Download this repository
2. Execute the next code in a conda prompt
    ```sh
    $ cd vizz_science
    $ conda create -f environment.yml
    $ conda activate vizzuality
    $ ipython kernel install --user --name=<name_for_kernel>
    $ jupyter notebook
```
Notes:
- Due to memory github problem with csv, the data must be unrared after downloading code
- the route should be 'data/HarvestedArea_spam2010'

### :file_folder: **Folder structure**
```
└── vizz_science
    ├── .gitignore
    ├── requirements.txt
    ├── environment.yml
    ├── README.md
    └── data
        ├── areas.geojson
        ├── HarvestedArea_spam2010 
            ├── spam2010V2r0_global_H_TA.csv
            ├── spam2010V2r0_global_H_TR.csv
            ├── spam2010V2r0_global_H_TH.csv
            ├── spam2010V2r0_global_H_TL.csv
            ├── spam2010V2r0_global_H_TS.csv
            ├── spam2010V2r0_global_H_TI.csv            
```
### :love_letter: **Contact info**
This project was developed by Irene Aguerri.

https://linkedin.com/in/ireneaguerri

If you have any doubts or comments, please refer to my email

:inbox_tray: ireneaguerri@gmail.com

---

# Progress of the Philippines' Sustainable Development Goals (SDGs): An Open-Source Dataset
In 2015, the United Nations General Assembly created 17 interlinked global goals that were intended to be achieved by 2030. It was said that it would pave the way to "a better and more sustainable future for all". The interlinked global goals were named the Sustainable Development Goals (SDG).

These goals were embraced by all member states of the United Nations, which includes the Philippines, as they believe that these goals would bring prosperity not only to their citizens but to the whole planet. The creation of these goals recognizes that to end poverty, other problems must also be addressed. These problems include improving the health and education system and reducing all forms of inequalities. 

In this notebook, **27** different datasets from the **Philippine Statistics Authority**, the government agency assigned to update the Philippine's data on this goals, would be combined. Fifteen (15) of these datasets are directly about the SDG, while others are indirectly connected to the SDGs.

## Importance of the Dataset
As this dataset compiles, cleans and pre-process all of the available regional datasets related to the SDG of the Philippines, this dataset can help in determining if there are relationships between the different indicators. Additionally, it provides an easier way to access and to explore information and data on the Sustainable Development Goals of the Philippines. Exploring the given dataset can help in determining which SDGs each region needs to focus on. Most importantly, this could assist the national government in determining where to direct its relief efforts or if they are prioritizing what needs to be prioritized based on the nation's current situation. This will serve as a guide for the national government and local government units (LGUs) in ensuring that each region of the country progresses over time. In addition, exploring the datasets in the Philippines can help in assessing how progressive its data collection is.

## Scope of the Dataset
The open-source dataset—the Progress of the Sustainable Development Goals (SDGs) of the Philippines—was a result of scouring the official open data platform of the Philippine Statistics Authority (PSA), the OpenSTAT.

Due to the goal of this dataset, the type of datasets that were searched for was datasets regarding SDGs that were divided per region per year. However, as OpenSTAT only contains data for the Philippines as a whole (for datasets that are for the targets of the SDGs) two divisions of the PSA have been contacted: the Knowledge Management and Communications Division and the SDG division. 

This implies that if the PSA did not collect or release the target for a specific SDG per region, this dataset cannot include these as there are no official data.
Through this, fourteen SDG datasets, which correspond to one indicator each, were received and collated. Although the SDG was only formally established in 2015, some of the datasets started as far back as 2001. 

The SDG datasets that were retrieved from the PSA are based on the SDG Database as of **April 22, 2022**. As for the non-SDG datasets, it was retrieved from the PSA last **May 19, 2022** and some were updated last **June 18, 2022** upon checking recent enhancements. 

Thus, these datasets only include data for the **regions of the Philippines** and **Philippines** as a whole. The years differ for some of the columns, but the total range is from **2000 to 2021**.

## Data Dictionary
The Data Dictionary or the Codebook of this dataset can be accessed through this [link](https://drive.google.com/file/d/1pY9zVrpjaDBiMtpuLTfnfFpRkH9BTreB/view?usp=sharing). 

This contains the **data collection methodology** and the **coding rules** for this open-source dataset. This includes a description of each variable used in this dataset as well as a brief explanation of how each source dataset was pre-processed. In addition, the Sustainable Development Goals are briefly discussed in this document.

## How to set up and run the project locally through JupyterNotebook or JupyterLab
1. Extract the folder from the zipped file that you can download through this DownGit [link](https://minhaskamal.github.io/DownGit/#/home?url=https://github.com/francheska-vicente/datapre-project).
2. Launch `Jupyter notebook` or `JupyterLab`.
3. Navigate to the project folder containing N01-Group1.ipynb.
4. Open `N01-Group1.ipynb`. This contains the **data pre-processing** and **cleaning**.
5. On the **Kernel** Tab, click on **Restart & Run All**.
6. After using this notebook, open `N01-Group1-EDA.ipynb`. This contains the **Exploratory Data Analysis**.

## Downloading the Open-source Dataset
The open-source dataset, which is composed of **12 different files** corresponding to the SDGs and combined datasets, can be downloaded through this [Google Drive link](https://drive.google.com/file/d/17x4BKqTD7vx8-MIPC_KnQF81ImN_FkwX/view?usp=sharing).

The open-source dataset (`data_output`) includes the following:
- `combined_data.csv` combination of all datasets (SDG and non-SDG datasets)
- `supplementary_datasets.csv` combination of all non-SDG datasets
- Combined Datasets Per SDG
  - `sdg_1.csv`
  - `sdg_3.csv`
  - `sdg_4.csv`
  - `sdg_7.csv`
  - `sdg_8.csv`
  - `sdg_10.csv`
  - `sdg_11.csv`
  - `sdg_13.csv`
  - `sdg_14.csv`
  - `sdg_16.csv`

**Note**: Not all SDGs have their own dataset file because the data sources available are limited.

## Authors
- **Cerilla, Vincent Carlo L.** <br/>
vincent_cerilla@dlsu.edu.ph
- **Marcelo, Andrea Jean C.**  <br/>
andrea_marcelo@dlsu.edu.ph
- **Vicente, Francheska Josefa**  <br/>
francheska_vicente@dlsu.edu.ph

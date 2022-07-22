# NML_Project
This is our submission for the final project of the Network Machine Learning at EPFL 2022. You can visit our github repository [here](https://github.com/Potamitisn/NML_Project) and our google drive [here](https://drive.google.com/drive/folders/1kD9TzG5XSjifvF5h2nIBNbqlyobuExj2).

## Table of Contents
1. [Instructions](#Instructions)
2. [Repo organization](#Repo_organization)
3. [Interactive graphs](#graphs)
4. [Authors](#Authors)


## Instructions <a name="Instructions"></a>
The proposed method to run the code of our project is using google colab.The reason is that free gpu is provided which we can use in the later part of this report to speed up our GNN learning process. There are the steps you need to follow in order to reproduce our results : 
1. Upload `network_machine_learning_project.ipynb` on the colab as a notebook.
2. Upload the `project` folder on your google drive. 
3. All that is left to do is to adjust the path (where you saved the `project`) on the notebook so it can access its contents. More specific instructions in the notebook itself (just 1 change in 1 line of code).



## Repo Organization <a name="Repo_organization"></a>
```
|   README.md
|   network_machine_learning_project.ipynb.zip
|   NML_Report.pdf
|
+---Networks
      DC_2000
      DC_2001
      Marvel_2000
      Marvel_2001
|
|
+---project
    |   network_machine_learning_project.ipynb
    |
    +---data
          dc_2000-2001.parquet
          dc_2001-2002.parquet
          marvel_2000-2001.parquet
          marvel_2001-2002.parquet
    |
    +---features
    +---gexf_files
    +---graphs
    +---images

```

- `network_machine_learning_project.ipynb.zip`: A zipped version of our notebook where the outputs are still there. However, due to the size of the images we had to zip it to reduce its size. You can also find the same notebook (not zipped) in our google drive too. 
- `network_machine_learning_project.ipynb`: Notebook containing the whole coding process of the project. The outputs have been cleared due to the size of the images.
- `Networks`: Folder containing 4 subfolders. Each of these subfolders corresponds to a .js template/interactive graph for each dataset. They are just there so we can host our interactive graph plots on github pages.
- `project`: Folder to be downloaded along the notebook.
- `data`: Folder containing the provided data for the project. Due to privacy reasons we haven't uploaded the actual parquet files.
- `features`: Folder where we stored the features used for the classification part (just in case the user prefers to load them directly to save time).
- `gexf_files`: Folder contatining all the gexf files corresponding for each graph that we created along the project. 
- `graphs`: Folder containing the adjacency matrices for needed graphs (just in case the user prefers to load them directly to save time).
- `images`: Folder containing the static images of the visualized graphs.

## Interactive Graphs <a name="graphs"></a>
- [Marvel 2000](https://potamitisn.github.io/NML_Project/Networks/Marvel_2000/)
- [Marvel 2001](https://potamitisn.github.io/NML_Project/Networks/Marvel_2001/)
- [DC 2000](https://potamitisn.github.io/NML_Project/Networks/DC_2000/)
- [DC 2001](https://potamitisn.github.io/NML_Project/Networks/DC_2001/)

## Authors <a name="Authors"></a>
- Bohan Wang
- Nearchos Potamitis


### Vesicle Segmentation

Objectives:
 - Segment vesicles in axon by implementing Mask RCNN neural net. 
 - Classify vesicles as inhibitoy, excitatory

The repository includes:

Source code of Mask R-CNN built on FPN and ResNet101.

Training code for vesicle segmentation

Jupyter notebooks to visualize the detection pipeline at every step

Evaluation on MS COCO metrics (AP)


### Data
 - 

### Environment

1. Navigate to the `MRCNN` folder with the `setup.py` file.
2. Create the conda environment with the main dependencies.
```bash
conda create -n 
conda activate 
conda install python=3.8
pip install tensorflow scikit-learn jupyterlab
pip install seaborn pandas 

```
3. Install the development version of this repository
```bash
pip install.
```

4. Install the `MRCNN` repository.  
```bash
# can do this within any directory on local machine
git clone https://github.com/AllenInstitute/..
cd MRCNN
pip install.
```


### Additional repositories

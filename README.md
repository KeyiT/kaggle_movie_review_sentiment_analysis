# kaggle_future_sales

## Setup package
1. Setup a new python virtual environment:
```bash
conda create --name <env_name> python=3.6
source activate <env_name>
```
2. Under the root folder
```bash
pip install -r requirements
```
3. create data folder and download data
```bash
mkdir input/<competition_name>
cd input/<competition_name>
kaggle competitions download -c <competition_name>
cd ../../
```
4. create a folder for source code
```bash
mkdir src
```

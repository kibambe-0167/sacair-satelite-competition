# sacair-satelite-competition
SACAIR 2023 Satellite Image Classification Competition



## Data files flow
- data
   - data
      - cloudy
      - desert
      - water
      - green_area
   - sacair_data



## how to run code
- make sure you have python programming language isntalled on the machine
- if you're using python3.4 or later pip is install by default
- if you prefer to use docker or conda, to run the code, please check the links provided
- conda: https://conda.io/projects/conda/en/latest/user-guide/getting-started.html
- docker: https://www.docker.com/get-started/ 
- but if you prefer pip and **virtualenv**, please follow the points below
- install virtualenv on your machine: pip install virtualenv
- create a virtual env in the root folder
- macbook / linux: python3 -m virtualenv env
- windows : python -m virtualenv env
- activate the environment
- macbook / linux: source env/bin/activate
- windows: .\env\Script\activate
- install packages / libraries in the requirments.txt file in the created env: pip install -r requirements.txt
- make sure to pick the right env in the notebook
- make sure the files/images are place in the right folder


## files to run
- when the data files are places as described above. the CSV files will match images locations from the file
- in the convnet.ipynb
- select the right env
- run all to test the codes
- 
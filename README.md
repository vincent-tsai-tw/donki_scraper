# donki_scraper
Donki products scraper
This scraper would scrape the Donki products list by each category.

Please follow the below step to run this script.
<br/>

## Clone this repository ##
clone this repository by `git clone git@github.com:vincent-tsai-tw/donki_scraper.git` <br/>
<br/>

## Install requirements.txt <br/>
You can run create a virtual environment to run this script to make sure you have a clean environment. <br/>
Create a new virtualenv with virtual environment name: `virtualenv venv` <br/>
Activate new virtualenv: `source venv/bin/activate`<br/>
Install packages from requirements.txt: `pip3 install -r requirements.txt`<br/>

## Open the jupyter notebook
start the jupyter notebook:`jupyter notebook`

<img width="572" alt="image" src="https://user-images.githubusercontent.com/67896676/171989796-1d0bebe6-8494-40b7-9858-44775e22a028.png">


Click the **scraper.ipynb** to start the notebook.

Before you run the script, please open this [link](https://mpglobal.donki.com/ec-web/d/pcd?titleStr=5YyW5aaG5ZOB&gpId=gm-0004?lan=zh-tw)
You can choose which main category you would like to get the products list and copy the category name to the **scraper.ipynb** as an input for the `pre_run` category inputs.

<img width="999" alt="image" src="https://user-images.githubusercontent.com/67896676/171989854-0899e84b-b8b1-4849-92e0-a0379eb16c0d.png">

<img width="555" alt="image" src="https://user-images.githubusercontent.com/67896676/171989986-71d156ca-2f4e-4b47-9ede-127d181fee9e.png">

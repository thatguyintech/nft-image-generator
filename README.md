

## About
Python Notebook in Jupyter that will generate a series of unique images using a collection of layers.

## Getting Started
1. Install [Python](https://www.python.org/downloads/)

2. Install PIP
Download PIP get-pip.py
```
curl https://bootstrap.pypa.io/get-pip.py -o get-pip.py

python get-pip.py
```

3. Install Python Pillow
```
pip install pillow
```

4. Install Python display
```
pip install display
```

5. Install Jupyter Notebook
```
pip install jupyter 
```

6. Run Jupyter in your nft-image-generator folder
```
jupyter notebook
```

7. Run the commands in [generate.ipynb] to generate images.

8. First time you run notebook, it will ask you to install ipykernel, accept this.
 
9. If the program executes successfully, it will output all the generated images to the /images folder, and the metadata to the /metadata folder. The filenames will refer to tokenIds. 

10. The program uses trait layers from the attributes folder to generate your image. The attributes folder should contain sub-folders with each of the traits, prefixed with the number of the layer order it is in, with "1" as the lowest layer and incrementing upwards for higher layers. The folder organization should match the attribute dictionary initialized at the top of the notebook file.

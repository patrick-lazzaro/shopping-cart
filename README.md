# Shopping Cart

## PREREQUISITES

Anaconda 3.7+

Python 3.7+

Pip

## INSTALLATION

Fork this remote repository under your own control, then download your remote copy onto your local computer. 

Then navigate there from the command line:

```
cd ~/Desktop/shopping-cart
```

Use Anaconda to create and activate a virtual envirnoment, perhaps called "shopping-env":

```
conda create -n shopping-env python = 3.8
conda activate shopping-env
```

From inside the virtual envirnoment, install package dependencies:

```
pip install -r requirements.txt
```

## SETUP

In the root directory of your local repository, create a new file called ".env", and update the contents of the ".env" file to specify your desired tax rate:

```
TAX_RATE = 0.0875
```

## USAGE 

Run the game script:

```
python shopping_cart.py
```

Enter the product identifiers, then type 'Done' when finished.

Enjoy your receipt!
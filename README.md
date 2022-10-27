# Single Cell Analysis on Saturn Cloud

## Requirements

* A saturn cloud account. 
    * The free account is fine for this example.
* Optionally, instead of Saturn Cloud you can use any computer with conda/mamba and internet connectivity.
* Optional - S3 Bucket with Read/Write access.

That's it!

## Setup - Saturn Cloud

The Saturn Cloud UI is fairly self explanatory. 

* Create a new Python Server resource type.
![Python Server](./images/Screen Shot 2022-10-27 at 1.47.08 PM.png)
* Choose a CPU Instance Type
 ![CPU Example](./images/Screen Shot 2022-10-27 at 1.37.26 PM.png)
   (We're not doing anything here that requires a GPU.)
* Choose your memory requirements
  * From the Size dropdown choose an instance type.


## Setup - Local

## Data Analysis

You can grab the [scanpy tutorials](https://github.com/scverse/scanpy-tutorials) with:

```bash
git clone https://github.com/scverse/scanpy-tutorials
```

I'm only going over the `pbmc3k.ipynb` notebook. It's supplied here because I made one very minor change, but all accolodes should go to the ScanPy team.

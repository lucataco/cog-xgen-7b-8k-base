# Salesforce/xgen-7b-8k-base Cog model

This is an implementation of the [Salesforce/xgen-7b-8k-base](https://huggingface.co/Salesforce/xgen-7b-8k-base) as a Cog model. [Cog packages machine learning models as standard containers.](https://github.com/replicate/cog)

First, download the pre-trained weights:

    cog run script/download-weights

Then, you can run predictions:

    cog predict -i prompt="The world is"

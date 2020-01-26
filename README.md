# noHateErrorClasses

## instalation

Run 'bash install.sh' for windows or 'bash install_pip3.sh' for macOS
In these files are all libraries listed needed for running the jupyter notebook

## Use different testdata

1. Put your testset as a csv file inside the data folder
2. change the testset variable inside the config file
3. change the model url inside the configs if needed
4. change the prediction_file name inside the configs if you do not want to override the old prediction file
5. Run the predict.ipynb this could take a while

Now you can use the generated json file to search error classes

## Search error classes

Inside the error_classes folder all examples
We put clearer comments inside the 'spellchecker' file
There are a bunch of of functions needed for this process
you can find them inside the lib folder
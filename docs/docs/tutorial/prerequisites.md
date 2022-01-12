Before we begin, there are a few things that we need to ensure.


## Clone the GitHub repository
We need these to be available locally for the user to edit. The project repository is available [here](https://github.com/kedar-ketos/lead-service-line-map).

You can either use `git clone` command line functionality or download all files from the repository as a compressed folder.

After downloading or cloning these files, this is how the directory structure should look like-

    - lead-service-line-map
      - Assets
      - Data
      - docs
      - LICENSE
      - README.md
      - Lead Service Line Map.pbix

We will discuss these dependencies in greater detail in the ['get and transform data' section](get_data.md).



## Power BI
This tool uses [Microsoft Power BI](https://powerbi.microsoft.com/) for mapping and data visualization. Power BI can be installed from [here](https://aka.ms/pbisingleinstaller).

Microsoft has some great free tutorials on Power BI and it's a very widely used tool. However, its major drawback is its incompatibility with Mac OS devices. We recommend users to use a Windows virtual machine to replicate these steps if they don't have access to a Windows machine locally.

If you want to publish a report to the cloud, then you will also need a basic Power BI license. You can find more information about this in Power BI's documentation. Note that you do not need any licenses for this tutorial.


## GeoJSON editor
Data cleaning is a part of this tutorial. To follow this, we'll need access to a GeoJSON editor. Most programming languages make it very easy to modify GeoJSON files (for example, the [GeoPandas library for Python](https://geopandas.or)), but users may also choose to do this using free web tools like [geojson.io](https://geojson.io).


## Spreadsheet tool
We will need access to a spreadsheet tool that's able to edit comma-separated (CSV) files. For example, Microsoft Excel.
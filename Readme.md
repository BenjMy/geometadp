[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/agrogeophy/geometadp.git/HEAD?urlpath=voila%2Frender%2FMetadataManager.ipynb)

# Geophysical Metadata Management using a Juypter Notebook

## Usage

A full Anaconda install should provide all packages required to run the
metadata manager.

Open a new Jupyter Notebook (Python 3 >= 3.7) and execute the
following code within on cell:

	!pip install git+https://github.com/m-weigand/geometadp
	import IPython
	IPython.display.clear_output()
	%gui qt
	import geometadp
	obj = geometadp.geo_metadata()
	obj.manage()

.. note::

	The first three lines do install the metadata manager and can be omitted
	once it is installed.

[<img src="CAGS_metadata_Manager.png" width=90%>](https://agrogeophy.github.io/geometadp)

## Wishlist

* import functionality: import a given JSON-file and edit it

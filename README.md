|<img src="https://raw.githubusercontent.com/euroargodev/euroargodev.github.io/master/img/logo/ArgoLogos/Argo_Logo_S.gif" width="100"/>| <h1> Argo float of the day ! <br> ![Twitter Follow](https://img.shields.io/twitter/follow/argobot84)|
|:-----:|:-----:|

Every day, this repo will select an Argo float that reported data over the last 24 hours and will publish its data on Twitter.

Checkout the Twitter feed at: https://twitter.com/argobot84

### Data processing

- Select a random Argo profile reported over the last 24 hours from [the global index profile file](https://data-argo.ifremer.fr/ar_index_global_prof.txt.gz)
- Fetch profile data from the [IFREMER GDAC ftp](//ftp.ifremer.fr/argo)
- Create and save plots with profile measurements data
- Tweet meta data and images of plots on twitter at: https://twitter.com/argobot84

### Software Used

This bot is a Jupyter notebook. It uses open source Scientific Python packages, including:
- [Argopy](https://argopy.readthedocs.io): the Argo floats data model and data fetcher
- [Xarray](http://xarray.pydata.org/): the underlying data model and computational library
- [Matplotlib](https://matplotlib.org/) and [Cartopy](http://scitools.org.uk/cartopy/index.html) for plotting
- [Seaborn](https://seaborn.pydata.org/) and [Proplot](https://proplot.readthedocs.io/) to make beautiful plots


### Automation

The bot is automated using [Github workflows](//docs.github.com/en/actions/learn-github-actions), [papermill](//papermill.readthedocs.io/) and [Python-twitter](//python-twitter.readthedocs.io/).

***
This repository was inspired by: https://github.com/rabernat/poseidon-bot
 
This repository is maintained by:
<div>
<img src="https://www.umr-lops.fr/var/storage/images/_aliases/logo_main/medias-ifremer/medias-lops/logos/logo-lops-2/1459683-4-fre-FR/Logo-LOPS-2.png" width="70"/>
<img src="https://raw.githubusercontent.com/euroargodev/euroargodev.github.io/master/img/logo/ArgoFrance-logo_banner-color.png" width="200"/>
</div>

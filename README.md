<img src="https://raw.githubusercontent.com/euroargodev/euroargodev.github.io/master/img/logo/ArgoLogos/Argo_Logo_S.gif" width="100"/>

# Argo float of the day !
![Twitter Follow](https://img.shields.io/twitter/follow/argobot84)

[![Binder](https://binder.pangeo.io/badge_logo.svg)](https://binder.pangeo.io/v2/gh/euroargodev/floatoftheday/main?filepath=floatoftheday.ipynb)

Every day, this repo will select an Argo float that reported data over the last 24 hours and will publish on Twitter images of the data collected.

Checkout the Twitter feed at: https://twitter.com/argobot84

### Data processing

- Select a random Argo profile reported over the last 24 hours from [the weekly index profile file](ftp://ftp.ifremer.fr/ifremer/argo/ar_index_this_week_prof.txt)
- Fetch profile data from the [IFREMER GDAC ftp](ftp://ftp.ifremer.fr/argo)
- Load data with [argopy](https://argopy.readthedocs.io)
- Create and save plots with profile data
- Tweet meta data and images of plots on twitter at: https://twitter.com/argobot84

### Software Used

This bot is a Jupyter notebook. It uses open source Scientific Python packages, including
- [Argopy](https://argopy.readthedocs.io): the Argo floats data model and fetcher
- [Xarray](http://xarray.pydata.org/): the central data model and computational library
- [Matplotlib](https://matplotlib.org/) and [Cartopy](http://scitools.org.uk/cartopy/index.html) for plotting


### Automation

The bot is automated using github workflows and [papermill](https://papermill.readthedocs.io/).

***
This repository was inspired by: https://github.com/rabernat/poseidon-bot
 
This repository is maintained by:
<div>
<img src="https://www.argo-france.fr/wp-content/uploads/2019/10/Argo-logo_banner-color.png" width="200"/>
<img src="https://www.umr-lops.fr/var/storage/images/_aliases/logo_main/medias-ifremer/medias-lops/logos/logo-lops-2/1459683-4-fre-FR/Logo-LOPS-2.png" width="70"/>
</div>

FROM pangeo/pangeo-notebook:2021.02.02
RUN /srv/conda/envs/notebook/bin/python -m pip install git+https://github.com/cisaacstern/pangeo-forge-recipes.git@0.4.0-closed-file
RUN /srv/conda/envs/notebook/bin/python -m pip install -U "gcsfs>=2021.6.1"

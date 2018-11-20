## Jupyter Quick setup

``` Bash

conda create -n jupyter python=3.6
conda activate jupyter
conda install -y -c conda-forge \
    scipy           \
    numpy           \
    tensorflow-gpu  \
    keras           \
    pytorch         \
    pandas          \
    matplotlib      \
    nb_conda        \
    jupyterhub      \
    jupyterlab      \
    alembic         \
    decorator       \
    jinja2          \
    mako            \
    markupsafe      \
    nodejs          \
    psycopg2        \
    pyopenssl       \
    python-dateutil \
    python-editor   \
    sqlalchemy      \
    tornado         \
    traitlets
    
jupyter labextension install @jupyterlab/hub-extension

```

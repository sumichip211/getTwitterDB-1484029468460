web: ipython profile create; echo "c.NotebookApp.password = '$( python -c 'from IPython.lib import passwd; import os; print passwd(os.environ.get("PASSWORD", ""))' )'" >> ~/.ipython/profile_default/ipython_notebook_config.py; cd content; ipython notebook --port=$VCAP_APP_PORT --ip=$VCAP_APP_HOST --no-mathjax



default: run

run:
	docker run -i -t -p 8888:8888 -v "$(PWD)":/opt/notebooks continuumio/anaconda3 /bin/bash -c "/opt/conda/bin/conda install numpy matplotlib pandas jupyter notebook scikit-learn bokeh -y --quiet && mkdir -p /opt/notebooks && /opt/conda/bin/jupyter notebook --notebook-dir=/opt/notebooks --ip='*' --port=8888 --no-browser --allow-root"

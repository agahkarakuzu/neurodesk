FROM vnmd/neurodesktop:latest

# Invalidate cache when the main branch updates
ADD https://api.github.com/repos/NeuroDesk/example-notebooks/commits/main /dev/null

# Clone the example notebooks
RUN git clone https://github.com/NeuroDesk/example-notebooks.git /home/jovyan/examples

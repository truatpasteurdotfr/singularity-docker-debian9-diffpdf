# singularity-docker-debian9-diffpdf
singularity container based on debian9 docker providing diffpdf

Run diffpdf from the container without really installing it.

Running without installation:
```
singularity run shub://truatpasteurdotfr/singularity-docker-debian9-diffpdf
```
Building:
```
sudo singularity build singularity-docker-debian9-diffpdf.simg Singularity
```
or use the provided `build.sh` script.

Download and rename:
```
singularity pull --name "diffpdf.simg" shub://truatpasteurdotfr/singularity-docker-debian9-diffpdf
```

# Run ipython within a docker container mapping a host folder to docker.
docker run -ti -v $pwd:/workspace bvlc\caffe:cpu ipython 

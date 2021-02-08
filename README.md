# 3Dinpaint#

docker build -t 3dinp:test .


docker run -it  --gpus all -v [path-dir]:/3dInpaint/ 3dinp:ver1 /bin/bash

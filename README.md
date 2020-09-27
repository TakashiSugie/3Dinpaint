# 3Dinpaint#

docker build -t 3dinp:test .
docker run --rm -v /home/takashi/Desktop/study/3Dinpaint/3d-photo-inpainting-master:/3dInpaint 3dinp:test /bin/bash

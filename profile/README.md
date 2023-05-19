## AIC 👋
### Used in board rk3588
```
docker run -d --privileged --name test \
    -p 5555:5555 \
    -v /dev/mali0:/dev/mali0 \
    shangzebei/rk3588 androidboot.redroid_gpu_mode=mali
```

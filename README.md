# m1_mac_12_play_with_tflite
build for m1 mac

## **lane detection을 위해서 설치하다 열받아서 올립니다.**

기존에 있는 download_dependencies.sh가 mac에서는 grep 커맨드쪽이 다른것도 모르고 삽질을 했네요


```c
git clone https://github.com/iwatake2222/play_with_tflite.git
cd play_with_tflite
git submodule update --init --recursive --recommend-shallow --depth 1
cd InferenceHelper/third_party/tensorflow
chmod +x tensorflow/lite/tools/make/download_dependencies.sh
tensorflow/lite/tools/make/download_dependencies.sh
```

이부분입니다

기존의 download_dependencies.sh를 삭제하고 git clone 하신 download_dependencies.sh로 바꿔주세요

출처
https://github.com/iwatake2222/play_with_tflite

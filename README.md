## Android on-device (korean) TTS test project from [Sherpa-onnx](https://github.com/k2-fsa/sherpa-onnx) / [SherpaOnnxTts](https://github.com/k2-fsa/sherpa-onnx/tree/master/android/SherpaOnnxTts) demo


## pretraind model list
https://github.com/k2-fsa/sherpa-onnx/releases/tag/tts-models




Download pretraind-model, (detail [doc](https://k2-fsa.github.io/sherpa/onnx/android/build-sherpa-onnx.html#build-sherpa-onnx-c-code))
```shell
wget https://github.com/k2-fsa/sherpa-onnx/releases/download/tts-models/{target_file}.tar.bz2
tar xvf target_file.tar.bz2
rm target_file.tar.bz2
```
And move the folder to app/src/main/assets/

Like this examples

    kokoro-multi-lang-v1_1 > app/src/main/assets/kokoro-multi-lang-v1_1

    vits-mimic3-ko_KO-kss_low > app/src/main/assets/vits-mimic3-ko_KO-kss_low

    vits-vctk > app/src/main/assets/vits-vctk
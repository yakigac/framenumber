# Frame Number #
動画ファイル中のフレーム番号を確認するプログラム

### What is this repository for? ###
動画ファイルを引数として指定すると、フレーム番号とともに動画の中間地点が表示される。

プログラム中で使うキーコマンド  
- j:  1フレーム戻る  
- k:  1フレーム進む  
- n:  番号入力(コンソールに数字を入力)  
- q:  終了  

### How do I build this project? ###
```sh
$ ./waf configure
$ ./waf
```

### How do I use this project? ###

```sh
$ ./build/frame_number videofilename
```

### using libraries ###
- libopencv_core
- libopencv_highgui
- libopencv_imgproc

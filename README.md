# ubuntu_command
some commands <br>
1.tar <br>
```
$ sudo tar zcvf xxx.tar.gz files_path
```
<br>

2.delete files<br>
```
$ sudo rm path_files
```
<br>

3.delete files_dir<br>
```
$ sudo rmdir path_files
```
<br>

4.create files_dir<br>
```
$ sudo mkdir path_files
```
<br>

5.move A to B <br>
```
$ sudo mv A B
```
<br>

6.backup img from Nano:
```
$sudo dd if=/dev/sdc of=nano_back_1.img
```
<br>

7.寻找某行代码<br>

```
grep -nr "代码" 路径 
eg： grep -nr "mlir-opt yolov3_416_finetuning_without_detection_from_onnx_fp32.mlir" ~
```

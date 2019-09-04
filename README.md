# FMX-Camera-Corp-Image
如果在安卓8.0系统中，使用了
FMX.MediaLibrary.Actions.TTakePhotoFromCameraAction
并设置
Editable := True
在 DidFInishTaking 将不能返回裁剪后的图片，

详细情况请参见 QC 汇报：
https://quality.embarcadero.com/browse/RSP-23206

这次演示只演示调用摄像头拍照后，裁剪，返回裁剪后的图片。

测试平台：
华为 Mate8 + Android8.0

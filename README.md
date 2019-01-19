# ank-qrcode
##生成二维码
下面给二维码添加logo的功能
```
/**
 * 生成二维码图片
 * @param  integer $size    二维码大小
 * @param  string  $content 二维码内容
 * @param  string  $logo    二维码logo图片
 * @param  string  $savePath 二维码保存路径,留空的话直接输出
 * @return [type]           [description]
 */
\ank\QRcode::build($content = '', $size = 100, $logo = '', $savePath = '')
```
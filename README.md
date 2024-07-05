# stable_diffusion
stable-diffusionをいろいろ使うためのレポジトリ
備忘録に近いかも

## setup
```bash
git clone https://github.com/AUTOMATIC1111/stable-diffusion-webui
```
pythonのバージョンを上記Readmeを見ながら合わせて実行

※バージョンを検証されたものに合わせないと動かない

## modelの追加
ネットで、*.safetensorsをダウンロードし、stable-diffusion-webui/models/Stable-diffusionに入れるだけ

## local ネットワークへ公開
--listenを加えるのみ
--enable-insecure-extension-accessを加えるとエクステンションも可能

公開しているとGPU使用が弱い？
メモリは使用しているが、電源を使っていない・・・
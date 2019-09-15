# 郵便番号で住所自動入力

[yubinbango.js](https://github.com/yubinbango/yubinbango)を使って，郵便番号から住所を自動入力。[Bootstrap](https://getbootstrap.com/)を使っている。送信ボタンには動作を割り当てていない。

## テスト方法

ウェブブラウザで`index.html`を開く。

### 開発サーバ

PythonまたはPHPの開発用のサーバを使ってもよい。ウェブブラウザで[http://localhost:8000](http://localhost:8000)に接続する。

#### Python

```python
python -m http.server 8000
```

#### PHP
```php
php -S localhost:8000
```
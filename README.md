[![Build Status](https://travis-ci.org/pinalto/invoice-generator.svg?branch=master)](https://travis-ci.org/pinalto/invoice-generator)
[![Coverage Status](https://coveralls.io/repos/github/pinalto/invoice-generator/badge.svg?branch=master)](https://coveralls.io/github/pinalto/invoice-generator?branch=master)
![MIT License](https://img.shields.io/github/license/pinalto/invoice-generator.svg)


# Invoice

請求書ジェネレーターです。URLパラメーターをつけると入力状態で開くことができます。

```
https://pinalto.github.io/invoice-generator/?title=品目&count=数量&unit=人日&unitCost=単価
```

- 情報はローカルストレージに保存されます。画面右上よりキャッシュクリアが可能です
- 通信は一切発生しません。ローカルで完結しています。

## コントリビュート

- バグ報告や機能追加要望はIssueをください。
- 軽微な修正や機能追加については直PRでもOKです。
- 大きめのUI変更、機能追加はまずIssueでコンセンサスを得るようお願いします。

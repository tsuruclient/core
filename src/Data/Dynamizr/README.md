# Normalizer
Normalizerは、APIから取得した異なるデータを2つの過程を経てデータを正規化し、Tsuruが読める一意なデータに変換することを目的とした関数です。
以下の2つの過程を要します。  
  
## 正規化 - normalize
正規化は、Normalizrを介して行われます。これの主な理由は、階層構造になったデータを均し、操作しやすい形にするためです。  
[Dynamizr](https://stackblitz.com/edit/dynamizer)という名前にしていますがnpmで公開していません。  
  
## 平滑化 - smooth
平滑化は、平滑化されたデータを、データの種類―――User, Contentなど―――ごとにそれぞれ一意のオブジェクト形式に変換することです。  
  

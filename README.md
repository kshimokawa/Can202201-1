# がん研究会PBL 系統樹作成入門
This is test version.

# 系統樹推定：原理と特徴

距離に基づく方法
* 最近接法（近隣結合法）
  
  各配列（サンプル）のアライメントから塩基置換数に基づき距離行列を計算。
  距離行列から階層クラスタリングを行なう。距離行列の作成法に様々な提案がある（塩基置換の起こりやすさ、逆位、遺伝子移動）。
  
  計算効率が高く、他の方法では計算できない場合でも計算可能。異なる種間などサンプル間の配列が離れているものを扱う。
  

系統樹の評価に基づく方法
* 最大節約法（最節約法）

  最も塩基置換数の少ないステップ数で説明できるサンプル同士で系統樹を作っていく。
  
  系統樹推定に最初に使用された方法。多重置換を仮定していない。最適解が複数存在する。計算に時間がかかる。サンプル間の配列が比較的類似したものを扱うのに向いている。

* 最尤法

  多数の確率モデルがある。
  
  モデルを変えると結果が変わる可能性がある。
  

```bash
R repository
ssh !
```

# 系統樹の信頼性評価法
* BootStrap 法
  配列をサンプリングして長さを変えたものを使い、複数回の試行を行う。高い確率で推定される樹形図を信頼性の高いものとして評価する。
  

# がんサンプルの系統樹

* 分化度が高いサンプル
* 最大節約法
* 推定法


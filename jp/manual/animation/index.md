# アニメーション

<span class="label label-doc-audience">デザイナー</span>
<span class="label label-doc-audience">プログラマー</span>

3D モデルは、次の 3 種類のアセットを追加することによってアニメーション化できます。

* スケルトン
* スキン モデル
* アニメーション クリップ

>[!NOTE]
>2D アニメーションについては、「[スプライト](../sprites/index.md)」を参照してください。

### スケルトン

**スケルトン**は、3D モデルの変形パターンを記述するデジタル構造です。スケルトンは、階層を形成するボーンで構成されています。親ボーンの位置が変化すると、子ボーンの位置にも影響があります。たとえば、手のボーンには子ボーンが 5 個 (5 本の指) があります。手が上下に動くと、指もそれに合わせて動きます。

スケルトンは、実際の人や動物の骨格と似ている必要はありません。スケルトンを使用して、任意の 3D モデルをアニメーション化できます。

>[!NOTE]
>現在、Game Studio でスケルトンを目に見えるようにする手段はありません。

### スキン モデル

**スキニング**は、頂点とそれが依存するボーンに重みを割り当てるプロセスです。各頂点は、通常、1 つから 4 つのボーンに依存します。

**スキン モデル**は、スケルトンと一致するようにスキニングされたモデルです。**スキン**は、ボーンが移動したときにメッシュの頂点がどのように変形するかを記述しています。

>[!NOTE]
>Game Studio で作成できるのは、球体や立方体のような簡単な 3D モデルだけです。その方法については、「[アセットの作成](../game-studio/create-assets.md)」を参照してください。さらに複雑なモデルを作成するには、3DS Max、Maya、Blender のような専用のソフトウェアを使用した後、[モデルを Game Studio にインポート](import-animations.md)します。

### アニメーション クリップ

**アニメーション クリップ**は、特定の瞬間における**スケルトン**のポーズを記述するものです。スケルトンはアニメーションに従って動きます。メッシュの頂点は、現在のポーズと一致するように変形 (スキニング) します。

## アニメーションのサンプル

Xenko でのアニメーションの動き方の例を見るには、**Animation** サンプル プロジェクトを読み込んでください。

![Animations](media/animations-index1.png)

テンプレート [First-person shooter]、[Third-person platformer]、[Top-down RPG] にも、いくつかの高度なアニメーション技法が含まれます。

## このセクションの内容

* [アニメーションのインポート](import-animations.md)
* [アニメーションのプロパティ](animation-properties.md)
* [アニメーションのセットアップ](set-up-animations.md)
* [アニメーションのプレビュー](preview-animations.md)
* [アニメーションのスクリプト](animation-scripts.md)
* [加算アニメーション](additive-animation.md)
* [プロシージャル アニメーション](procedural-animation.md)
* [カスタム ブレンド ツリー](custom-blend-trees.md)
# 目次
* [どういうツール？](#about)
* [使い方](#how2use)
	* [設定](#setting)
	* [基本的な使い方](#use)
* [使用素材・アセット](#assets)
* [更新履歴](#histroy)

# <a id="about"></a>どういうツール？
AmongUSの議論中、誰がどこで死んだ、誰が怪しい、前回のキルがどこだったなどの情報を覚えておくのが苦手だったので、  
それを補助するためにツールを作成しました。  

基本的にPCでの使用を想定しています。  
ドラッグ＆ドロップによるキャラの移動、右クリックによるステータスの変更、スナップショットの撮影などが行えます。
![どういうツール](https://github.com/MoonInTheRain/AmongUsMap/blob/main/Resources/AmongUsMapUse.gif?raw=true)
## ツール自体はブラウザで起動動作するようにしています。[**リンク**](https://moonintherain.github.io/AmongUsMap/)

# <a id="how2use"></a>使い方
  
## <a id="setting"></a>設定
画面右上の『設定』からダイアログを開き、プレイヤー人数、プレイヤー名、色を設定できます。  
また、表示サイズやタッチ位置の調整ができます。
![設定](https://github.com/MoonInTheRain/AmongUsMap/blob/main/Resources/AmongUsMapSetting.gif?raw=true)

## <a id="use"></a>基本的な使い方
* マウスの左クリックによるドラッグ＆ドロップでキャラを移動できます。
* マウスの右クリックでキャラの状態を変更することが出来ます。  
	一部項目は重複して設定可能です。  
	![コンテキストメニュー](https://github.com/MoonInTheRain/AmongUsMap/blob/main/Resources/AmongUsMapContextMenu.jpg?raw=true)
	![キャラの状態](https://github.com/MoonInTheRain/AmongUsMap/blob/main/Resources/AmongUsMapChara.jpg?raw=true)
	* 死亡　　　　：骨になります。  
	　　　　　　　インポスターによりキルされたキャラに使用想定です。
	* 吊り　　　　：天使の輪が付きます。  
	　　　　　　　投票によって追放されたキャラに使用想定です。
	* 緊急押し済み：ボタンマークが表示されます。  
	　　　　　　　緊急ボタンを使用済みのキャラに使用想定です。  
	* 黒　　：目が赤くなります。  
	　　　　怪しいキャラに使用想定です。
	* グレー：目が水色になります。デフォルト。  
	　　　　どっちとも付かないキャラに使用想定です。
	* 白　　：目が緑になります。  
	　　　　怪しくないキャラに使用想定です。

* 『設定』ボタン：  
	[設定](#setting)を参照
* 『使い方/使用素材』ボタン：  
	このページを開きます。
* 『撮影』ボタン：  
	現在のマップの状態をスナップショットに撮ります。  
* 『全消去』ボタン：
	スナップショットをすべて消去します。  
	１つずつ削除するには、スナップショットの右上の『X』ボタンを押してください。
* 『位置リセット』ボタン：  
	キャラの状態はそのままで、位置だけを元に戻します。  
	議論が終わり、『撮影』を行った後に押す想定です。
* 『全リセット』ボタン：  
	キャラの位置と状態を元に戻します。  
	勝敗が付き、ゲームが終了した際に押す想定です。
  
# <a id="assets"></a>使用素材・アセット
* フォント  
	* しねきゃぷしゅん ([リンク](https://fontdasu.com/429))
* マップ
	* アモングアス日本語訳対応MAP([リンク](https://baskmedia.jp/amongus-japanese-map/))
* その他機能  
	* WebGLInput ([リンク](https://github.com/kou-yeung/WebGLInput))
	* DOTween (HOTween v2) ([リンク](https://assetstore.unity.com/packages/tools/animation/dotween-hotween-v2-27676))
	* Easy Save 3 ([リンク](https://assetstore.unity.com/packages/tools/utilities/easy-save-the-complete-save-data-serialization-asset-768))

# <a id="histroy"></a>更新履歴
* 2021/06/27 公開
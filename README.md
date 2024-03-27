# うんこ PRO 68K　リリース版
横スクロール型ゲーム「うんこPRO-68K ver1.00」のリリース版です。
## 文字通りのクソゲーです。

★概要★<br>
- XM6等のエミュレータで使用可能なフロッピーイメージ(XDF形式)となっておりますので、<br>
解凍したイメージファイルをエミュレータ側からマウント後に再起動する事で起動します。<br>
※フロッピーから起動しない場合は「OPT.1」に相当するキーを押下しながら起動して下さい。

★操作★<br>
■キーボードでの操作
- テンキーの「4」「6」「8」「2」で移動、「Z」でジャンプします。<br>
	アイテム（後述）を拾った場合は「X」キーで使用できます。<br>

■コントローラーでの操作
- コントローラーの場合は十字キーで移動、「A」キーでジャンプします。<br>
	アイテム（後述）を拾った場合は「B」キーで使用できます。<br><br>
- 「ESC」キーでPAUSEします。<br>
	コントローラーの場合は「SELECT」でPAUSEですが、富士通のTOWNSパッド（FMT-PD102）のみ対応となります。
- 壁や床に対して、半キャラ分程度であれば自動的に避ける機能を付加していますので、
- 若干操作が楽になっているかと思います。
- 途中で終了したい場合は「Q」で自爆（セルフ水洗）し残機を１機失います。

★ルール★
- 画面上に存在する敵キャラを避けてステージ内の「うんこ」を回収して下さい。<br>
	全て回収し終えるとステージクリアとなります。
- また、制限時間を経過すると「水洗」されてしまい残機を１機（？）失い、残機数０の<br>
	 時点でゲームオーバーとなります。
- 最終面に設置されている「伝説のクリーナー」を入手する事でクリアとなります。

★アイテム★<br>
- **ラバーカップ**：いわゆる、「お便所スッポン」です。アメーバくん以外の敵キャラをぶん殴って弾く事ができます。
- **ヨンポール**：あらゆるものを消毒・殺菌する、頼りになる洗浄剤です。**サ〇ポールじゃありません。ヨンポールです（力説）**

★敵キャラクタ★<br>
- **大腸菌くん１号**：お尻の鞭毛がチャームポイント。ひたすら直進しますが壁に当たると折り返します。
- **ノロウイルスくん**：緑色のウイルス。自機を追尾しますが壁を越える事はできません。
- **アメーバくん**：水色の単細胞生物ですが壁を通り抜ける事ができ、ラバーカップでは撃退できません。

★デモ及びトレースプレイ機能★<br>
- タイトル画面で一定時間以上放置すると、デモプレイが再生されます。
- トレース機能をONにすると、自分のプレイ内容を記憶します。メニューから「TRACE PLAY」を選択するとリプレイが再生できます。
 	トレースデータはメニューの「TRACE SAVE」を選択する事で１つだけファイルに保存できますが、無圧縮なのでファイルサイズが嵩みます。
  	最終面まで一気に記録すると、おおよそ500KBを超過する程度のサイズとなります。<br>
  ### ※なお、トレース機能は試験的に搭載しているため保存に失敗する可能性があります。

★謝辞★<br>
本ソフトウェアは、以下の方々の素晴らしいソフトウェア群によって支えられております。<br>
この場をお借りして、作者の皆様に感謝致します。
- [PI.](https://twitter.com/xm6_original)様
  <br>X68000エミュレータ「XM6 TypeG」
- [yosshin](https://twitter.com/yosshin4004/status/1645762714319605760)様
  <br>クロスコンパイル開発環境「xdev68k」
- [吉野智興](http://retropc.net/x68000/software/develop/c/gcc_mariko/)様
  <br>GNU Cコンパイラ「GCC真里子版 ver 1.42」
- [西川善司](http://www.z-z-z.jp/zmusic/)様
  <br>FM音源ドライバ「Z-MUSIC Ver3」
- [効果音ラボ](https://soundeffect-lab.info/)様
  <br>各種SE音声を利用させていただいております。
- [ヒホ](https://voicevox.hiroshiba.jp/qa/)様
  <br>テキスト読み上げソフト「VOICEVOX」
- [NOZ](http://noz.ub32.org/68fsw.html)様
  <br>音声ファイルの変換（wav形式からpcm形式に）ツール「pcm3pcm」
- [Thorbjørn Lindeijer](http://www.mapeditor.org/)様
  <br>マップエディタ「Tiled」
  <br><br>
  **また、制作中にＸ（旧Twitter）上にて、多くの方々より貴重なアドバイスをいただきました。<br>
  皆様のお力添え無しには本作品は完成しなかったであろうと思われます。<br>
  この場にて簡素ではありますが、改めてお礼申し上げます。**

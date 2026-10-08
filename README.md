# 森羅道中 巡礼（Aoi Walk: Junrei）── 坂東・秩父・江戸の札所を歩く（試作）

> 2026-10-05 に名前を改めました（旧名《Qualium in Junrei》）。Qualium は、この作品の考え方の名前として使います。

坂東三十三観音・秩父三十四観音・江戸三十三観音（昭和新撰）の札所 101 か所を、一つの地図で歩くアプリ。札所ごとに「見る → 碧の話 → 見直す」の順で、地形・水／歴史／文化・伝えを重ねる。案内は碧（あおい）。碧は mitsulab の AI。

公開先：https://mitsulab-soil.github.io/qualium-in-junrei/

## 試作であること（確かめている途中）

- くわしい札は 19 か所。ほかの 82 か所は、名簿にある本尊・宗派・開基などと、地面の高さを出す。
- 坂東・江戸の位置は、公式の地図リンクか、公式の住所を国土地理院の住所検索で引いた座標で、数十〜数百 m の誤差がありうる（◐）。門か本堂かは確かめていない。
- **要確認**（公式の表記の欠け・取り違え。アプリの中にも「要確認」と出る）：坂東 十番 正法寺の宗派／十七番 満願寺の本尊／二十番 西明寺の宗派／二十六番 清瀧寺の位置／江戸 二十七番 道往寺の本尊／秩父 七番・十二番・二十六番の住所／江戸三十三観音の始まりの時期（寺のサイトで書き方に幅がある）。
- 点線は番号順に直線で結んだもので、巡礼の道ではない。
- 信仰やご利益の効き目は書かない。伝えは「〜と伝えられる」「〜と公式は書いている」と書いた。

## AI であること

碧は AI。公式に書いてあることだけを話し、信仰を決めつけず、土地を診断しない。会話や位置は保存しない（来た日と謎の答えだけを、この端末の中に残す。消すボタンあり）。

## 出典・クレジット

- 名簿・札の中身：[秩父札所連合会](https://chichibufudasho.com/)・[坂東札所霊場会](https://bandou.gr.jp/)・江戸三十三観音の札所の寺の公式の一覧（[第 9 番 定泉寺](http://www.josenji.or.jp/kannon/)・[第 15 番 放生寺](https://www.houjou.or.jp/reijyou02.html)）・各寺の公式サイト（アプリの中に札ごとにリンク）
- 地図：[国土地理院 地理院タイル（淡色地図）](https://maps.gsi.go.jp/development/ichiran.html)。標高：国土地理院 標高 API。位置：国土地理院の住所検索。出典：国土地理院
- お寺の写真・御詠歌・巡礼道の線は取り込んでいない（リンクで示す）
- 碧の 3D：VRoid Studio で作った碧（作者 mitsulab）。表示＝[three.js](https://threejs.org/)・[@pixiv/three-vrm](https://github.com/pixiv/three-vrm)・地図＝[Leaflet](https://leafletjs.com/)

## 利用について

- ページの文・構成は © 2026 mitsulab。リンクは歓迎。
- 碧の 3D モデル（`web/aoi.vrm`）は、このアプリで碧を表示するためにだけ置いている。**作者（mitsulab）のみ利用・再配布しない・改変しない**の条件（VRM のメタ情報）。取り出して使わないでください。

作：mitsulab　https://mitsulab.jp

## 碧の声

碧の声：VOICEVOX:冥鳴ひまり（AI の合成音声。[VOICEVOX](https://voicevox.hiroshiba.jp/)）。寺の名・人の名・地名は、霊場会・寺・自治体の公式や辞典で読みを確かめたものだけを声にしています。声は押したときだけ鳴ります。

## 著作権 ／ Copyright

© 2026 mitsulab. All rights reserved. この作品の文章・画像・音声・3D・プログラムの著作権は、別に示した他者の素材を除き mitsulab にあります。無断の複製・転載・改変と、AI の学習・生成への利用はお断りします（テキスト・データマイニングの権利を留保します）。[利用規約](https://mitsulab.jp/terms/#ai)

© 2026 mitsulab. All rights reserved. Copyright in the text, images, audio, 3D and software of this work belongs to mitsulab, except third-party materials credited separately. Copying, reposting or modifying them without permission, and using them for AI training or generation, are not permitted. Text and data mining rights are reserved. [Terms](https://mitsulab.jp/terms/#ai-en)

他者の素材（CC BY・ODbL・CC0・VOICEVOX など）は、それぞれの条件に従います。

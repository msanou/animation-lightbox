# なんですか、これ
HTML5のCanvas APIを利用した、アニメ制作用Webアプリケーションです。

# 現在できること
イラストの描画、Undo/Redo(キャンバスにフォーカスが当たっている状態でCtrl + Z/Y)、フレーム追加、オニオンスキン表示(前後のフレームを別色で表示し確認できる機能)、アニメーション再生(8fps)

# To Do
- [x] ペン先の色指定・サイズ変更
- [x] 消しゴム
- [x] Undo, Redo
- [ ] フレームの削除・挿入・複製
- [ ] フレームレートの変更
- [ ] 空フレームの作成、再生時スキップ、オニオンスキンの非表示
- [x] オニオンスキン
- [ ] レイヤー機能
- [ ] 背景用フレームの追加
- [ ] グリッド表示機能(模写練習用として別のページにするかも)
- [ ] 画像の読み込み
- [ ] ペンの入り抜きでのサイズ・濃淡変更

## 実現方法が不明・未定なTo Do
- [ ] 筆圧検知によるサイズ・濃淡変更
- [ ] 解像度の変更やキャンバスの拡縮対応
- [ ] キャンバス内でアニメーション再生対象となるフレームの設定<sup>[1](#note1)</sup>
- [ ] パンニングなどの画面効果
- [ ] UIの拡充・改修
- [ ] オニオンスキンのパフォーマンス改善

etc...

<small id="note1">1:通常、アニメーションはA4サイズの紙などに描かれたものから画面比16:9の部分のみ放映されるので、キャンバス上からアニメーション再生する部分だけを切り出すような感じ。</note>

# 未来へ…

投稿機能や、同時に編集する機能などといった、SNS的な機能も導入したい。

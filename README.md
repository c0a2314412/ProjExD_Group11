# こうかとん伝説

## 実行環境の必要条件
* python >= 3.10
* pygame >= 2.1

## ゲームの概要
主人公キャラクターこうかとんがラウンドをどんどんクリアしていく。
ラウンドクリアごとに攻撃か体力の上昇を選択
３ラウンドくらいにしたい
* 敵の体力:３
* こうかとんの体力:５

## ゲームの実装
### 共通基本機能
* 背景画像と主人公キャラクターの描画

### 担当追加機能
* ラウンド表示（担当：ときたま）：今が第何ラウンドなのかを表示。ステージクリアごとにラウンドを更新する機能（３ラウンドくらいまでを想定）
* 敵追加１（担当：さとう）：ビームを使う敵を追加する機能
* 攻撃、体力上昇選択（担当：てる）：ラウンド終了時に攻撃、体力を選択して強化、更新する機能
<<<<<<< HEAD
* 敵追加２（担当：よっしー）：攻撃を当てると分裂し、小さくなるスライムを追加する機能

###　説明
* 敵追加１（担当：佐藤）敵機からこうかとんに対してline関数を用いて徐々に太くなるビームを描写、当たり判定の決定が不十分。

### 説明
指定の条件(現状は5キルするごと)をクリアするごとにラウンド数が増えていく

=======
* 敵追加２（担当：よっしー）：画面にいる敵の総数と次のラウンドに行くまでのカウントを表示
>>>>>>> nextround
### ToDo
* こうかとんが動いている間は攻撃を行わず、こうかとんが止まると、自動でビームを打つようにしたい。
* 敵の体力について、可視化できるような形にしたい。

### メモ
* クラス内の変数は，すべて，「get_変数名」という名前のメソッドを介してアクセスするように設計してある
* すべてのクラスに関係する関数は，クラスの外で定義してある


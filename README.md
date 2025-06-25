# feeder-worst　
Tampermonkeyにあったスクリプトが動かなかったので作成しました。


***このツールはオープンソースです。拡張、改造等は自己責任です。***
### IOSの場合
https://www.icloud.com/shortcuts/12fa1492a1af4967b63ad72998896957
※ショートカットアプリが立ち上がります
起動したいページ上で共有シートからworstV1,1を選択して"許可をする"を選択し、起動すれば成功です
### windowsの場合(※Chromeでのみ動作します)
~~上部"worst"フォルダをダウンロードし、Chromeの設定で拡張機能に移動します（chrome://extensions/）。
デベロッパーモードを有効化を選択します
パッケージ化されていない拡張機能を読み込むをクリックし、ダウンロードしたworstフォルダを選択します
上部アイコンバーに"worst"が追加されていれば成功です~~

↑パッケージ化しなくても、User javascript and css で動作するようにコードを更新しましたので、拡張機能内にペースト→新規ルールを作成の手順で起動してください。
<br>
<br>
・拡張機能ダウンロードリンク　<https://chromewebstore.google.com/detail/user-javascript-and-css/nbhcbdghjpllgmfilhnhkllmkecfmpld?hl=ja>
### Macの場合
基本の手順はIOSと同じですが、拡張機能として追加しても動作します。
### 今後追加予定の機能
preバージョンの完成と同時に、以下の機能の実装を考えています。
<br>・禁止ワード回避(Unicode)
<br>
・トリップ重複回避
<br>
・ALTban回避（制限数あり） 
<br>・カスタムCSSローダー  <br>
・起動キー割り当て（PC）
<br>・ステメ自動更新  <br>
・アイコンマネージャー  
・ALTマネージャー  
・連投検知自動回避  
　etc…

クライアントの作成開始しました。
<br>
<https://github.com/yakze/feeder-client>
<br>
α版、α版+（有料プラン）は7月までには出せれば良いと思っています。
<br>
Worstとの連携も予定しています。（Worst単体でもアップデートはします）

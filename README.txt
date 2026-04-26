待ち合わせマップ v4

変更点:
1. ログイン中メンバーの名前を画面左上に表示。
2. Firebase未設定でindex.html単体実行した場合も、自分の現在地マーカーを表示。
   ただし、複数人の位置共有にはFirebase Realtime Databaseが必要です。
3. マーカーの色分けを廃止し、全員同じ色に統一。
4. 「合言葉」を「パスワード」に変更。

仮パスワード:
index.html 内の以下を変更してください。
const PASSWORD = "m340";

Firebase設定:
index.html 内の firebaseConfig を自分のFirebaseプロジェクトの値に置き換えてください。

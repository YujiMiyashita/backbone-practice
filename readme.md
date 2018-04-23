## 処理の流れ

### アプリの起動

* Todosコレクションが作成
* Todoルーティングの作成
* AppViewの初期化
*

### タスクの登録

* .new-todoの入力欄から入力し、ENTER_KEYを押す
* /views/app-view.js のeventsである `'keypress .new-todo': 'createOnEnter'` が反応
* createOnEnter内のメソッドで、エンターキーの番号が一致し、さらに半角スペースのない状態になったら、コレクションを作成、入力欄を空欄にする
*

### チーム名
- quinque

### チームメンバーおよびそれぞれの役割
- ***
- ***
- 丸山 翼(github: TsubasaMaruyama)
- ***

### 開発するアプリケーションの概要
1. アプリケーション名  
    mother - Management Of THE Reality
1. アプリケーションの目的および解決すべき問題  
    色々なジャンルのやらなければいけないこと, やりたいことをまとめて管理するアプリ.
    TODOリスト, 読書リストなどの複数のタスクリストから一括して締め切りリマインドの通知を受け取る.
        
    __想定するタスクジャンル__
    - 読書
    - メール
    - レポート
    - 買い物
    - etc
    
1. アプリケーション仕様
    1. 基本機能
        - TODOリスト機能
            - タスク追加機能
            - 検索機能
        - リストを管理するリスト機能
            - トップ画面にリスト一覧を表示
            - それぞれのジャンルについて項目を決める
            - リストの追加・削除
        - 締め切り通知機能
            - トップ画面に締切通知を表示
            - 締め切りを設定したタスク→締切前に通知
            - 締め切りを設定していないタスク→タスク登録後, 定期的に通知
    1. 発展機能
        - タスク共有機能
            - タスクを他ユーザと共有
            - リスト全体の共有も可能
        - カレンダー表示機能
            - タスク作成時に締め切りをカレンダーから選ぶことができる
        - ページ遷移なしの画面切り替え
    1. 画面遷移
    
1. 作業分担  
    通知機能(サーバ) : 丸山翼  
    親リスト(サーバ) : 張新宇  
    リスト(サーバ) : 御喜家奈波  
    ログイン機能 : 丸山翼  
    ページデザイン(クライアント) : 金子真柚  
1. 開発スケジュール

    |予定日 |全体|通知機能 |親リスト |リスト |ログイン機能 |ページデザイン |
    |:---|:---|:---|:---|:---|:---|:--|
    |12/10(火) | |ルーティング詳細 | | | | | |
    |12/13(金) | データベース構造 <br> 基本ジャンル決定|||||全体デザイン|
    |12/17(火) | | - |追加|一覧表示追加|ユーザ追加|共通画面  CSS/html|
    |12/20(金) | | | 編集・削除 |編集・削除 |ログイン機能|ログイン画面作成|
    |12/23-27  | | |ユーザの紐付け |締切機能|ユーザ編集・退会|各リスト画面|
    |1/7(火)   | | 通知機能|ユーザの紐付け|カレンダー||通知機能可能|
    |1/10(金) | | | |カレンダー|||
    |1/14(火) | | |リスト共有 |タスク共有| | |
    |1/17(金) |拡張機能| | | | | |
    |1/21(火) |拡張機能/発表準備| | | | | |
    |1/24(金) | 発表準備||||||
    |1/28(火)| 発表日||||||

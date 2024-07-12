# graduation_exam

### サービス概要
1. 健康に関する質問やアドバイスを共有できる掲示板。
2. シンプルなUIで誰でも簡単に利用可能。

### このサービスへの思い・作りたい理由
このサービスは、健康管理に関心のある人たちが気軽に情報交換できる場を提供したいという思いから生まれました。自分自身が健康に関する情報を探していた際に、信頼できる情報源が分散しており、不便さを感じた経験があります。このアプリを通じて、健康に関する知識を共有し、お互いにサポートし合えるコミュニティを作りたいと考えました。

### ユーザー層について
**働く大人**：健康管理に関心が高く、同じ境遇の人々と情報を共有したいと考える人をターゲットとします。またシンプルなUIは、忙しい社会人に適していると考えました。

### サービスの利用イメージ
ユーザーは掲示板にアクセスし、健康に関する質問やアドバイスを投稿します。他のユーザーはそれに対してコメントをし、情報を交換します。検索機能を使って、過去の投稿や関連情報を簡単に見つけることができます。

### ユーザーの獲得について
**働く大人**：健康関連のブログやウェブサイトでの紹介、SNSでのプロモーション。

### サービスの差別化ポイント・推しポイント
- **既存の掲示板との差別化**：健康に特化した情報交換の場であり、特定のトピックに関する深い知識を持つコミュニティが形成されます。
- **独自の強み**：Stimulus Autocompleteを用いた検索機能により、必要な情報を迅速に見つけやすくします。

### 機能候補
- **MVPリリース時に作っていたい機能**
  - 基本的な掲示板機能（投稿、コメント、ブックマーク）
  - ユーザープロフィール機能
- **本リリースまでに作っていたい機能**
  - 検索機能（Stimulus Autocomplete）

### 機能の実装方針予定
- **掲示板機能**：Railsの標準的なCRUD機能を活用し、基本的な投稿・コメント機能を実装します。
- **検索機能**：Stimulus Autocompleteを使用して、ユーザーがキーワードを入力した際に関連するトピックや投稿が表示されるようにします。
- **ユーザープロフィール機能**：Deviseなどの認証ライブラリを用いて、ユーザーがプロフィール情報を登録・編集できるようにします。

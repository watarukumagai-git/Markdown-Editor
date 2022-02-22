Githubをリポジトリ用途で使用する方法。
- 2022/02/22: 作成。

# 1. Github
Githubは一般的なウェブサービスで、主にファイルやソースコードを管理・共有する用途で使用されている。

ソフトウェア開発企業によっては、ソースコード管理をGithubのプラットフォーム上で実施している企業もある。

一方、「重要なソースコードなのにpublicにしたままで情報流出した」という事件もあるため、企業で使用する場合は注意が必要である。

ただし、重要度が低いファイルをアップする範囲に留めておけば、大きな問題は発生しないと考えられる。

（サーベイで扱うファイルは、一般の論文について要約する程度のファイルなので）


# 2. リポジトリ
## 2.1 リポジトリとは
リポジトリとは、バージョン管理を前提としたデータベースである。

ソフトウェア開発においては、ソースコードをバージョンで管理するため、その一式をリポジトリと呼んでいる。

ただ、一般のファイルを扱う程度なら、「リポジトリ」＝「大きな塊のフォルダ」という認識で良い。

プロジェクト毎に、別々のリポジトリを作成しておくのが通常である。

また、単体のリポジトリの内部にフォルダを作成し、階層構造化することが可能である。

自分の場合は、下記URLがホームページである。

<https://github.com/watarukumagai-git>

そこに「how-to-use_Github」というリポジトリを作成し、そこにこのmdファイルをアップロードしている。

<https://github.com/watarukumagai-git/how-to-use_Github>

リポジトリ名の変更設定は、下記の手順で可能である。

- 手順1：リポジトリページのタブの「Settings」を開く。
- 手順2：「General」の一番上に、「Repository name」がある。その欄を変更して、Renameボタンを押せば変更が可能。


## 2.2 その他用語
ブランチやコミットという用語が登場するが、これらはバージョン管理用語である。

「ブランチ」＝「分岐先」を指すが、一人で一般のファイルを扱うなら、ブランチは常に一つで良く、気にする必要はない。

「コミット」＝「上書き保存」という認識で良い。


## 2.3 public/private
リポジトリ毎に、public/privateという設定がある。

publicの場合、一般ユーザがアクセスできるリポジトリとなり、そこに含まれているファイルはダウンロードすることが可能である。

privateの場合、原則非公開のリポジトリとなり、管理者が許可したユーザしかアクセスできない。

__.mdからオンライン上の画像を参照する場合、publicリポジトリに画像をアップロードしておく必要がある。__

public/privateの切替設定は、下記の手順で可能である。

- 手順1：リポジトリページのタブの「Settings」を開く。
- 手順2：「General」の下のほうに、「Danger Zone」=>「Change repository visibility」 がある。Change visibilityボタンを押す。
- 手順3：「Make public」か「Make private」を選ぶ。「please type ** to confirm」とあるので、空欄に入力して変更ボタンを押せば変更が可能。


# 3. ファイル・フォルダ操作
## 3.1 ファイルのアップロード
リポジトリへのアップロードは、下記の手順で可能である。

- 手順1：アップロードしたいリポジトリページのタブの「Code」を開き、「Add file」=>「Upload files」を押す。
- 手順2：「Drag files here**」と表示されているエリアに、アップロードしたいファイルをドラッグ&ドロップする。
- 手順3：一番下の「Commit changes」を押すと、アップロードが完了する。

## 3.2 フォルダの作成方法
リポジトリ内でフォルダ作成はデフォルトではできない。
リポジトリ内でのフォルダの作成方法は、下記の手順で可能である。

- 手順1：リポジトリページのタブの「Code」を開き、「Add file」=>「Create new file」を押す。
- 手順2：上に「<リポジトリ名>/[Name your file...] in main」と表示されている。[Name your file]の欄に「/< foldername >」と入力すると、「<リポジトリ名>/< foldername >/[Name your file...] in main」に自動で変更される。
- 手順3：
なお、Name your fileにファイル名をタイプすると、そのまま新しくファイルを作成することになる。
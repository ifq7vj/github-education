# N/S高生へ、GitHub Education について

## はじめに

GitHub Education (以下 Education) は、学生や教育者向けに GitHub の様々な機能を無償で提供するプログラムです。
Education に登録すると、学生向けプランの Global Campus や有料プランの Pro など、様々なサービスを利用することができます。
また、AI がコード補完などを行う Copilot も利用することができます。

そんなわけで、申請しない手はない！！ と思ったのですが、いざやってみると全く通らない...
かなり格闘してやっと通せたので、Education について少しまとめてみようと思います。

## 申請方法の概要

GitHub Education の申請方法を以下に示します。
一度では通らないと思いますが、まずは申請してみましょう。
GitHub アカウントを持っていない場合は、[GitHub](https://github.com/) からアカウントを作成してください。

1. [GitHub Education](https://education.github.com/) にアクセスし、指示に従って進みます。
2. メールアドレスや在籍している学校などの情報や、学生証の写真を求められるのでアップロードします。
3. [Get your GitHub benefits](https://education.github.com/discount_requests/application) から申請の状況を見る事ができます。Approved が表示されていれば成功です。
4. しばらく待ちましょう。申請後、数時間から数日で承認されます。

## トラブルシューティング

ほとんどの人は、上記の方法で申請しても承認されずに Rejected と表示されていると思います。
私は以下の方法で対策できたため、参考にしてください。
弾かれた理由はあくまで可能性なので、別の原因があるかもしれません。

### 選択した学校の近くにいない

> You appear not to be near any campus location for the school you have selected.

選択した校舎からあまりにも遠い場所にいるため、その学校に所属していると判断されません。
この場合、申請理由や学生証の写真に通信制高校の生徒である旨を記載することで対策ができます。

### プロフィールが不十分

> You are unlikely to be verified until you have completed your GitHub user profile with your full name as it appears in your academic affiliation document plus a short bio.

GitHub のプロフィールが不十分であるため、学生証の写真に記載されている情報との照合ができません。
GitHub のプロフィールに学生証と同様の情報や、高校のホームページのURLを記載することで対策ができます。
プロフィールの更新には一度ログアウトが必要な点に注意してください。

### 学校名が含まれていない (S高生)

> The image you selected does not appear to contain your school name.

学生証の写真に入力したものと同様の学校名が含まれていないため、照合ができないとのことです。
このエラーが出た時にもしっかりと学校名が写っていたため、S高生がメールドメインからN高生と判断されている時に生じるエラーでしょう。
これは、申請理由や学生証の写真にメールドメインがN高と共通であるが、S高生であるという内容を記載することで対策ができます。

### 学生証の写真が不十分

> Uploaded images are more easily manipulated and are therefore less trustworthy.

学生証の写真がアップロードされているため、信頼性が低いと判断されています。
これはデジタルである限り仕方がないので、印刷して PC のカメラで頑張って撮りましょう。

### 学生証の写真が編集されている

> The image you used appears to be edited. Manipulated images may not be used. Please try a different image.

学生証の写真が編集されているため、使用できないとのことです。
これもデジタルである限り仕方がないので、同じく印刷して PC のカメラで撮影しましょう。

## 詳細な申請方法/通し方

上記を踏まえて、詳細な申請方法及び通し方を示します。
これでも一度では通らないと思うので、申請が通るまで試行錯誤して頑張りましょう！

### プロフィールの更新

まずは GitHub のプロフィールを更新しましょう。
私の場合ですが、以下のように記載しました。(詳細には覚えていないので、一部誤りがあるかもしれません)

| 項目 | 内容 |
| :-: | :-: |
| Name | <ローマ字> / <本名> |
| Bio | S High School Student |
| Company | S High School / S高等学校 |
| Location | Sapporo, Hokkaido, Japan |
| Website | https://nnn.ed.jp/high_school_feature/s_high_school/ |

### 申請理由

申請理由は以下のように記載しました。必要に応じて変更してください。
「GitHub Pro を使って、開発やプロジェクトをより良いものにしていきたいと思います。」という文章と、本校からの距離/メールドメインに関する説明です。

> I will use GitHub Pro to improve my development and projects.
> I am a student at S High School, a correspondence high school, and my student ID is digital.
> My email domain is nnn.ed.jp, which I share with N High School.
> I can tell it is official by checking it against the school's website.
> https://nnn.ed.jp/high_school_feature/s_high_school/

### 学生証の写真

マイページのスクリーンショットを撮り、右側に英語訳/左側には背景の説明を記載して印刷、PC のカメラで撮影しました。
[テンプレート](https://github.com/ifq7vj/github-education/blob/main/student_card.psd)(psd) を適当に編集して使用するか、参考にして情報を記載すると良いでしょう。
証明書の形式は Student Id です。

### 申請

1. [GitHub Education](https://education.github.com/) にアクセスし、指示に従って申請を行いましょう。
2. [Get your GitHub benefits](https://education.github.com/discount_requests/application) で状況を確認し、Approved となっていれば成功です！！

## GitHub Copilot

GitHub Copilot は、GitHub が提供する AI によるコード補完機能で、VSCode, Visual Studio, JetBrains IDE, Vim/NeoVim に対応しています。
拡張機能をインストールして簡単に Copilot を利用することができるエディタもあるので、[GitHub Copilotの概要](https://docs.github.com/ja/copilot/getting-started-with-github-copilot) を参考に、ぜひ活用してみてください！

## おわりに

上記の方法を何度も試しても通らないという事もあると思いますが、今後の申請のハードルが下がるよう、格闘して情報を共有していただけると嬉しいです。
最後に、この記事が少しでも役に立てることを願い、様々な情報を共有してくださった #programming の皆様に感謝しています。

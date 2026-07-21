# 共通ルール：Google Workspaceとは（個人アカウントとの違い）

> 対象アプリ: 全アプリ共通
> 最終更新日: 2026-07-20
> 作成・更新者: {氏名}

## 1. 概要

Google Workspace（グーグル ワークスペース）は、Gmail・ドライブ・カレンダー・Meet などを**会社のアカウントとして一括管理**して使う、法人向けのグループウェアです。
このマニュアルでは、Google Workspace とは何か、個人の Gmail アカウント（〜@gmail.com）と何が違うのかを説明し、当社でのアカウント（エディション）の種類と発行手順をまとめます。

## 2. 機能の説明

### 2-1. Google Workspace とは

Google Workspace は、Google が提供する法人・組織向けのサービスで、以下の特徴があります。

- **会社独自のドメインのメールアドレスを使う**（例: `氏名@会社ドメイン`）
- Gmail / ドライブ / ドキュメント / スプレッドシート / スライド / カレンダー / Meet / Chat などを、同じアカウントでまとめて利用できる
- **管理者がアカウントやデータ、セキュリティを一元管理**できる
- 会社としてデータを保有・管理するため、退職・異動時のアカウント停止やデータ引き継ぎができる

つまり、「個人が無料で使う Google」ではなく、**会社が契約し、会社が管理する Google** です。

### 2-2. 個人アカウント（〜@gmail.com）との違い

| 項目 | 個人アカウント（〜@gmail.com） | Google Workspace（会社アカウント） |
| --- | --- | --- |
| アカウントの持ち主 | 個人 | **会社** |
| メールアドレス | 〜@gmail.com | 会社ドメインのアドレス |
| 発行・管理 | 個人が自由に作成 | **会社が発行・管理** |
| データの所有 | 個人 | **会社**（業務データは会社の資産） |
| 管理・セキュリティ設定 | 個人任せ | 管理者が組織全体に適用 |
| 退職・異動時 | 個人が継続保持 | 会社がアカウント停止・データ引き継ぎ |
| サポート | なし（自己解決） | 会社／Google のサポート |

**ポイント**：会社アカウントで作成・保存したメールやファイルは、**個人のものではなく会社の資産**です。個人の Gmail とは切り分けて利用してください。

### 2-3. 当社で使うアカウント（エディション）の種類

当社では、担当する業務範囲に応じて、次の **Google のエディション**を使い分けます。どのエディションになるかは業務範囲に応じて判断され、発行時に決まります。

- **エンタープライズスタンダード（Enterprise Standard）**：本部・オフィス社員向けの**フル機能版**。業務アプリ、AI、セキュリティ、コンプライアンスを包括する。
- **フロントラインスターター（Frontline Starter）**：店舗・工場・現場社員向けの**軽量版**。Gmail・Chat・Meet・ドキュメント等を低容量で提供する。
- **Cloud Identity Free（クラウド アイデンティティ フリー）**：Gmail を持たない**ID 管理用**。会社の Google アカウント・SSO・グループ・基本的な端末管理だけを無料で提供する。Google Workspace の廉価版ではなく、あくまで ID 管理サービス。

> **【訂正】** 以前このマニュアルで「エッセンシャルスタンダード」と記載していたのは誤りで、正しくは **エンタープライズスタンダード（Enterprise Standard）**です。
> Essentials 系エディション（Essentials Starter／Enterprise Essentials 等）は **Gmail（会社メール）を含みません**が、**Enterprise Standard は会社ドメインの Gmail を含みます**。

### 2-4. エディション詳細比較表（Cloud Identity Free／Enterprise Standard／Frontline Starter）

記号の意味：**◎＝本格利用可能／○＝利用可能／△＝制限・条件あり／×＝ライセンスに含まれない**
（2026年7月16日時点の Google 公式比較に基づく。「Googleアイデンティティフリー」の正式名称は **Cloud Identity Free**）

| 比較項目 | Cloud Identity Free | Enterprise Standard | Frontline Starter |
| --- | --- | --- | --- |
| **サービスの位置づけ** | **ID管理用**。会社アカウント、SSO、グループ、基本的な端末管理が中心 | **本部・オフィス社員向けのフル機能版**。業務アプリ、AI、セキュリティ、コンプライアンスを包括 | **店舗・工場・現場社員向けの軽量版**。Gmail、Chat、Meet、ドキュメント等を低容量で提供 ([Google Cloud][1]) |
| **想定される利用者** | Gmailやカレンダーを必要とせず、会社IDやSSOだけ必要な人 | 本部社員、管理職、文書作成者、情報管理担当、法務・人事など | 店舗従業員、製造・物流・接客・コールセンターなどの現場社員 ([Google Cloud][1]) |
| **利用者の資格条件** | 特別な職種条件なし | 特別な職種条件なし | **厳格なFrontline適格性あり**。顧客対応・製造・物流等が主業務で、共有端末またはモバイル中心、文書作成が軽度であることが原則。Googleが不適格と判断すると利用を制限する場合あり ([Google Workspace Help][2]) |
| **料金・購入方法** | 無料 | 有料。Googleまたは販売代理店から見積り | 有料。Googleまたは販売代理店から見積り ([Google Cloud][1]) |
| **利用人数** | 申し込み時にユーザー上限が通常50増加。追加の無料ライセンス申請が可能 | 人数上限なし | 適格なFrontline社員であれば人数上限なし ([Google Cloud][1]) |
| **会社管理のGoogleアカウント** | ◎ | ◎ | ◎ |
| **管理コンソール・組織部門・グループ管理** | ◎。組織部門・グループは無制限 | ◎。高度な管理・監査を含む | ◎。基本的な管理・監査を含む ([Google Cloud][1]) |
| **独自ドメインのGmail** | ×。会社メールボックスは付かない | ◎。`氏名@会社ドメイン`のメール | ◎。`氏名@会社ドメイン`のメール ([Google Cloud][1]) |
| **Googleカレンダー** | ×。Workspace版は付かない | ◎ | ◎。チームカレンダー、設備・会議室予約にも対応 ([Google Cloud][1]) |
| **Google Chat・スペース** | ×。Workspace版は付かない | ◎。高度な管理とAI機能あり | ○。1対1、グループ、スペース、外部チャット等を利用可能 ([Google Workspace Help][3]) |
| **Google Meet** | ×。Cloud Identityのライセンス機能には含まれない | ◎。最大500人、最長24時間、録画・Drive保存等に対応 | ○。最大100人、最長24時間。画面共有、ノイズキャンセル、出席確認等に対応 ([Google Workspace Help][3]) |
| **Drive・ドキュメント・スプレッドシート** | △。作成・共有は可能だが、本人用ストレージは付かない | ◎。フル機能 | ○。Docs、Sheets、Slides、Forms、Sitesを利用可能 ([Google Cloud][1]) |
| **ストレージ容量** | **0GB**。ただし、同じ組織にWorkspace契約があれば、そのストレージプールを消費可能 | **1ユーザー当たり5TBを組織でプール** | **1ユーザー当たり5GB**。Gmail、Drive、写真等で共用 ([Google Cloud][1]) |
| **共有ドライブへの参加権限** | △。メンバーとしては原則「閲覧者」のみ。ただし、個別に直接共有されたファイルは編集・コメント可能 | ◎。投稿者、コンテンツ管理者、管理者など通常の権限を付与可能 | △。メンバーとしては原則「閲覧者」のみ。ただし、個別に直接共有されたファイルは編集・コメント可能 ([Google Cloud][1]) |
| **Googleグループ・メーリングリスト** | ◎ | ◎ | ◎。共同トレイやメッセージ管理にも対応 ([Google Cloud][1]) |
| **Google Forms** | △。Drive・ドキュメント系の限定利用として扱われる | ◎ | ◎。店舗アンケート、教育テスト、チェックリスト等に利用可能 ([Google Cloud][1]) |
| **AppSheet Core** | ×。Coreライセンスは付かず、必要なら別契約 | ◎。追加料金なしで含まれる | ◎。追加料金なしで含まれる ([Google Workspace Help][3]) |
| **NotebookLM** | △。追加Googleサービスとして提供される場合がある | ◎ | ○。利用可能 ([Google Workspace Help][4]) |
| **Geminiアプリ単体** | △。管理者が許可すれば追加Googleサービスとして利用可能。ただしWorkspaceのコアサービス扱いではなく、機密情報の投入には不向き | ◎。コアサービス扱いで企業向けデータ保護あり。Frontline Starterより高い利用枠 | ○。コアサービス扱いで企業向けデータ保護あり。ただし基本アクセスで利用上限は比較的低い ([Google Workspace Help][5]) |
| **Gmail・Chat・Meet・Docs内のGemini** | × | ◎。文章作成、要約、メールスレッド要約、会議メモ、スプレッドシート支援などを利用可能 | ×。Starterには付かない。これらは原則Frontline Plusの機能 ([Google Workspace Help][3]) |
| **Google Vids** | × | ◎。作成・編集可能 | △。閲覧のみ。作成・編集は不可 ([Google Workspace Help][3]) |
| **Gmailの分割配信・デュアルデリバリ** | ×。Gmail自体がない | ◎。既存メールとGmailを併用する移行にも対応 | ◎。分割配信、デュアルデリバリ、受信・送信ゲートウェイ等に対応 ([Google Workspace Help][3]) |
| **迷惑メール・フィッシング対策** | Gmailなし | ◎。高度なフィッシング・マルウェア対策、Security Sandbox等 | ○。迷惑メール、ウイルス、高度なフィッシング・マルウェア対策あり。ただしSecurity Sandboxはなし ([Google Workspace Help][3]) |
| **2段階認証・セキュリティキー** | ◎ | ◎ | ◎ ([Google Cloud][1]) |
| **GoogleをIdPとしたSSO** | ◎。Cloud Identityの主要用途 | ◎ | ◎。200以上の設定済みSAMLアプリにも対応 ([Google Cloud][1]) |
| **外部IdPからGoogleへのSSO** | ◎ | ◎ | ◎ ([Google Cloud][1]) |
| **SAMLアプリの自動プロビジョニング** | ×。Free版には付かない | ◎。接続数は無制限 | △。最大3アプリ ([Google Cloud][1]) |
| **Secure LDAP** | ×。Premiumのみ | ◎ | ×。StarterにはCloud Identity Premiumが含まれない ([Google Cloud][1]) |
| **端末管理のレベル** | △。基本管理。パスコード、端末ブロック、アカウント削除など | ◎。エンタープライズ管理。会社所有端末、証明書、iOS保護、ルール制御等 | ○。高度な端末管理。強力なパスコード、Android仕事用プロファイル、ゼロタッチ登録、Windows管理等 ([Google Cloud][1]) |
| **端末紛失時のワイプ** | △。Googleアカウントや仕事用データのワイプが中心。端末全体のワイプは不可 | ◎。端末全体のリモートワイプに対応 | ◎。端末全体のリモートワイプに対応 ([Google Cloud][1]) |
| **DLP／情報漏えい防止** | × | ◎。Gmail、Drive、ChatのDLPルールを設定可能 | ×。機密情報を含むDriveファイルの「分析レポート」はあるが、共有を自動で止めるDLPルールはない ([Google Workspace Help][3]) |
| **Google Vault** | × | ◎。メール、Drive、Chat等の保持、検索、eDiscovery、法的保持 | ×。Frontline Standard以上で利用可能 ([Google Workspace Help][3]) |
| **Context-Aware Access** | ×。Premiumのみ | ◎。利用者、端末状態、IP、地域等に基づくアクセス制御 | ×。Frontline Standard以上で利用可能 ([Google Cloud][1]) |
| **Cloud Identity Premium機能** | × | ◎。別ライセンスなしで含まれる | ×。Frontline Standard以上で含まれる ([Google Workspace Help][3]) |
| **監査ログ** | ○。管理者、ユーザー、SAML、OAuth、グループ、Drive等の基本ログ | ◎。Gmail、Drive、Chat、端末、Meet等の詳細ログ | ○。Gmail、Drive、Chat、Meet、端末等のログイベントを確認可能 ([Google Cloud][1]) |
| **セキュリティ調査ツール** | ×。Free版にはない | ◎。検索結果からメール隔離、ファイル共有修正、端末対応等を実行可能 | △。ログの検索・確認は可能だが、検索結果から直接対処する高度機能はFrontline Standard以上 ([Google Cloud][1]) |
| **データリージョン** | × | ○。全社共通で保存地域を1つ設定できる基本データリージョン | ○。全社共通で保存地域を1つ設定できる基本データリージョン ([Google Workspace Help][6]) |
| **ランサムウェア検知** | × | ◎。標準で含まれる | △。Starterでは追加オプション ([Google Workspace Help][3]) |
| **サポート・稼働率保証** | コミュニティサポート中心。99.9％SLAなし | Enhanced Support、99.9％稼働率保証 | Standard Support、99.9％稼働率保証 ([Google Cloud][1]) |
| **最適な用途** | SSO専用、社内システムへのログイン、グループ所属、最低限の端末管理 | 本部、管理職、クレーム・個人情報・人事・法務、資料作成、共有ドライブ管理 | 店舗従業員へのGmail、Chat、Forms、AppSheet、限定的なSheets利用 |
| **最大の注意点** | Gmail、Calendar、Chat、Meet、AppSheet Coreがないため、業務アカウントの代替にはなりにくい | 機能は最も充実するが、全社員配布では費用が大きい | 5GB、共有ドライブは閲覧者のみ、Vault・DLPなし、Workspace内Geminiなし、Frontline適格性が必要 |

### 2-5. 3つの違いを一言で整理すると

- **Cloud Identity Free ＝「会社のデジタル社員証」**
  Google アカウントを作り、SSO・グループ・基本端末管理はできますが、Gmail や Chat を使う通常の業務アカウントにはなりません。

- **Frontline Starter ＝「店舗・現場社員向けの業務アカウント」**
  Gmail・Calendar・Chat・Meet・Forms・Sheets・AppSheet Core まで利用できます。現場社員に業務連絡、アンケート、教育テスト、チェックアプリなどを提供する用途に強力です。

- **Enterprise Standard ＝「本部・管理者向けの完全版」**
  5TB ストレージ、共有ドライブの完全な権限、Vault、DLP、Context-Aware Access、セキュリティ調査、Workspace 内 Gemini などが付いています。

### 2-6. 当社（400店舗・約12,000名規模）での運用設計

当社の規模では、次の **3層構成**が合理的です。

| 対象 | 割り当てエディション | 理由 |
| --- | --- | --- |
| 本部社員・管理職・店長の一部 | **Enterprise Standard** | クレーム情報、従業員情報、報告書、会議資料、通達、個人情報を扱うため、Vault・DLP・共有ドライブ管理・5TB・Gemini 機能が必要 |
| 店舗従業員 | **Frontline Starter** | Gmail・Chat・Forms・AppSheet・教育資料・限定的な Sheets 利用が中心。共有端末／モバイル中心・軽度の文書作成という実態にも合致 |
| メール不要・SSO だけ必要な人 | **Cloud Identity Free** | 勤怠・社内ポータル・外部 SaaS などへのログイン ID だけ必要で、Gmail や AppSheet を使わない人向け |

> **【運用上の重要注意】**
> - **Frontline Starter は共有ドライブのメンバー権限が「閲覧者」に限定**されます。店舗従業員に共有ドライブ内のスプレッドシートを更新させる場合は、そのファイルを**個別に「編集者」として直接共有**する運用が必要です。
> - **Frontline Starter は Gmail と Drive を合わせて 5GB** です。写真・動画・添付ファイルを大量保存させない設計が必要です。
> - 契約時には、次の4点を**販売代理店の見積条件に明記して確認**してください。
>   1. Frontline 適格性（対象職種・共有端末／モバイル中心・軽度な文書作成の要件）
>   2. Enterprise との混在条件
>   3. 共有ドライブの編集運用（個別共有での対応）
>   4. Frontline の 5GB 上限

## 3. 社内ルール

- **やること**
  - 業務では必ず**会社アカウント（Google Workspace）**を使用する
  - 自分のアカウント種別（エンタープライズスタンダード／フロントラインスターター／Cloud Identity Free）を把握しておく
- **やってはいけないこと**
  - 業務データを個人の Gmail アカウントに保存・転送しない
  - 会社アカウントを私的な用途に使わない
- **アカウントの発行手順**
  1. 所属部門で **物流部の承認**を得る
  2. 承認後、**システム課へアカウント発行を依頼**する
  3. システム課が、**業務範囲に応じて**エディション（エンタープライズスタンダード／フロントラインスターター／Cloud Identity Free）を判断して発行する
- **エディションの考え方**
  - どのエディションになるかは、担当する**業務範囲に応じて判断**される（目安は「2-6. 当社での運用設計」参照）
- **例外・注意点**
  - フロントラインスターターの利用者に共有ドライブ内ファイルを編集させる場合は、**個別に「編集者」で直接共有**する（メンバー権限は閲覧者のみのため）
  - エディションの変更が必要な場合も、物流部の承認 → システム課依頼の流れで対応する
  - 退職・異動時のアカウントの扱いについては、**システム課へ連絡**する

## 4. よくある質問（FAQ）

**Q. 個人の Gmail をそのまま業務に使ってもいい？**
A. いいえ。業務は必ず会社アカウントを使用してください。データの所有・管理の観点から、個人アカウントの業務利用は禁止です。

**Q. 自分がどのエディションか分からない。**
A. **システム課へ連絡**して確認してください。エディションは業務範囲に応じて判断されています。

**Q. どのエディションになるかは誰が決める？**
A. 担当する**業務範囲に応じて判断**され、発行時に決まります（目安は「2-6. 当社での運用設計」参照）。

**Q. アカウントはどうやって発行してもらう？**
A. 物流部の承認を得たうえで、システム課へ発行を依頼してください（詳細は「3. 社内ルール」参照）。

**Q. 店舗のスタッフ（フロントラインスターター）が共有ドライブのファイルを編集できない。**
A. Frontline Starter は共有ドライブのメンバー権限が「閲覧者」に限定されるためです。編集させたいファイルは、**個別に「編集者」として直接共有**してください。

**Q. Cloud Identity Free で Gmail は使える？**
A. 使えません。Cloud Identity Free は ID 管理用で、Gmail・カレンダー・Chat・Meet は含まれません。会社メールが必要な人には割り当てないでください。

## 5. 関連リンク

- 関連する社内マニュアル: {アカウント・ログイン.md／セキュリティ・機密区分.md（作成予定）}
- 公式ヘルプ: Google Workspace ヘルプ（https://support.google.com/a）

### 出典（Google 公式・2026-07-16 時点）

[1]: https://cloud.google.com/identity/docs/editions?hl=ja "エディション | Cloud Identity | Google Cloud Documentation"
[2]: https://knowledge.workspace.google.com/admin/getting-started/editions/frontline-edition-eligibility-requirements "Frontline edition eligibility requirements | Google Workspace Help"
[3]: https://knowledge.workspace.google.com/admin/getting-started/editions/compare-enterprise-editions "Compare Enterprise editions | Google Workspace Help"
[4]: https://knowledge.workspace.google.com/admin/getting-started/editions/compare-frontline-editions "Compare Frontline editions | Google Workspace Help"
[5]: https://knowledge.workspace.google.com/admin/generative-ai/gemini-app/turn-the-gemini-app-on-or-off "Turn the Gemini App on or off | Google Workspace Help"
[6]: https://knowledge.workspace.google.com/admin/compliance/compare-data-region-features-across-google-workspace-editions "Compare data region features across Google Workspace editions | Google Workspace Help"

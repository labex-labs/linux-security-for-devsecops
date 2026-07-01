# DevSecOpsのためのLinuxセキュリティ

**言語:** [English](README.md) · [简体中文](README_zh.md) · [Español](README_es.md) · [Français](README_fr.md) · [Deutsch](README_de.md) · [日本語](README_ja.md) · [Русский](README_ru.md) · [한국어](README_ko.md) · [Português](README_pt.md)

<p align="center">
  <a href="https://labex.io/ja/courses/linux-security-for-devsecops">
    <img src="https://course-cover.labex.io/linux-security-for-devsecops.png?lang=ja" alt="DevSecOpsのためのLinuxセキュリティ">
  </a>
</p>

DevSecOps学習者向けのハンズオン形式のLinuxセキュリティコースです。サービスの公開設定、Webの堅牢化、ファイル権限、sudo、シークレット管理、root権限での自動化といったトピックを網羅しています。実際のホスト環境を調査し、適切な修正を適用した上で、堅牢化後もシステムが正常に動作することを確認します。

[LabEx でコースを開始](https://labex.io/ja/courses/linux-security-for-devsecops)

## 演習

|   インデックス | 名前                         | 難易度   | 練習                                                                                                                                                     |
|----------|----------------------------|-------|--------------------------------------------------------------------------------------------------------------------------------------------------------|
|       01 | リスニングサービスの監査               | 初級    | <a target='_blank' href='https://labex.io/ja/labs/linux-audit-listening-services-662167?course=linux-security-for-devsecops'>チャレンジを開始</a>              |
|       02 | 管理インターフェースをローカルホストに制限する    | 初級    | <a target='_blank' href='https://labex.io/ja/labs/linux-restrict-admin-interface-to-localhost-662317?course=linux-security-for-devsecops'>チャレンジを開始</a> |
|       03 | 不要なパブリックポートの削除             | 初級    | <a target='_blank' href='https://labex.io/ja/labs/linux-remove-unnecessary-public-port-662316?course=linux-security-for-devsecops'>チャレンジを開始</a>        |
|       04 | Web ディレクトリリスティングの無効化       | 初級    | <a target='_blank' href='https://labex.io/ja/labs/linux-disable-web-directory-listing-662309?course=linux-security-for-devsecops'>チャレンジを開始</a>         |
|       05 | 公開されたバックアップアーカイブの削除        | 初級    | <a target='_blank' href='https://labex.io/ja/labs/linux-remove-exposed-backup-archive-662313?course=linux-security-for-devsecops'>チャレンジを開始</a>         |
|       06 | 安全でないシークレットファイルの権限を修正する    | 初級    | <a target='_blank' href='https://labex.io/ja/labs/linux-fix-unsafe-secret-file-permissions-662310?course=linux-security-for-devsecops'>チャレンジを開始</a>    |
|       07 | ワールド書き込み可能な Web ディレクトリの修正  | 初級    | <a target='_blank' href='https://labex.io/ja/labs/linux-fix-world-writable-web-directory-662311?course=linux-security-for-devsecops'>チャレンジを開始</a>      |
|       08 | 過剰な権限を持つ sudo ルールの削除       | 中級    | <a target='_blank' href='https://labex.io/ja/labs/linux-remove-over-permissive-sudo-rule-662315?course=linux-security-for-devsecops'>チャレンジを開始</a>      |
|       09 | ハードコードされた認証情報の削除           | 中級    | <a target='_blank' href='https://labex.io/ja/labs/linux-remove-hardcoded-credentials-662314?course=linux-security-for-devsecops'>チャレンジを開始</a>          |
|       10 | root 権限で実行される Cron ジョブの堅牢化 | 中級    | <a target='_blank' href='https://labex.io/ja/labs/linux-harden-root-run-cron-job-662312?course=linux-security-for-devsecops'>チャレンジを開始</a>              |
|       11 | プロセス環境変数のシークレット管理          | 中級    | <a target='_blank' href='https://labex.io/ja/labs/process-env-secret-662282?course=linux-security-for-devsecops'>チャレンジを開始</a>                          |
|       12 | 専用サービスユーザー                 | 中級    | <a target='_blank' href='https://labex.io/ja/labs/dedicated-service-user-662278?course=linux-security-for-devsecops'>チャレンジを開始</a>                      |
|       13 | ログ書き込みの境界設定                | 中級    | <a target='_blank' href='https://labex.io/ja/labs/log-write-boundary-662281?course=linux-security-for-devsecops'>チャレンジを開始</a>                          |
|       14 | デバッグモードのクリーンアップ            | 中級    | <a target='_blank' href='https://labex.io/ja/labs/debug-mode-cleanup-662277?course=linux-security-for-devsecops'>チャレンジを開始</a>                          |
|       15 | アプリケーションポリシーのロックダウン        | 中級    | <a target='_blank' href='https://labex.io/ja/labs/app-policy-lockdown-662275?course=linux-security-for-devsecops'>チャレンジを開始</a>                         |
|       16 | サービス環境ファイル                 | 中級    | <a target='_blank' href='https://labex.io/ja/labs/service-env-file-662284?course=linux-security-for-devsecops'>チャレンジを開始</a>                            |
|       17 | 安全なスクリプトの PATH             | 中級    | <a target='_blank' href='https://labex.io/ja/labs/safe-script-path-662283?course=linux-security-for-devsecops'>チャレンジを開始</a>                            |
|       18 | バックアップパスの境界設定              | 中級    | <a target='_blank' href='https://labex.io/ja/labs/backup-path-boundary-662276?course=linux-security-for-devsecops'>チャレンジを開始</a>                        |
|       19 | 診断エンドポイント                  | 中級    | <a target='_blank' href='https://labex.io/ja/labs/diagnostic-endpoint-662279?course=linux-security-for-devsecops'>チャレンジを開始</a>                         |
|       20 | インシデントバイパスのクリーンアップ         | 上級    | <a target='_blank' href='https://labex.io/ja/labs/incident-bypass-cleanup-662280?course=linux-security-for-devsecops'>チャレンジを開始</a>                     |

## About LabEx

<div align="left"><p><a href="https://labex.io"><strong>LabEx</strong></a> is a <strong>hands-on learning platform for beginners</strong>.</p><p>Explore <a href="https://labex.io/learn/linux"><strong>Linux</strong></a>, <a href="https://labex.io/learn/devops"><strong>DevOps</strong></a>, <a href="https://labex.io/learn/cybersecurity"><strong>Cybersecurity</strong></a>, and <strong>more</strong> — all directly in your browser.</p><p>Learn step by step through <strong>interactive labs</strong>, <strong>guided exercises</strong>, and <strong>real-world projects</strong>. 🌱<br />No setup, no stress — just practice and grow your skills by doing.</p><br /><p><a href="https://apps.apple.com/app/id6765840991"><img src="https://developer.apple.com/assets/elements/badges/download-on-the-app-store.svg" alt="Download on the App Store" height="54" /></a>&nbsp;<a href="https://apps.apple.com/app/id6765840991"><img src="https://developer.apple.com/app-store/marketing/guidelines/images/badge-download-on-the-mac-app-store.svg" alt="Download on the Mac App Store" height="52" /></a></p><br /><p>📖 Need help? Visit our <a href="https://support.labex.io/">Help Center</a> or email info@labex.io</p></div>


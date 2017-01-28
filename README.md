Windows PE イメージを作成するバッチファイル
===

## 使い方
1. Windows ADK for Windows 10 をインストールします
2. [展開およびイメージング ツール環境] を管理者権限で起動します
3. 以下のコマンドを実行すると、``C:\WinPE_amd64\WinPE_amd64.iso`` にイメージファイルが作成されます
```bat
makeWindowsPE.bat
```

## 確認環境
* Windows 10 [Version 10.0.14393]
* Windows ADK for Windows 10 Version 1607
  * https://developer.microsoft.com/ja-jp/windows/hardware/windows-assessment-deployment-kit

## 設定値
* アーキテクチャ
  * amd64
* パッケージ
  * WinPE-Font Support-JA-JP
  * WinPE-RNDIS
  * WinPE-WDS-Tools
  * WinPE-WMI
  * WinPE-NetFX
  * WinPE-Scripting
  * WinPE-PowerShell
  * WinPE-DismCmdlets
  * WinPE-SecureBootCmdlets
  * WinPE-StorageWMI
  * WinPE-SecureStartup
  * WinPE-EnhancedStorage
  * WinPE-LanguagePack-Package
* 言語設定
  * キーボードレイアウト：日本語配列
  * タイムゾーン：東京

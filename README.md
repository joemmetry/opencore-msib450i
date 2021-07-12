# MSI B450I チップセット + AMD Zen2 OpenCore EFI

### [English](https://github.com/joemmetry/opencore-msib450i/blob/master/README.EN.md)

OpenCore ブートローダー用の EFI フォルダー。[OpenCore Vanilla デスクトップガイド](https://khronokernel-2.gitbook.io/opencore-vanilla-desktop-guide/)にて作成されました。

<img src = "https://scontent.fmnl17-2.fna.fbcdn.net/v/t1.6435-9/206743122_10216513288344107_3539624459220602424_n.jpg?_nc_cat=109&_nc_rgb565=1&ccb=1-3&_nc_sid=0debeb&_nc_ohc=GIahA9UCavwAX-0qNjY&_nc_ht=scontent.fmnl17-2.fna&oh=26a8b3847e6d7f8eaf644a7e4826a00f&oe=60F11940" />

### 特徴

- 最新の AMD-OSX パッチ
- 最新 macOS 12 Beta 1 のサポート
- Intel Wi-Fi と Bluetooth は完全に機能しています
- GUI ブートメニューは有効
- トリプルブート（macOS、Windows、Ubuntu）
- Bootcamp は機能します

### ソフトウェアバージョン

- macOS Monterey ベータ 1（21A5248p）
- Windows 11
- Ubuntu 21.04
- OpenCore 0.7.2

### システムコンポーネント

| **コンポーネント** | **モデル**                             |
| ------------------ | -------------------------------------- |
| CPU                | AMD Ryzen 5 3600                       |
| マザーボード       | MSI B450I ゲーミングプラス AC          |
| RAM                | 16GB（2 x 8GB）Corsair Vengeance       |
| オーディオ         | Realtek ALC887 コーデック              |
| GPU                | AMD Radeon RX 580 8GB                  |
| Wi-Fi と Bluetooth | Intel デュアルバンドワイヤレス-AC 3168 |
| イーサネット       | Realtek RTL8111                        |
| OS ディスク（SSD） | ADATA XPG SX8200 PRO 512 PCIe NVMe     |

### 動作可能

CPU、RAM、ファン、クーリングなど ✔<br/>
オーディオ ✔<br/>
イーサネット ✔<br/>
グラフィック ✔<br/>
HDMI ✔<br/>
スリープ/ウェイク機能 ✔<br/>
電力管理 ✔<br/>
App Store ✔<br/>
iMessage ✔<br/>
iCloud ✔<br/>
FaceTime ✔<br/>
USB ✔<br/>
ブートローダー ✔<br/>
HDMI オーディオ ✔<br/>
ボリュームホットキー ✔<br/>
Wi-Fi ✔<br/>
Bluetooth ✔<br/>
ハンドオフ ✔<br/>

### 動作不可能

AirDrop ✗<br/>
サイドカー ✗<br/>
Docker（Docker マシンのみが機能） ✗<br/>

### クイックノート

1.カーネル拡張機能はこのリポジトリに含まれていません。[acidanthera](https://github.com/acidanthera)、[OpenIntelWireless](https://github.com/OpenIntelWireless)、およびその他のプロバイダーにアクセスして、最新のバージョンをダウンロードしてください。<br/>
2.Apple のサポートは制限されているために機能しない macOS ものがいくつかあります。 <br/> 3.このリポジトリは、独自の EFI を構成する方法を学習するためのものです。これをコピーして、EFI パーティションに配置するだけでは、システムが正常に起動されません。<br/>

### ソース

- [OpenCore インストールガイド](https://dortania.github.io/OpenCore-Install-Guide/)
- [AMD Vanilla OpenCore](https://github.com/AMD-OSX/AMD_Vanilla)
- [OpenCore EFI および Kexts](https://dortania.github.io/builds/)

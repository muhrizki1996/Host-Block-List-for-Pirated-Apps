# Host Block List for Pirated Apps
Host Block List Untuk Pengguna Aplikasi Bajakan

--------------------------------------------------------------------------------------------

[![License](https://img.shields.io/github/license/muhrizki1996/Host-Block-List-for-Pirated-Apps)](https://github.com/muhrizki1996/Host-Block-List-for-Pirated-Apps/blob/master/LICENSE)
[![GitHub last commit](https://img.shields.io/github/last-commit/muhrizki1996/Host-Block-List-for-Pirated-Apps)](https://github.com/muhrizki1996/Host-Block-List-for-Pirated-Apps/commits/main)
[![Github file size](https://img.shields.io/github/size/muhrizki1996/Host-Block-List-for-Pirated-Apps/hosts?label=total+size)](https://github.com/muhrizki1996/Host-Block-List-for-Pirated-Apps/blob/master/hosts)

This is my <b>Host Block List File</b> to be used for <b>Pirated</b> or <b>Cracked</b> apps. Example; Adobe Products, Corel, AutoDesk, etc. (EN)

Ini adalah <b>File Daftar Blokir Host</b> digunakan untuk aplikasi <b>Bajakan</b> atau hasil <b>Crack</b>. Contoh; Produk Adobe, Corel, AutoDesk, dll. (ID)

Can be used with (EN) / Bisa digunakan Dengan (ID):
- Microsoft Windows XP
- Microsoft Windows 7
- Microsoft Windows 8.0 / 8.1
- Microsoft Windows 10
- Microsoft Windows 11
- PiHole
- AdGuardHome
- any AdBlock DNS level with same listing method (EN) / semua pemblokir iklan level DNS dengan metode daftar yang sama (ID)

<img src="/img/screenshot.png?raw=true" alt="Host Block List Screenshot" align="center">

> ## How to Use (EN) / Cara Penggunaan (ID)
- (EN) for Windows users: Download latest host file releases,
  go-to: C:\Windows\system32\Drivers\etc\ and then, replace host file with releses version.

  (ID) untuk pengguna Windows: Unduh rilisan file host terbaru,
  pergi-ke: C:\Windows\system32\Drivers\etc\ kemudian, timpa file host dengan versi rilis.
- (EN) for AdBlock users: Copy this URL "https://raw.githubusercontent.com/muhrizki1996/Host-Block-List-for-Pirated-Apps/main/host" and paste to your AdBlock List URL in configuration menu.
  (ID) untuk pengguna pemblokir iklan: salin tautan ini "https://raw.githubusercontent.com/muhrizki1996/Host-Block-List-for-Pirated-Apps/main/host" dan tempelkan pada daftar tautan pemblokir anda di menu konfigurasi.

> ## Sample GIF How-To (EN) / GIF ontoh tata-cara (ID)
- for Windows users (EN) / untuk pengguna Windows (ID):
  <img src="/img/windows.gif?raw=true" alt="Windows" align="center">

- for AdBlock users (EN) / untuk pengguna pemblokir iklan (ID):
<details>
<summary><strong> PiHole </strong></summary>
<br>
  <img src="/img/pihole.gif?raw=true" alt="PiHole" align="center">
</details>

<summary><strong> AdGuardHome </strong></summary>
<br>
  <img src="/img/adguardhome.gif?raw=true" alt="AdGuardHome" align="center">

> ## Additional for Windows and Adobe users (EN) / Tambahan untuk pengguna Windows dan Adobe (ID)
- (EN) Windows + R then type services.msc, stop this 3 services; <b>Adobe Acrobat Update Service</b>, <b>Adobe Genuine Software Integrity Service</b>, and <b>Adobe Genuine Monitor Service</b>.
  Open Windows Power Shell (type Power Shell on Start Menu), then run this command:
  1. Remove-NetFirewallRule -DisplayName "Block Adobe x86 - Genuine"
  2. Remove-NetFirewallRule -DisplayName "Block Adobe - Genuine"
  3. New-NetFirewallRule -DisplayName "Block Adobe x86 - Genuine" -Direction Outbound -Program "C:\Program Files (x86)\Common Files\Adobe" -Action Block
  4. New-NetFirewallRule -DisplayName "Block Adobe - Genuine" -Direction Outbound -Program "C:\Program Files\Common Files\Adobe" -Action Block

- (ID) Tekan pada papan ketik anda kombinasi Windows + R lalu ketikkan services.msc, stop 3 service berikut; <b>Adobe Acrobat Update Service</b>, <b>Adobe Genuine Software Integrity Service</b>, dan <b>Adobe Genuine Monitor Service</b>.
  Buka Windows Power Shell (ketikkan Power Shell pada Start Menu anda), lalu jalankan perintah berikut ini:
  1. Remove-NetFirewallRule -DisplayName "Block Adobe x86 - Genuine"
  2. Remove-NetFirewallRule -DisplayName "Block Adobe - Genuine"
  3. New-NetFirewallRule -DisplayName "Block Adobe x86 - Genuine" -Direction Outbound -Program "C:\Program Files (x86)\Common Files\Adobe" -Action Block
  4. New-NetFirewallRule -DisplayName "Block Adobe - Genuine" -Direction Outbound -Program "C:\Program Files\Common Files\Adobe" -Action Block

--------------------------------------------------------------------------------------------

> ## Credits
[DRSDavidSoft ~ additional-hosts](https://github.com/DRSDavidSoft/additional-hosts/blob/master/domains/blacklist/activation.txt) | [consti ~ host](https://gist.github.com/consti/8022703) | [AndreiGhitan](https://gist.github.com/consti/8022703?permalink_comment_id=3241348#gistcomment-3241348) | [thirumurthy](https://gist.github.com/consti/8022703?permalink_comment_id=3300924#gistcomment-3300924).
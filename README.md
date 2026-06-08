# AterBot ✨

## Kurulum Tamamlandı

**Bot Bilgileri:**
- Bot Adı: afk1
- Sunucu: VadiBox.aternos.me
- Port: 22456

## Başlangıç Adımları

### 1. Bağımlılıkları Yükle
```bash
npm install
```

### 2. Botu Çalıştır
```bash
npm start
```

### 3. Minecraft Sunucusu Ayarları

- Sunucuya bağlan
- Bedrock odası oluştur (5x3x5 önerilir)
- Botu odaya teleport et:
  ```
  /tp afk1 <x> <y> <z>
  ```
- Bot gamemode'unu Creative'e çevir:
  ```
  /gamemode creative afk1
  ```
- Bot **kesinlikle bedrock odası içinde** kalmalı

### 4. Web URL'sini Al

- Konsol çıktısında web URL'sini kopyala
- UptimeRobot'a ekle (5 dakikada bir ping)

## ⚠️ Önemli Uyarılar

- Proje artık bakım görmemektedir
- Aternos AFK oyuncuları sınırlı süre içinde sunucudan atabilir
- Bot escapeverse durumunda playerdata silinmesi gerekebilir
- Şüpheli aktiviteler nedeniyle hesap silinebilir

## Sorun Giderme

**Q: Bot bağlanamıyor?**
- Sunucu adresini ve portu kontrol et (config.json)
- Sunucu çevrimiçi mi kontrol et

**Q: Bot sürekli ayrılıyor?**
- UptimeRobot'un web URL'sini ping'lediğini kontrol et
- Bedrock odasından çıkıp çıkmadığını kontrol et

**Q: "Invalid move player packet"?**
- Sunucu `world/playerdata` klasöründe bot UUID'sini sil
- Sunucuyu yeniden başlat

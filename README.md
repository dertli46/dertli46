- 👋 Hi, I’m @dertli46
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
dertli46/dertli46 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->C# Dilinde oyun kodlamaya çalışıyorum ünity üzerindne.

## VS Code senkronizasyonunu sıfırlama (kısa rehber)

Eğer VS Code ayarlarını/senkronizasyonu sıfırdan başlatmak istiyorsan:

1. VS Code'da `Settings Sync: Turn Off` yap.
2. Komut paletinden `Settings Sync: Reset Synced Data` çalıştır (buluttaki eşitlenmiş veriyi temizler).
3. Gerekirse yerel ayar dosyalarını temizle:
   - **Windows**: `%APPDATA%\\Code\\User`
   - **macOS**: `~/Library/Application Support/Code/User`
   - **Linux**: `~/.config/Code/User`
4. VS Code'u yeniden başlat.
5. İstersen tekrar `Settings Sync: Turn On` ile temiz şekilde başlat.

### Her şey sıfırlandı mı?

`Reset Synced Data` + yerel `User` klasörü temizliği yaptıysan, senkronizasyon verisi ve yerel kullanıcı ayarları sıfırlanmış olur.  
Eklentileri de tamamen sıfırlamak istersen, kurulu extension'ları ayrıca kaldırman gerekir.

# 🪐 Yörünge / Orbit

**Yörünge**, hayatını bir yörünge gibi düzenlemeni sağlayan modern, görsel ve motive edici bir kişisel verimlilik uygulamasıdır.  
Alışkanlıklarını, hedeflerini ve günlük rutinlerini gezegenler gibi etrafında döndürerek takip et.

**Orbit** is a modern, visual and motivational personal productivity app that helps you organize your life like an orbit.  
Track your habits, goals and daily routines as planets revolving around you.

---

## ✨ Özellikler / Features

### Türkçe
- **Yörünge Görselleştirme**: Alışkanlıkların ve hedeflerin gezegen gibi etrafında döner
- **Günlük / Haftalık / Aylık Rutinler**: Tek dokunuşla işaretle
- **Streak (Seri) Sistemi**: Kaç gündür bozmadığını gör
- **Odak Modu**: Pomodoro tarzı zamanlayıcı + yörünge animasyonu
- **İlerleme Analitiği**: Haftalık ve aylık grafikler
- **Karanlık / Aydınlık Tema**: Gece gökyüzü ve gündüz teması
- **Bildirimler**: Yörüngenden sapma, unutma!
- **Widget Desteği**: Ana ekranda yörüngeni gör
- **Çoklu Dil**: Türkçe & İngilizce

### English
- **Orbital Visualization**: Habits and goals revolve around you like planets
- **Daily / Weekly / Monthly Routines**: One-tap check-in
- **Streak System**: See how many days you’ve kept the orbit intact
- **Focus Mode**: Pomodoro-style timer with orbital animation
- **Progress Analytics**: Beautiful weekly & monthly charts
- **Dark / Light Theme**: Night sky & daytime themes
- **Smart Notifications**: Don’t drift out of your orbit
- **Home Screen Widgets**
- **Bilingual**: Turkish & English

---

## 🛠 Teknoloji Stack / Tech Stack

- **Framework**: Flutter 3.x
- **State Management**: Riverpod
- **Local Database**: Hive / Isar
- **Animations**: Rive + Custom Painters (orbital paths)
- **Charts**: fl_chart
- **Notifications**: flutter_local_notifications
- **Architecture**: Clean Architecture + Feature-first

---

## 📱 Ekran Görüntüleri / Screenshots

> *(Buraya ekran görüntülerini ekle)*

| Ana Ekran / Home | Yörünge Detay / Orbit Detail | Analitik / Analytics |
|------------------|------------------------------|----------------------|
| ![Home](screenshots/home.png) | ![Detail](screenshots/detail.png) | ![Stats](screenshots/stats.png) |

---

## 🚀 Kurulum / Getting Started

### Gereksinimler / Requirements
- Flutter SDK 3.16 veya üzeri
- Dart 3.2+
- Android Studio / VS Code
- iOS için Xcode (macOS)

### Adımlar / Steps

```bash
# 1. Repoyu klonla
git clone https://github.com/KULLANICI_ADIN/yorunge.git
cd yorunge

# 2. Bağımlılıkları yükle
flutter pub get

# 3. Uygulamayı çalıştır
flutter run

# 1. Gün: ROS2 Giriş ve Kurulum 🚀

## 🎯 Günün Hedefleri
- ROS2 mimarisini anlamak.
- Ubuntu 22.04 üzerine ROS2 Humble kurulumu.
- Talker/Listener testi.

## 📝 Öğrendiklerim
ROS2 (Robot Operating System), robot parçalarının birbiriyle konuşmasını sağlayan bir ara katman yazılımıdır. Node'lar (Düğümler) aracılığıyla iletişim kurulur.

## 🛠️ Kurulum Notları
1. **Locale Ayarları:** UTF-8 desteği kontrol edildi.
2. **Sources:** ROS2 repository'si sisteme eklendi.
3. **Kurulum:** `ros-humble-desktop` paketi kuruldu.
4. **Ortam Ayarı:** `.bashrc` dosyasına `source /opt/ros/humble/setup.bash` eklendi.

## ✅ Test
Talker ve Listener demo node'ları çalıştırıldı ve başarılı bir şekilde haberleştikleri görüldü.
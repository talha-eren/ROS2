# 🚀 ROS 2 - Ders 2: Launch Dosyaları

## 📖 Proje Hakkında
Bu projede, tek tek terminaller açmak yerine **ROS 2 Launch** sistemini kullanarak birden fazla düğümü (node) tek komutla yönetmeyi öğrendim. 

Konuşan (`talker`) ve dinleyen (`listener`) robotları bir orkestra şefi gibi aynı anda başlattık.

## 🛠️ Öğrenilen Kavramlar
* **Launch Files (.launch.py):** Düğümleri başlatma senaryoları.
* **LaunchDescription:** Başlatılacak öğelerin listesi.
* **Setup.py:** Launch dosyalarının sisteme tanıtılması.

## ⚡ Nasıl Çalıştırılır?

Projeyi derlemek ve başlatmak için sırasıyla şu komutları kullanın:

1. **İnşa Et (Build):**
   ```bash
   colcon build

2. **Kaynak Göster (Source):**

   ```bash
   source install/setup.bash

3. **Başlat (Launch):**

   ```bash
   ros2 launch ikinci_ders ikinci_ders.launch.py

*Bu depo, çalışmalarıma ait kaynak kodları ve yapı çıktılarıyla birlikte günlük ilerlememin kaydıdır.*


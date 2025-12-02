# 🤖 ROS 2 Öğrenme Yolculuğum

Bu depo, Robot İşletim Sistemi (ROS 2 Humble) öğrenme sürecimdeki projelerimi, aldığım notları ve geliştirdiğim kodları barındırmaktadır.

Sıfırdan başlayarak adım adım ilerlediğim bu serüvende, karmaşık robotik kavramlarını basit örneklerle uygulayarak pekiştiriyorum.

## 🇹🇷 Dil ve Kaynak Notu

**Bu projedeki tüm dokümantasyon, kod yorumları ve ders notları Türkçe olarak hazırlanmıştır.** Amacım, hem kendi öğrendiklerimi ana dilimde pekiştirmek hem de Türkçe ROS 2 kaynağı arayanlara örnek teşkil etmektir.

## 📂 Ders İçerikleri

Şu ana kadar tamamladığım bölümler:

### [Ders 1: Temeller ve İletişim](./ilk_paketim)
* **Konular:** ROS 2 Kurulumu, Workspace mantığı, Node, Topic, Mesajlaşma.
* **Uygulama:** Python ile basit bir Yayıncı (Talker) ve Abone (Listener) geliştirilmesi.
* **Görselleştirme:** `rqt_graph` kullanımı.

### [Ders 2: Launch Sistemleri](./ikinci_ders)
* **Konular:** Çoklu düğüm yönetimi, Launch dosyaları (.launch.py), Parametre yapıları.
* **Uygulama:** Tek komutla tüm sistemi (Talker + Listener) ayağa kaldıran orkestra şefi dosyasının yazılması.

## 🛠️ Kurulum ve Çalıştırma

Bu projeleri kendi bilgisayarınızda denemek isterseniz:

1.  **Gereksinimler:**
    * Ubuntu 22.04 LTS
    * ROS 2 Humble Hawksbill

2.  **Repoyu Klonlayın:**
    ```bash
    git clone https://github.com/talha-eren/ROS2.git
    cd ROS2
    ```

3.  **Derleyin ve Başlatın:**
    ```bash
    colcon build
    source install/setup.bash
    ```

---
*Bu yolculuk devam ediyor... Yeni dersler eklendikçe güncellenecektir.* 🚀
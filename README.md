# 🎬 WatchOPedia

## 📖 İçindekiler
- [🌟 Proje Hakkında](#-proje-hakkında)
- [🚀 Özellikler](#-özellikler)
- [🛠️ Teknolojiler](#️-teknolojiler)
- [📁 Proje Yapısı](#-proje-yapısı)
- [🏁 Başlangıç](#-başlangıç)
- [🖥️ Kullanım](#️-kullanım)
- [🌐 Çoklu Dil Desteği](#-çoklu-dil-desteği)
- [🎨 Özelleştirme](#-özelleştirme)
- [🤝 Katkıda Bulunma](#-katkıda-bulunma)
- [📄 Lisans](#-lisans)

## 🌟 Proje Hakkında

WatchOPedia, film tutkunları için geliştirilmiş interaktif bir web uygulamasıdır. Kullanıcılar, kişisel film koleksiyonlarını oluşturabilir, yönetebilir ve keşfedebilirler. Modern ve kullanıcı dostu arayüzü ile film deneyiminizi zenginleştirir.

## 🚀 Özellikler

- 📝 Film ekleme ve listeleme
- 🔍 Film arama
- 📊 Film detaylarını görüntüleme
- ⭐ Film puanlama sistemi
- 🌍 Çoklu dil desteği (Türkçe ve İngilizce)
- 🎲 Eğlenceli sayaç özelliği

## 🛠️ Teknolojiler

- ⚛️ React
- 🅱️ Bootstrap
- 🌐 i18next (çoklu dil desteği için)
- 💅 CSS (özel stiller için)

## 📁 Proje Yapısı

WATCHOPEDIA
├── public/
│ ├── locales/
│ │ ├── en/
│ │ └── tr/
│ └── index.html
├── src/
│ ├── components/
│ ├── images/
│ ├── styles/
│ ├── utils/
│ ├── App.js
│ └── index.js
├── package.json
└── README.md


## 🏁 Başlangıç

Projeyi yerel makinenizde çalıştırmak için:

1. Repoyu klonlayın:
   ```
   git clone https://github.com/kullaniciadi/watchopedia.git
   ```
2. Proje dizinine gidin:
   ```
   cd watchopedia
   ```
3. Bağımlılıkları yükleyin:
   ```
   npm install
   ```
4. Uygulamayı başlatın:
   ```
   npm start
   ```

## 🖥️ Kullanım

- 🎥 Film Ekleme: "Add Movie" formunu kullanarak yeni filmler ekleyin.
- 🔎 Film Arama: Arama çubuğunu kullanarak filmleri filtreleyebilirsiniz.
- 📜 Film Detayları: Film kartlarındaki "Details" butonuna tıklayarak film detaylarını görüntüleyin.
- ⭐ Film Puanlama: Her film için yıldız simgelerini kullanarak puan verin.
- 🔢 Sayaç: Eğlenceli sayaç özelliğini kullanarak sayıyı artırıp azaltın.

## 🌐 Çoklu Dil Desteği

WatchOPedia, Türkçe ve İngilizce dillerini destekler. Dil değiştirmek için:

1. Sayfanın üst kısmındaki dil butonlarını kullanın (TR / EN).
2. Seçtiğiniz dile göre uygulama anında güncellenecektir.

## 🎨 Özelleştirme

- 🎭 Tema: `public/index.html` dosyasındaki CSS değişkenlerini düzenleyerek temayı özelleştirebilirsiniz.
- 🔤 Metinler: `public/locales` klasöründeki JSON dosyalarını düzenleyerek çevirileri güncelleyebilirsiniz.

## 🤝 Katkıda Bulunma

Katkılarınızı memnuniyetle karşılıyoruz! Lütfen:

1. Projeyi forklayın
2. Yeni bir branch oluşturun (`git checkout -b feature/AmazingFeature`)
3. Değişikliklerinizi commit edin (`git commit -m 'Add some AmazingFeature'`)
4. Branch'inizi push edin (`git push origin feature/AmazingFeature`)
5. Bir Pull Request oluşturun

## 📄 Lisans

Bu proje [MIT Lisansı](https://opensource.org/licenses/MIT) altında lisanslanmıştır.

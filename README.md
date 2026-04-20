## Laravel Blade Zimmet Formu Şablonu

Bu dosya, Laravel Blade kullanılarak hazırlanmış yazdırılabilir bir zimmet formu şablonudur. Amaç; personele teslim edilen cihaz, aksesuar ve ilişkili bileşenlerin tek bir kurumsal form üzerinde listelenmesi, teslim ve iade süreçlerinin kayıt altına alınmasıdır.

### Şablonun İçeriği
- Kurum bilgileri
- Personel bilgileri
- Departman ve yönetici bilgisi
- Kullanıcıya atanmış cihazlar
- Kullanıcıya atanmış aksesuarlar
- Asset ilişkili bileşen / uygulama / grup bilgileri
- Teslim beyan metni
- Teslim ve iade imza alanları
- Hasar / eksik ürün not alanı

### Teknik Yapı
Şablon, Blade üzerinden dinamik verilerle çalışır. Kullanıcı, asset, accessory, component, department ve manager gibi ilişkili veriler doğrudan form üzerinde gösterilir. CSS tarafında A4 sayfa yapısı ve tablo düzeni kullanılarak çıktıya uygun sade bir tasarım uygulanmıştır.

### Kullanım Amacı
Bu yapı özellikle aşağıdaki süreçlerde kullanılabilir:
- IT zimmet teslimi
- Personel cihaz teslim formu
- İade süreçlerinin kayıt altına alınması
- Kurumsal demirbaş takibi
- İç denetim ve arşivleme

### Notlar
- Logo alanı örnek bırakılmıştır, projeye göre güncellenmelidir.
- Şirket adı ve adres bilgileri dummy veri olarak yazılmıştır.
- Veri ilişkileri mevcut proje modeline göre uyarlanmalıdır.
- Boş satır üretimi yapılan kısım geliştirmeye açıktır.

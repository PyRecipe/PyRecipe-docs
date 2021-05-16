# Kurulum

!> PyRecipe şu anda geliştirme aşamasındadır bu sebeple kurulum, geliştirme ortamına göre anlatılmaktadır.

## Gereksinimler

- Python 3 veya daha yenisi
- Django

## Kurulum Adımları

Geliştirme ortamınızı hazırladıktan sonra bu adımları takip edebilirsiniz.

### 1) Projenizi güncellemeyi unutmayın:

Main branchi üzerinde `git pull` komutu ile yapılan son değişikleri projenize uygulayabilirsiniz.

### 2) Geliştirme ortamınızın gereksinimleri karşıladığından emin olun:

Eğer projenizi pipenv ile kullanıyorsanız `pipenv install` komutu ile kolayca gerekli olan Python kütüphanelerini kurabilirisiniz.

### 3) Migrationların kurulumunu yapın:

`python manage.py migrate`  komutu ile mevcut olan migrationların kurulumunu sağlayın.

?> _NOT:_ `python` komutu kullandığınız Python versiyonuna göre değişiklik gösterebilir. Bu komuttan kasıt en güncel Python 3 sürümüdür. Eğer cihazınız `python` komutu ile Python 2'yi çalıştırıyorsa `python3` komutunu deneyebilirsiniz.

### 4) Super User oluşturun:

`python manage.py createsuperuser` komutu ile admin paneline giriş yapabileceğiniz bir kullanıcı oluşturun. Projenizi geliştirme ortamında kullanmayı planlıyorsanız admin kullanıcısının güvenliğine önem vermeniz gerekmez.

### 5) Projeyi çalıştırın:

`python manage.py runserver` komutu ile projeyi çalıştırın. Eğer bir sorun yaşamazsanız, kurulum aşamasını doğru yapmışsınız demektir.

# Git 

## Git Nedir?
### Ücretsiz ve açık kaynaklı bir versiyon kontrol sistemidir.

## Versiyon Kontrol Nedir?
### Dökümanların, Bilgisayar programlarının, Büyük web sitelerinin ve diğer bilgi koleksiyonlarındaki değişimlerin (değişliklerinin) yönetimidir.

## Kurulum
winget install --id Git.Git -e --source winget (PowerShell)
apt-get install git (Linux/Mac)

| Komutlar | Açıklamalar |
| --- | --- |
| git clone | Github gibi uzak konumda tutulan depoyu yerel dizininize getirir. |
| git add | Dosylarınızı değişimlerini izlemek için Git e ekler. |
| git commit | Dosyalarınızı Git e kaydeder. |
| git push | Deponuzu uzak depo konumuna gönderir. | 
| git pull | Uzak konumdaki son değişiklikleri yerel konuma indirir. |
| git init | Yerelde bir depo oluşturur. |
| ssh-keygen | ssh anahtarı oluşturur.|
| git branch | Gitteki şubeleri gösterir. |
| git branch -d branch_name | branch_name i siler. |
| git checkout -b branch_name | Git'e branch_name adındaki yeni bir şube açar. |
| git checkout branch_name | branch_name adlı şubeyi aktif hali getirir. |
| git diff | Git'teki değişiklikleri satır satır gösterir. |
| git remote add r_name r_link | r_name adında r_link uzak depo bağlantısını kaydeder. |
| git remote remove r_name | r_name adındaki uzak depo bağlantısını siler. |
| git status | Git'teki dosyaların son durumunu (değişiklik, silme, ekleme) gösterir. |
| git log | Git'te yapılan son commitleri gösterir. |


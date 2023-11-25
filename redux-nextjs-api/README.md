## 1- Yeni bir react ve NextJs uygulaması oluşturmak 

Yeni bir proje oluşturmak için:

-"npx create next-app " komutu tterminalde çalıştırılır.
-Tailwind haricindeki bütün seçenekler "No" diyerek geçilebilir.(Tercihen)


## 2-NextJS Template nın temizlenmesi.

Silinecek olan klasör / dosya satırlar şu şekildedir:

pages > api klasörü
-styles > globals.css içerisinde @tailwind şeklinde başlayan satırlar hariçindeki diğer satırşar silinecek.

-pages > index.js altındaki bütün import silinir.(export default üstündeki tüm satırlar silinir) ve return () içiresindeki temizlenir.

return () boş etikete açılır (<>  </>)

JSX gösteriminde return içerisinde bütün HTML elemanlarını kapsayan bir etiket olmak zorundadır.


return (
       <> 
        <h2>Selam</h2>
        <span>Selam</span>
    </>
)

## 3-Proje ayağa kaldırılması.

Proje ayağa kaldırmak için 

npm run dev komutu terminale yazılır.


## 4
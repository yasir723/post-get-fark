# POST ile GET Arasındaki Fark

GET ve POST, web sayfalarında form verilerini sunucuya iletmek için kullanılan iki farklı yöntemdir. GET ile gönderilen veriler URL'nin bir parçası olarak görünürken, `POST ile gönderilen veriler gizli kalır`. GET ile gönderilen verilerin güvenliği daha düşüktür çünkü URL'ye eklendikleri için kullanıcı adı, şifre gibi hassas bilgileri içermemelidirler. POST, verileri HTTP isteğinin gövdesinde gönderdiği için daha güvenlidir ve hassas bilgilerin gönderilmesi için tercih edilir. `GET ile gönderilen veri boyutu sınırlıdır`, POST ise daha büyük veri kümelerini göndermek için daha uygundur. `GET, veri almak için` kullanılırken, `POST, veri göndermek için` kullanılır.

<div align="center">
        <img src="https://github.com/yasir723/istemci-sunucu-iletisimi/assets/111686779/5b7d9bc2-cc5d-472f-998c-dfc6fbfdb08c">
</div>


- ### Get İle Gönderilen Bilgiler 
    Örneğin:
    ```plaintext
     http://example.com/login?username=ali&password=123
    ```
    Bu URL'de, http://example.com/login adresine username=ali ve password=123 parametreleri eklenmiştir. Bu parametreler GET yöntemiyle sunucuya iletilir. Ancak, bu şekilde hassas bilgilerin (örneğin, şifre) açıkça URL'de görünmesi güvenlik riski oluşturabilir.

    __Test aşamasında, URL'yi kontrol etmek yerine, daha kapsamlı bilgileri sağlayan `Sağ Tıklayıp` -> `İncele` -> `Ağ` -> `Başlık` kısmındaki bilgilere odaklanacağız__

    Belirli bir siteye ilk girdiğimizde eğer ağ bilgilerine bakarsak `get` olarak gönderildiğini göreceğiz
    <div align="center" >
        <img src="https://github.com/yasir723/istemci-sunucu-iletisimi/assets/111686779/ca1dfef2-bc84-423c-a0db-3002b96796bf">
    </div>

    <br></br>
    Örneğin, kullanıcı adı olarak 'giriş' ve şifre olarak '123' girerek bir veri gönderdiğimizde, bu bilgilerin ağ kısmında `POST` olarak görünecektir
    <div align="center">
        <img src="https://github.com/yasir723/istemci-sunucu-iletisimi/assets/111686779/bae15ad0-bcf3-4e14-85da-eb11c47bbd55">
    </div>
    
   





    

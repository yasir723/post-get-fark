# POST ile GET Arasındaki Fark

GET ve POST, web sayfalarında form verilerini sunucuya iletmek için kullanılan iki farklı yöntemdir. GET ile gönderilen veriler URL'nin bir parçası olarak görünürken, `POST ile gönderilen veriler gizli kalır`. GET ile gönderilen verilerin güvenliği daha düşüktür çünkü URL'ye eklendikleri için kullanıcı adı, şifre gibi hassas bilgileri içermemelidirler. POST, verileri HTTP isteğinin gövdesinde gönderdiği için daha güvenlidir ve hassas bilgilerin gönderilmesi için tercih edilir. `GET ile gönderilen veri boyutu sınırlıdır`, POST ise daha büyük veri kümelerini göndermek için daha uygundur. `GET, veri almak için` kullanılırken, `POST, veri göndermek için` kullanılır.

<div align="center">
        <img src="https://github.com/yasir723/post-get-fark/assets/111686779/a92ad855-7111-41de-82cd-0db45876c043" width=900>
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
        <img src="https://github.com/yasir723/post-get-fark/assets/111686779/ebe9d4d9-f4a5-4862-97f0-611d3262d919">
    </div>

    <br></br>
    Örneğin, kullanıcı adı olarak 'giriş' ve şifre olarak '123' girerek bir veri gönderdiğimizde, bu bilgilerin ağ kısmında `POST` olarak görünecektir
    <div align="center">
        <img src="https://github.com/yasir723/post-get-fark/assets/111686779/748ed238-1d40-4e2c-8d33-10a37786e289">
    </div>
    
   





    

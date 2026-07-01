# Banka.VPOS
[![Nuget download](https://img.shields.io/nuget/dt/Banka.VPOS)](https://www.nuget.org/packages/Banka.VPOS) [![Nuget v2](https://img.shields.io/nuget/v/Banka.VPOS)](https://www.nuget.org/packages/Banka.VPOS) ![build](https://img.shields.io/github/actions/workflow/status/cempehlivan/Banka.VPOS/dotnet.yml?branch=master) [![GitHub license](https://img.shields.io/github/license/cempehlivan/Banka.VPOS)](https://github.com/cempehlivan/Banka.VPOS/blob/master/LICENSE)



## Banka.VPOS: Sanal Pos Entegrasyonlarını Basitleştirin

Banka.VPOS, Türkiye'deki birçok bankanın sanal pos entegrasyonlarını tek bir kod tabanı ile kullanmayı mümkün kılan .NET kütüphanesidir. Bu sayede geliştiriciler, her banka için ayrı ayrı kod yazmak zorunda kalmadan, tüm sanal pos işlemlerini tek bir kütüphane üzerinden gerçekleştirebilirler.

## Kütüphanenin Özellikleri

+ **Tek Kod Tabanı:** Farklı bankaların sanal pos entegrasyonları için ayrı ayrı kod yazmaya gerek kalmadan, tek bir kod tabanı ile tüm işlemleri gerçekleştirebilirsiniz.
+ **Basitleştirilmiş İşlem Akışı:** Sanal pos işlemleri için gerekli tüm adımlar kütüphane tarafından otomatik olarak halledilir. Bu sayede kod yazma süreci oldukça basitleşir.
+ **3D Güvenli Ödeme Desteği:** 3D Güvenli Ödeme işlemleri için gerekli tüm adımlar kütüphane tarafından desteklenir.
+ **Geniş Banka Kapsamı:** Akbank, Alternatif Bank, Anadolubank, Denizbank, QNB Finansbank, Finansbank Nestpay, Garanti BBVA, Halkbank, ING Bank, İş Bankası, Şekerbank, TEB, Türkiye Finans, Vakıfbank, Yapı Kredi ve Ziraat Bankası gibi birçok banka ile birlikte, Iyzico ve Sipay gibi ödeme kuruluşlarının da sanal pos entegrasyonları kütüphanede yer alır.
+ **.NET Uyumluluğu:** Kütüphane, .NET Framework, .NET Core ve .NET MAUI da dahil olmak üzere tüm .NET sürümleriyle tam uyumludur. Bu sayede farklı projelerde kolayca entegre edilerek kullanılabilir.

## Sürüm Notları

Son değişiklikler için: [CHANGELOG.md](CHANGELOG.md)

## Kütüphaneyi Nasıl Kullanabilirsiniz?
Banka.VPOS kütüphanesini NuGet paket yöneticisi aracılığıyla projenize ekleyebilirsiniz. Kütüphanenin kullanımıyla ilgili aşağıda bulunan kod örneklerine göz atabilirsiniz.

[https://www.nuget.org/packages/Banka.VPOS](https://www.nuget.org/packages/Banka.VPOS)

Package Manager:

> Install-Package Banka.VPOS

Dotnet CLI
> dotnet add package Banka.VPOS


## Kullanılabilir Sanal POS'lar

![ss](https://raw.githubusercontent.com/cempehlivan/Banka.VPOS/master/bankalar.png)

| Sanal POS | Satış | Satış 3D | İptal | İade  |
| --------- | :---: | :------: | :---: | :---: |
| Akbank | ✔️ | ✔️ | ✔️ | ✔️ |
| Akbank Nestpay | ✔️ | ✔️ | ✔️ | ✔️ |
| Alternatif Bank | ✔️ | ✔️ | ✔️ | ✔️ |
| Anadolubank | ✔️ | ✔️ | ✔️ | ✔️ |
| Denizbank | ✔️ | ✔️ | ✔️ | ✔️ |
| QNB Finansbank | ✔️ | ✔️ | ✔️ | ✔️ |
| Finansbank Nestpay | ✔️ | ✔️ | ✔️ | ✔️ |
| Garanti BBVA | ✔️ | ✔️ | ❌ | ❌ |
| Halkbank | ✔️ | ✔️ | ✔️ | ✔️ |
| ING Bank | ✔️ | ✔️ | ✔️ | ✔️ |
| İş Bankası | ✔️ | ✔️ | ✔️ | ✔️ |
| Şekerbank | ✔️ | ✔️ | ✔️ | ✔️ |
| Türk Ekonomi Bankası | ✔️ | ✔️ | ✔️ | ✔️ |
| Türkiye Finans | ✔️ | ✔️ | ✔️ | ✔️ |
| Vakıfbank | ✔️ | ✔️ | ✔️ | ✔️ |
| Yapı Kredı Bankası | ✔️ | ✔️ | ❌ | ❌ |
| Ziraat Bankası | ✔️ | ✔️ | ✔️ | ✔️ |
| Cardplus | ✔️ | ✔️ | ✔️ | ✔️ |
| Paratika | ✔️ | ✔️ | ✔️ | ✔️ |
| Payten - MSU | ✔️ | ✔️ | ✔️ | ✔️ |
| Iyzico | ✔️ | ✔️ | ✔️ | ✔️ |
| Sipay | ✔️ | ✔️ | ✔️ | ✔️ |
| QNBpay | ✔️ | ✔️ | ✔️ | ✔️ |
| ParamPos | ✔️ | ✔️ | ✔️ | ✔️ |
| PayBull | ✔️ | ✔️ | ✔️ | ✔️ |
| Parolapara | ✔️ | ✔️ | ✔️ | ✔️ |
| IQmoney | ✔️ | ✔️ | ✔️ | ✔️ |
| Ahlpay | ✔️ | ✔️ | ✔️ | ✔️ |
| Moka | ✔️ | ✔️ | ✔️ | ✔️ |
| Vepara | ✔️ | ✔️ | ✔️ | ✔️ |
| ZiraatPay | ✔️ | ✔️ | ✔️ | ✔️ |
| VakıfPayS | ✔️ | ✔️ | ✔️ | ✔️ |
| Tami | ✔️ | ✔️ | ✔️ | ✔️ |
| HalkÖde | ✔️ | ✔️ | ✔️ | ✔️ |
| Kuveyt Türk | ✔️ | ✔️ | ❌ | ❌ |
| Vakıf Katılım | ✔️ | ✔️ | ❌ | ❌ |
| PayNKolay | ✔️ | ✔️ | ✔️ | ✔️ |
| Paynet | ✔️ | ✔️ | ✔️ | ✔️ |



# Dokümanlar

Detaylı dokümanlara [https://www.vpos.com.tr/docs](https://www.vpos.com.tr/docs) adresinden ulaşabilirsiniz.

## API Bilgilerinin ayarlanması - `VirtualPOSAuth` Class'ı

Alan açıklamaları:

| Alan | Tür | Açıklama |
| ---- | --- | -------- |
| `bankCode` | `string` | Hangi banka entegrasyonunun kullanılacağının belirlendiği alandır. Banka kodlarının belirlenmesinde, bankaların global EFT kodları kullanılmıştır. 4 haneli olarak girilmelidir. Örneğin; Akbank global EFT kodu `46` dır. Akbank Sanal POS entegrasyonunu kullanmak için `0046` girilmelidir. Veya [Banka.VPOS.Services.BankService](./Banka.VPOS/Services/BankService.cs) Enum Class'ı kullanılabilir. Örneğin: `Banka.VPOS.Services.BankService.Akbank` |
| `merchantID` | `string` | Firma kodu |
| `merchantUser` | `string` | API kullanıcı adı |
| `merchantPassword` | `string` | API kullanıcı şifre |
| `merchantStorekey` | `string` | Bazı bankalar için 3D store key |
| `testPlatform` | `boolean` | Ortam bilgisi. Sanal POS Test ortamı için `true` gönderilmelidir. |


Sanal POS bazlı alan açıklamaları:

| Sanal POS | bankCode | merchantID | merchantUser | merchantPassword | merchantStorekey |
| --------- | -------- | ---------- | ------------ | ---------------- | ---------------- |
| Akbank | Banka.VPOS.Services.BankService.Akbank | İş Yeri No | Güvenli İşyeri Numarası (merchantSafeId) | Terminal Safe ID | Güvenlik Anahtarı (Secret Key) |
| Akbank Nestpay | Banka.VPOS.Services.BankService.AkbankNestpay | Mağaza Kodu | Api Kullanıcısı Adı | Api Kullanıcısı Şifre | 3D Storekey (Üye İş Yeri Anahtarı) |
| Alternatif Bank | Banka.VPOS.Services.BankService.AlternatifBank | Mağaza Kodu | Api Kullanıcısı Adı | Api Kullanıcısı Şifre | 3D Storekey (Üye İş Yeri Anahtarı) |
| Anadolubank | Banka.VPOS.Services.BankService.Anadolubank | Mağaza Kodu | Api Kullanıcısı Adı | Api Kullanıcısı Şifre | 3D Storekey (Üye İş Yeri Anahtarı) |
| Denizbank | Banka.VPOS.Services.BankService.Denizbank | Mağaza Kodu | Api Kullanıcısı Adı | Api Kullanıcısı Şifre | 3D Storekey (Üye İş Yeri Anahtarı) |
| QNB Finansbank | Banka.VPOS.Services.BankService.QNBFinansbank | Üye İşyeri Kodu | Api Kullanıcısı Adı | Api Kullanıcısı Şifre | Üye İşyeri Şifre |
| Finansbank Nestpay | Banka.VPOS.Services.BankService.FinansbankNestpay | Mağaza Kodu | Api Kullanıcısı Adı | Api Kullanıcısı Şifre | 3D Storekey (Üye İş Yeri Anahtarı) |
| Garanti BBVA | Banka.VPOS.Services.BankService.GarantiBBVA | Firma Kodu | Terminal No | `PROVAUT` kullanıcısı şifresi | 3D secure anahtarı |
| Halkbank | Banka.VPOS.Services.BankService.Halkbank | Mağaza Kodu | Api Kullanıcısı Adı | Api Kullanıcısı Şifre | 3D Storekey (Üye İş Yeri Anahtarı) |
| ING Bank | Banka.VPOS.Services.BankService.INGBank | Mağaza Kodu | Api Kullanıcısı Adı | Api Kullanıcısı Şifre | 3D Storekey (Üye İş Yeri Anahtarı) |
| İş Bankası | Banka.VPOS.Services.BankService.IsBankasi | Mağaza Kodu | Api Kullanıcısı Adı | Api Kullanıcısı Şifre | 3D Storekey (Üye İş Yeri Anahtarı) |
| Şekerbank | Banka.VPOS.Services.BankService.Sekerbank | Mağaza Kodu | Api Kullanıcısı Adı | Api Kullanıcısı Şifre | 3D Storekey (Üye İş Yeri Anahtarı) |
| Türk Ekonomi Bankası | Banka.VPOS.Services.BankService.TurkEkonomiBankasi | Mağaza Kodu | Api Kullanıcısı Adı | Api Kullanıcısı Şifre | 3D Storekey (Üye İş Yeri Anahtarı) |
| Türkiye Finans | Banka.VPOS.Services.BankService.TurkiyeFinans | Mağaza Kodu | Api Kullanıcısı Adı | Api Kullanıcısı Şifre | 3D Storekey (Üye İş Yeri Anahtarı) |
| Vakıfbank | Banka.VPOS.Services.BankService.Vakifbank | Üye İşyeri Numarası | POS No | Api Şifresi | |
| Yapı Kredı Bankası | Banka.VPOS.Services.BankService.YapiKrediBankasi | Firma Kodu | Terminal No | Pos Net ID | ENCKEY |
| Ziraat Bankası | Banka.VPOS.Services.BankService.ZiraatBankasi | Mağaza Kodu | Api Kullanıcısı Adı | Api Kullanıcısı Şifre | 3D Storekey (Üye İş Yeri Anahtarı) |
| Cardplus | Banka.VPOS.Services.BankService.Cardplus | Mağaza Kodu | Api Kullanıcısı Adı | Api Kullanıcısı Şifre | 3D Storekey (Üye İş Yeri Anahtarı) |
| Paratika | Banka.VPOS.Services.BankService.Paratika | Firma Kodu | Api Kullanıcısı Adı | Api Kullanıcısı Şifre | |
| Payten - MSU | Banka.VPOS.Services.BankService.Payten | Firma Kodu | Api Kullanıcısı Adı | Api Kullanıcısı Şifre | |
| Iyzico | Banka.VPOS.Services.BankService.Iyzico | Üye İşyeri Numarası | API Anahtarı | Güvenlik Anahtarı | |
| Sipay | Banka.VPOS.Services.BankService.Sipay | Üye İşyeri ID | Uygulama Anahtarı | Uygulama Parolası | Üye İşyeri Anahtarı |
| QNBpay | Banka.VPOS.Services.BankService.QNBpay | Üye İşyeri ID | Uygulama Anahtarı | Uygulama Parolası | Üye İşyeri Anahtarı |
| ParamPos | Banka.VPOS.Services.BankService.ParamPos | Terminal No (Client Code) | Kullanıcı Adı | Şifre | Anahtar (Guid) |
| PayBull | Banka.VPOS.Services.BankService.PayBull | Üye İşyeri ID | Uygulama Anahtarı | Uygulama Parolası | Üye İşyeri Anahtarı |
| Parolapara | Banka.VPOS.Services.BankService.Parolapara | Üye İşyeri ID | Uygulama Anahtarı | Uygulama Parolası | Üye İşyeri Anahtarı |
| IQmoney | Banka.VPOS.Services.BankService.IQmoney | Üye İşyeri ID | Uygulama Anahtarı | Uygulama Parolası | Üye İşyeri Anahtarı |
| Ahlpay | Banka.VPOS.Services.BankService.Ahlpay | member Id | Api Kullanıcısı Adı | Api Kullanıcısı Şifre | Üye işyeri API Key (hashPassword) |
| Moka | Banka.VPOS.Services.BankService.Moka | Bayi Kodu | Api Kullanıcısı Adı | Api Kullanıcısı Şifre | |
| Vepara | Banka.VPOS.Services.BankService.Vepara | Üye İşyeri ID | Uygulama Anahtarı | Uygulama Parolası | Üye İşyeri Anahtarı |
| ZiraatPay | Banka.VPOS.Services.BankService.ZiraatPay | Firma Kodu | Api Kullanıcısı Adı | Api Kullanıcısı Şifre | |
| VakıfPayS | Banka.VPOS.Services.BankService.VakifPayS | Firma Kodu | Api Kullanıcısı Adı | Api Kullanıcısı Şifre | |
| Tami | Banka.VPOS.Services.BankService.Tami | Üye İşyeri No | Terminal No | `KidValue` + "\|" + `KValue` | Secret Key |
| HalkÖde | Banka.VPOS.Services.BankService.HalkOde | Üye İşyeri ID | Uygulama Anahtarı | Uygulama Parolası | Üye İşyeri Anahtarı |
| Kuveyt Türk | Banka.VPOS.Services.BankService.KuveytTurk | MerchantId | UserName | Password | CustomerId |
| Vakıf Katılım | Banka.VPOS.Services.BankService.VakifKatilim | MerchantId | UserName | Password | CustomerId |
| PayNKolay | Banka.VPOS.Services.BankService.PayNKolay | sx (Token) | sx list | sx iptal | Merchant Secret Key |
| Paynet | Banka.VPOS.Services.BankService.Paynet | Bayi Kodu | Publishable Key | Secret Key | |


## 3D'siz Direkt Satış İşlemi

`payment3D.confirm = false` gönderilmesi halinde 3D'siz çekim işlemi yapılır ve direkt olarak nihai sonucu döner. 


```csharp
VirtualPOSAuth _qnbPayTest = new VirtualPOSAuth
{
    bankCode = Banka.VPOS.Services.BankService.QNBpay,
    merchantID = "20158",
    merchantUser = "07fb70f9d8de575f32baa6518e38c5d6",
    merchantPassword = "61d97b2cac247069495be4b16f8604db",
    merchantStorekey = "$2y$10$N9IJkgazXMUwCzpn7NJrZePy3v.dIFOQUyW4yGfT3eWry6m.KxanK",
    testPlatform = true
};

CustomerInfo customerInfo = new CustomerInfo
{
	taxNumber = "1111111111",
	emailAddress = "test@test.com",
	name = "cem",
	surname = "pehlivan",
	phoneNumber = "1111111111",
	addressDesc = "adres",
	cityName = "istanbul",
	country = Banka.VPOS.Enums.Country.TUR,
	postCode = "34000",
	taxOffice = "maltepe",
	townName = "maltepe"
};

SaleRequest saleRequest = new SaleRequest
{
	invoiceInfo = customerInfo,
	shippingInfo = customerInfo,
	saleInfo = new SaleInfo
	{
		cardNameSurname = "test kart",
		cardNumber = "4022780520669303",
		cardExpiryDateMonth = 1,
		cardExpiryDateYear = 2050,
		cardCVV = "988",
		amount = (decimal)10,
		currency = Banka.VPOS.Enums.Currency.TRY,
		installment = 1,
	},
	payment3D = new Payment3D
	{
		confirm = false
	},
	customerIPAddress = "1.1.1.1",
	orderNumber = Convert.ToInt32((DateTime.Now - new DateTime(1970, 1, 1)).TotalSeconds).ToString("X")
};


var resp = VPOSClient.Sale(saleRequest, _qnbPayTest);
```

## 3D Secure Satış İşlemi

`payment3D.confirm = true` gönderilmesi halinde 3D li  satış işlemi başlatılır. 3D li işlemlerde `payment3D.returnURL` alanına 3D den gelecek olan cevabın iletilmesi istenen URL girilmelidir. Örneğin: `https://localhost/Payment/VirtualPOS3DResponse`. 

`VPOSClient.Sale` metodundan dönen cevaptaki `statu` enum alanı `RedirectURL` veya `RedirectHTML` döner. statu `RedirectURL` ise `message` alanında client'ı yönlendirmeniz gereken url bulunur. statu `RedirectHTML` ise `message` alanında client'ın sayfasında çalıştırmanız gereken HTML bulunur. 

Bu işlem sonrası client, banka 3D doğrulama sayfasına yönlendirilir. Bu sayfadaki işlem sonucunu banka, `payment3D.returnURL` alanında belirttiğimiz url e client'ın browserını kullanarak form post yöntemi ile döner.

3D den gelen form request body'sini  `Dictionary<string, object>` e çevirip `VPOSClient.Sale3DResponse` methoduna gönderilmesi gerekmektedir. Bu işlem sonrası nihai sonuç döner.

```csharp
VirtualPOSAuth _qnbPayTest = new VirtualPOSAuth
{
    bankCode = Banka.VPOS.Services.BankService.QNBpay,
    merchantID = "20158",
    merchantUser = "07fb70f9d8de575f32baa6518e38c5d6",
    merchantPassword = "61d97b2cac247069495be4b16f8604db",
    merchantStorekey = "$2y$10$N9IJkgazXMUwCzpn7NJrZePy3v.dIFOQUyW4yGfT3eWry6m.KxanK",
    testPlatform = true
};

CustomerInfo customerInfo = new CustomerInfo
{
	taxNumber = "1111111111",
	emailAddress = "test@test.com",
	name = "cem",
	surname = "pehlivan",
	phoneNumber = "1111111111",
	addressDesc = "adres",
	cityName = "istanbul",
	country = Banka.VPOS.Enums.Country.TUR,
	postCode = "34000",
	taxOffice = "maltepe",
	townName = "maltepe"
};

SaleRequest saleRequest = new SaleRequest
{
	invoiceInfo = customerInfo,
	shippingInfo = customerInfo,
	saleInfo = new SaleInfo
	{
		cardNameSurname = "test kart",
		cardNumber = "4022780520669303",
		cardExpiryDateMonth = 1,
		cardExpiryDateYear = 2050,
		cardCVV = "988",
		amount = (decimal)10,
		currency = Banka.VPOS.Enums.Currency.TRY,
		installment = 1,
	},
	payment3D = new Payment3D
	{
		confirm = true,
		returnURL = "https://localhost/Payment/VirtualPOS3DResponse"
	},
	customerIPAddress = "1.1.1.1",
	orderNumber = Convert.ToInt32((DateTime.Now - new DateTime(1970, 1, 1)).TotalSeconds).ToString("X")
};


var resp = VPOSClient.Sale(saleRequest, _qnbPayTest);
```


### 3D Secure Satış İşlemi 2. Adım


```csharp

public class PaymentController
{
    public async Task<IActionResult> VirtualPOS3DResponse()
    {
        Dictionary<string, object>? pairs = null;

        if (Request.Method == "GET")
            pairs = Request.Query.Keys.ToDictionary(k => k, v => (object)Request.Query[v]);
        else
            pairs = Request.Form.Keys.ToDictionary(k => k, v => (object)Request.Form[v]);   

        SaleResponse response = VPOSClient.Sale3DResponse(new Sale3DResponseRequest
        {
            responseArray = pairs
        }, _qnbPayTest);
    }
}

```

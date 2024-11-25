# ENGLISH / TÜRKÇE

## Project Description / Proje Tanımı

**EN:**  
This project demonstrates how to use XML serialization and deserialization in C#. It includes examples of serializing objects to XML strings or files and deserializing XML back into objects or lists. The main purpose of this project is to teach the basics of handling XML data in C#.

**TR:**  
Bu proje, C# dilinde XML serileştirme ve serileştirme işlemlerinin nasıl kullanılacağını göstermektedir. Nesneleri XML stringlerine veya dosyalarına dönüştürme ve XML'i tekrar nesnelere veya listelere dönüştürme örneklerini içermektedir. Projenin temel amacı, C# dilinde XML verilerini işlemenin temel prensiplerini öğretmektir.

---

## Features / Özellikler

### EN:
1. **Serialize an object to an XML string**: Convert a `Member` object into an XML string and display it.  
2. **Deserialize an XML string to an object**: Transform an XML string back into a `Member` object.  
3. **Serialize a list of objects to an XML file**: Save a list of `Member` objects as an XML file (e.g., `sample04.xml`).  
4. **Deserialize an XML file to a list of objects**: Read data from an XML file (e.g., `sample04.xml`) and convert it into a list of `Member` objects.  
5. **Serialize an object to an XML file**: Save a single `Member` object to an XML file (e.g., `sample02.xml`).  
6. **Deserialize an XML file to a single object**: Load data from an XML file (e.g., `sample01.xml`) into a single `Member` object.  

### TR:
1. **Bir nesneyi XML stringine serileştirme**: `Member` nesnesini bir XML stringine dönüştürerek gösterir.  
2. **XML stringini bir nesneye serileştirme**: XML stringini tekrar bir `Member` nesnesine dönüştürür.  
3. **Bir nesne listesini XML dosyasına serileştirme**: `Member` nesnelerinden oluşan bir listeyi (`sample04.xml`) bir XML dosyasına kaydeder.  
4. **XML dosyasını bir nesne listesine serileştirme**: `sample04.xml` dosyasındaki verileri okuyarak bir `Member` listesine dönüştürür.  
5. **Bir nesneyi XML dosyasına serileştirme**: Tek bir `Member` nesnesini (`sample02.xml`) bir XML dosyasına kaydeder.  
6. **XML dosyasını tek bir nesneye serileştirme**: `sample01.xml` dosyasından verileri okuyarak tek bir `Member` nesnesine dönüştürür.  

---

## Requirements / Gereksinimler

### EN:
- **C#**: Any version supporting .NET Framework or .NET Core.  
- **IDE**: Visual Studio or any compatible C# development environment.  

### TR:
- **C#**: .NET Framework veya .NET Core'u destekleyen herhangi bir sürüm.  
- **IDE**: Visual Studio veya herhangi bir uyumlu C# geliştirme ortamı.  

---

## Installation and Usage / Kurulum ve Kullanım

### EN:
1. Clone or download the project to your local machine.  
2. Open the project in Visual Studio or your preferred IDE.  
3. Build and run the project.  
4. During execution, the program will:  
   - Serialize a `Member` object to an XML string.  
   - Deserialize the XML string back to a `Member` object.  
   - Serialize a list of `Member` objects to an XML file.  
   - Deserialize the XML file into a list of `Member` objects.  

### TR:
1. Projeyi bilgisayarınıza klonlayın veya indirin.  
2. Projeyi Visual Studio veya tercih ettiğiniz IDE ile açın.  
3. Projeyi derleyin ve çalıştırın.  
4. Çalıştırma sırasında program:  
   - Bir `Member` nesnesini XML stringine serileştirecek.  
   - XML stringini tekrar bir `Member` nesnesine serileştirecek.  
   - `Member` nesnelerinden oluşan bir listeyi bir XML dosyasına serileştirecek.  
   - XML dosyasını bir `Member` nesne listesine serileştirecek.  

---

## Sample Output / Örnek Çıktı

```xml
<Member>
  <Name>John</Name>
  <Email>john@gmail.com</Email>
  <Age>30</Age>
  <RegistrationDate>2024-11-25T10:15:30.9999999</RegistrationDate>
  <IsActive>false</IsActive>
</Member>


### Açıklamalar:
- Her başlık için uygun bir Markdown seviyesi kullanıldı (örn. `##`, `###`).
- Dil seçenekleri açıkça ayrıldı ve kolay okunabilirlik için **bold** veya **italik** gibi basit vurgulamalar eklendi.
- Listeler, Markdown'daki madde işaretleriyle düzgün şekilde hizalandı.
- Kod blokları için üçlü tırnak işaretleri kullanıldı. Bu, XML veya diğer kod örneklerinin düzgün görünmesini sağlar.

Bu düzeni README dosyanıza uygularsanız, hiyerarşi ve düzen netleşir. 🎉


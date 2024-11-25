ENGLISH/TÜRKÇE
Project Description / Proje Tanımı
This project demonstrates how to use XML serialization and deserialization in C#. It includes key features like converting objects to XML and vice versa, handling individual objects and lists, and saving/loading XML files.
Bu proje, C# dilinde XML serileştirme ve seriden çıkarma işlemlerinin nasıl kullanılacağını göstermektedir. Nesneleri XML'e ve XML'i nesnelere dönüştürme, bireysel nesneler ve listeleri işleme, XML dosyalarını kaydetme/yükleme gibi temel özellikleri içermektedir.

Features / Özellikler
Serialize an object to an XML string / Bir nesneyi XML dizgesine dönüştürme:
The project converts a Member object into an XML string and displays it.
Proje, bir Member nesnesini XML dizgesine dönüştürüp ekrana yazdırır.

Deserialize an XML string to an object / XML dizgesini nesneye dönüştürme:
An XML string is converted back to a Member object.
XML dizgesi bir Member nesnesine geri dönüştürülür.

Serialize a list of objects to an XML file / Nesne listesini XML dosyasına dönüştürme:
A list of Member objects is serialized into an XML file (sample04.xml).
Member nesnelerinden oluşan bir liste, XML dosyasına (sample04.xml) dönüştürülür.

Deserialize an XML file to a list of objects / XML dosyasını nesne listesine dönüştürme:
Data from an XML file (sample04.xml) is converted back to a list of Member objects.
sample04.xml dosyasındaki veriler, Member nesneleri listesine geri dönüştürülür.

Serialize an object to an XML file / Bir nesneyi XML dosyasına dönüştürme:
A single Member object is saved to an XML file (sample02.xml).
Bir Member nesnesi, XML dosyasına (sample02.xml) kaydedilir.

Deserialize an XML file to a single object / XML dosyasını tek bir nesneye dönüştürme:
Data from an XML file (sample01.xml) is read and deserialized into a Member object.
sample01.xml dosyasındaki veri, bir Member nesnesine dönüştürülür.

Requirements / Gereksinimler
C#: Any version supporting .NET Framework or .NET Core / .NET Framework veya .NET Core'u destekleyen herhangi bir sürüm.
IDE: Visual Studio or any other C# IDE / Visual Studio veya başka bir C# IDE'si.
Installation and Usage / Kurulum ve Kullanım
Follow these steps to run the project:
Projenin çalıştırılması için aşağıdaki adımları izleyin:

Clone or download the project / Projeyi klonlayın veya indirin.
Build and run the project / Projeyi derleyip çalıştırın.
The program will perform the following operations / Program aşağıdaki işlemleri gerçekleştirecektir:
Serialize a Member object to an XML string / Bir Member nesnesini XML dizgesine dönüştürür.
Deserialize that XML string back to a Member object / XML dizgesini Member nesnesine geri dönüştürür.
Serialize a list of Member objects to an XML file / Bir Member nesne listesini XML dosyasına dönüştürür.
Deserialize that XML file back into a list of Member objects / XML dosyasını Member nesneleri listesine geri dönüştürür.
Sample Output / Örnek Çıktı
When you run the project, XML output will appear on the console. For example:
Projeyi çalıştırdığınızda, konsolda XML çıktısı göreceksiniz. Örnek:

xml
Copy code
<Member>
  <Name>John</Name>
  <Email>john@gmail.com</Email>
  <Age>30</Age>
  <RegistrationDate>2024-11-25T10:15:30.9999999</RegistrationDate>
  <IsActive>false</IsActive>
</Member>
Notes / Notlar
This project is designed for learning purposes to understand XML operations in C#.
Bu proje, C# dilinde XML işlemlerini öğrenmek için tasarlanmıştır.

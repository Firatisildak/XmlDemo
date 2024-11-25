##ENGLISH/TÜRKÇE
#Project Description / Proje Tanımı
EN:
This project demonstrates how to use XML serialization and deserialization in C#. It includes examples of serializing objects to XML strings or files and deserializing XML back into objects or lists. The main purpose of this project is to teach the basics of handling XML data in C#.

TR:
Bu proje, C# dilinde XML serileştirme ve serileştirme işlemlerinin nasıl kullanılacağını göstermektedir. Nesneleri XML stringlerine veya dosyalarına dönüştürme ve XML'i tekrar nesnelere veya listelere dönüştürme örneklerini içermektedir. Projenin temel amacı, C# dilinde XML verilerini işlemenin temel prensiplerini öğretmektir.

Features / Özellikler
EN:

Serialize an object to an XML string: Convert a Member object into an XML string and display it.
Deserialize an XML string to an object: Transform an XML string back into a Member object.
Serialize a list of objects to an XML file: Save a list of Member objects as an XML file (sample04.xml).
Deserialize an XML file to a list of objects: Read data from an XML file (sample04.xml) and convert it into a list of Member objects.
Serialize an object to an XML file: Save a single Member object to an XML file (sample02.xml).
Deserialize an XML file to a single object: Load data from an XML file (sample01.xml) into a single Member object.
TR:

Bir nesneyi XML stringine serileştirme: Member nesnesini bir XML stringine dönüştürerek gösterir.
XML stringini bir nesneye serileştirme: XML stringini tekrar bir Member nesnesine dönüştürür.
Bir nesne listesini XML dosyasına serileştirme: Member nesnelerinden oluşan bir listeyi (sample04.xml) bir XML dosyasına kaydeder.
XML dosyasını bir nesne listesine serileştirme: sample04.xml dosyasındaki verileri okuyarak bir Member listesine dönüştürür.
Bir nesneyi XML dosyasına serileştirme: Tek bir Member nesnesini (sample02.xml) bir XML dosyasına kaydeder.
XML dosyasını tek bir nesneye serileştirme: sample01.xml dosyasından verileri okuyarak tek bir Member nesnesine dönüştürür.
Requirements / Gereksinimler
EN:

C#: Any version supporting .NET Framework or .NET Core.
IDE: Visual Studio or any compatible C# development environment.
TR:

C#: .NET Framework veya .NET Core'u destekleyen herhangi bir sürüm.
IDE: Visual Studio veya herhangi bir uyumlu C# geliştirme ortamı.
Installation and Usage / Kurulum ve Kullanım
EN:

Clone or download the project to your local machine.
Open the project in Visual Studio or your preferred IDE.
Build and run the project.
During execution, the program will:

Serialize a Member object to an XML string.
Deserialize the XML string back to a Member object.
Serialize a list of Member objects to an XML file.
Deserialize the XML file into a list of Member objects.
TR:

Projeyi bilgisayarınıza klonlayın veya indirin.
Projeyi Visual Studio veya tercih ettiğiniz IDE ile açın.
Projeyi derleyin ve çalıştırın.
Çalıştırma sırasında program:

Bir Member nesnesini XML stringine serileştirecek.
XML stringini tekrar bir Member nesnesine serileştirecek.
Member nesnelerinden oluşan bir listeyi bir XML dosyasına serileştirecek.
XML dosyasını bir Member nesne listesine serileştirecek.
Sample Output / Örnek Çıktı
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
EN:
This project is designed to help developers understand the concepts of XML serialization and deserialization in C#. It serves as a learning tool for working with structured data in XML format.

TR:
Bu proje, geliştiricilerin C# dilinde XML serileştirme ve serileştirme kavramlarını anlamalarına yardımcı olmak için tasarlanmıştır. XML formatındaki yapılandırılmış verilerle çalışmayı öğrenmek için bir araç görevi görür.








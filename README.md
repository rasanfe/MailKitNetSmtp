# 📧 MailKitNetSmtp

![.NET](https://img.shields.io/badge/.NET-10.0-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![C#](https://img.shields.io/badge/C%23-239120?style=flat-square&logo=csharp&logoColor=white)
![MailKit](https://img.shields.io/badge/MailKit-4.17-1f6feb?style=flat-square)
![Blog](https://img.shields.io/badge/blog-rsrsystem-FF5722?style=flat-square&logo=blogger&logoColor=white)

> Librería de clases **.NET 10** para **enviar e-mails por SMTP** desde PowerBuilder, apoyándose en [MailKit](https://github.com/jstedfast/MailKit).

## 📋 ¿Qué es esto?

Esta es la librería que uso en el ejemplo de PowerBuilder **pbMailKit**. La idea es sencilla: dejar
el SMTP moderno (TLS, autenticación, adjuntos, HTML…) en manos de **MailKit/MimeKit** y consumirla
desde PowerBuilder como un `dotnetobject`, sin pelearnos con las APIs de correo nativas.

## 🧩 Dependencias

| Paquete | Versión |
|---------|---------|
| [MailKit](https://www.nuget.org/packages/MailKit) | `4.17.0` |
| [MimeKit](https://www.nuget.org/packages/MimeKit) | `4.17.0` |

## 🛠️ Requisitos

- **.NET SDK 10.0** o superior
- Visual Studio 2022 (o compilar con `dotnet`)

## 🚀 Compilar

```bat
dotnet build MailKitNetSmtp.csproj -c Release
```

La DLL queda en `bin\Release\net10.0\`.

## 🔗 Proyecto PowerBuilder relacionado

👉 **pbMailKit** — https://github.com/rasanfe/pbMailKit

---

📨 **Blog:** <https://rsrsystem.blogspot.com/>

> ¡Nos vemos en el próximo artículo! Y recuerda: en PowerBuilder, los límites solo están en nuestra imaginación. 🚀

---
title: Создание решений Microsoft 365 с помощью подписки для разработчиков
description: Используйте подписку для разработчиков Microsoft 365, чтобы создавать нужные решения.
ms.localizationpriority: high
ms.openlocfilehash: 2450b0dee53ca7a8bdaf90beea3cb08f9e2dea36
ms.sourcegitcommit: b10b392973a9eb8636ce4f1994c3bdbed000411c
ms.translationtype: MT
ms.contentlocale: ru-RU
ms.lasthandoff: 10/13/2022
ms.locfileid: "68570595"
---
# <a name="use-your-developer-subscription-to-build-microsoft-365-solutions"></a>Создание решений Microsoft 365 с помощью подписки для разработчиков

Что вы хотите создать с помощью подписки на Microsoft 365 для разработчиков? Вы можете выполнять различные задачи в зависимости от целей. Ниже описаны некоторые продукты и технологии, с которых можно начать.

## <a name="microsoft-teams"></a>Microsoft Teams

Microsoft Teams - это рабочее пространство на основе чата, которое интегрируется с приложениями и службами, которые люди используют для совместной работы. Платформа разработки Microsoft Teams упрощает интеграцию службы независимо от того, разрабатываете ли вы специальные приложения для своего предприятия или приложения SaaS для команд по всему миру.

Ниже представлен процесс настройки и написания кода с помощью Microsoft Teams.

1. [Подготовка подписки для разработчиков](/microsoftteams/platform/get-started/get-started-tenant).
2. Настройка среды разработки. Этот процесс зависит от создаваемого типа приложения или службы. Дополнительные сведения см. в одном из следующих разделов:

  - [Начало работы на платформе Microsoft Teams с использованием Node.js](/microsoftteams/platform/get-started/get-started-nodejs-app-studio)
  - [Начало работы на платформе Microsoft Teams с использованием C#/.NET](/microsoftteams/platform/get-started/get-started-dotnet-app-studio)

## <a name="microsoft-graph"></a>Microsoft Graph

Вы можете использовать Microsoft Graph для работы с данными миллионов пользователей в Microsoft Cloud. С помощью Microsoft Graph можно создавать приложения для организаций и потребителей, которые подключаются к различным ресурсам, отношениям и оповещениям через одну конечную точку: `https://graph.microsoft.com`.

Чтобы автоматически настроить песочницу для пробного использования сценариев Microsoft Graph, установите примеры пакетов данных "Пользователи" и "Почта и события":

- Пользователи. Устанавливает 16 вымышленных пользователей с лицензиями, почтовыми ящиками и метаданными, включая имена и фотографии для каждого пользователя. Используйте API Microsoft Graph для работы с примерами данных пользователей следующим образом:
  - Получение сведений об определенном пользователе
  - Обновление пользователя
  - Получение подчиненных
  - Подготовка организационной диаграммы
  - Получение пользователей по отделам
- Почта и события. Добавляет беседы электронной почты Outlook и события календаря для каждого из 16 примеров пользователей. Используйте API Microsoft Graph для работы с примерами данных почты и событий следующим образом:
  - Получение сообщений электронной почты для пользователей
  - Получение сообщений электронной почты, отфильтрованных по дате
  - Получение предстоящих событий
  - Обновление и удаление предстоящих событий

Подробности см. в статье [Установка примеров пакетов данных](install-sample-packs.md). 

Подробнее о том, как начать работу с Microsoft Graph, см. в статье [Начало создания приложений Microsoft Graph](https://developer.microsoft.com/en-us/graph/get-started) или [Краткое руководство](https://developer.microsoft.com/en-us/graph/quick-start) по Microsoft Graph.

## <a name="office-add-ins"></a>Надстройки Office

You can use the Office Add-ins platform to build solutions that extend Office applications and interact with content in Office documents. With Office Add-ins, you can use familiar web technologies such as HTML, CSS, and JavaScript to extend and interact with Word, Excel, PowerPoint, OneNote, Project, and Outlook. Your solution can run in Office across multiple platforms, including Office for Windows, Office Online, Office for the Mac, and Office for the iPad.

Чтобы настроить среду разработки и создать первую надстройку, см. статью [Краткие руководства по надстройкам Office](/office/dev/add-ins/).

## <a name="sharepoint-framework"></a>SharePoint Framework

The SharePoint Framework (SPFx) is a page and web part model that provides full support for client-side SharePoint development, easy integration with SharePoint data, and support for open source tooling. With the SharePoint Framework, you can use modern web technologies and tools in your preferred development environment to build productive experiences and apps that are responsive and mobile-ready.

To automatically configure your sandbox to try out different SharePoint templates and scenarios, install the SharePoint sample data pack.
For more details, see:

- [Установка примеров пакетов данных](install-sample-packs.md)
- [Настройка подписки разработчика на SPFx](/sharepoint/dev/spfx/set-up-your-developer-tenant)
- [Настройка среды разработки](/sharepoint/dev/spfx/set-up-your-development-environment)

## <a name="sharepoint-add-ins"></a>Надстройки SharePoint 

Надстройка SharePoint — это автономный функциональный модуль, расширяющий возможности веб-сайтов SharePoint для решения определенной бизнес-задачи. Можно создавать два типа надстроек SharePoint (с размещением в SharePoint и у поставщика). Дополнительные сведения см. в статье [Надстройки SharePoint](/sharepoint/dev/sp-add-ins/sharepoint-add-ins).

Процесс настройки и написания кода с помощью надстроек SharePoint:

- [Настройка подписки](/sharepoint/dev/spfx/set-up-your-developer-tenant).  
- Настройка среды разработки: 
  - [Знакомство с созданием надстроек SharePoint с размещением в SharePoint](/sharepoint/dev/sp-add-ins/get-started-creating-sharepoint-hosted-sharepoint-add-ins)  
  - [Знакомство с созданием надстроек SharePoint с размещением у поставщика](/sharepoint/dev/sp-add-ins/get-started-creating-provider-hosted-sharepoint-add-ins)  

## <a name="power-apps"></a>Power Apps

Power Apps для Office 365 входит в вашу лицензию на подписку разработчика Microsoft 365 E5. Это означает, что вы можете создавать и тестировать неограниченные приложения со [стандартными соединителями](/connectors/connector-reference/connector-reference-standard-connectors). Чтобы использовать [премиальные](/connectors/connector-reference/connector-reference-premium-connectors) или настраиваемые соединители и Dataverse, требуется дополнительная лицензия. В целях разработки и тестирования вы можете использовать [план разработчика Power Apps](https://powerapps.microsoft.com/developerplan). 

Power Apps — это набор приложений, служб, соединителей и платформ данных, образующих среду для быстрой разработки собственных приложений с учетом уникальных бизнес-потребностей предприятия. С помощью Power Apps можно быстро создавать настраиваемые бизнес-приложения для подключения собственных бизнес-данных, хранящихся либо на базовой платформе (Common Data Service), либо в различных сетевых и локальных источниках, таких как SharePoint, Microsoft 365, Dynamics 365, SQL Server и т. д.

Приложения, созданные на базе Power Apps, поддерживают разнообразную бизнес-логику и рабочие процессы для трансформации бизнес-процессов, осуществляемых вручную, в цифровые и автоматизированные. Кроме того, приложения Power Apps отличаются адаптивным дизайном и отлично работают как в браузере, так и на мобильных устройствах (телефонах и планшетах). Power Apps делает создание бизнес-приложений более доступным занятием, позволяя пользователям разрабатывать собственные функциональные бизнес-приложения без написания программного кода.

Power Apps также служит надежной платформой, которая позволяет разработчикам программно взаимодействовать с данными и метаданными, применять бизнес-логику, создавать собственные соединители и настраивать интеграцию с внешними данными.

Подробнее:

- [Power Apps](/powerapps/)
- Посмотрите [демонстрации Power Apps](https://powerapps.microsoft.com/demo/)
- Посмотрите видео на канале [Power Apps](https://www.youtube.com/channel/UCGfWR2ekfRFckLjev6eQYLg) в YouTube


## <a name="see-also"></a>См. также

- [Присоединяйтесь к программе для разработчиков Microsoft 365](microsoft-365-developer-program.md)
- [Настройка подписки разработчика Microsoft 365](microsoft-365-developer-program-get-started.md) 
- [Продление подписки с истекающим сроком действия](subscription-expiration-and-renewal.md)
- [Вопросы и ответы о программе для разработчиков Microsoft 365](microsoft-365-developer-program-faq.yml)
- [Документация Microsoft 365 для разработчиков](/microsoft-365/developer)

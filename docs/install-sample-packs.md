---
title: Использование примеров пакетов данных в подписке программы для разработчиков Microsoft 365
description: Узнайте, как установить примеры пакетов данных в подписке разработчика, чтобы быстро подготовить среду в песочнице.
localization_priority: Priority
ms.openlocfilehash: 3802c1c1e02c7be9ccb322561189ee0d085e8ce0
ms.sourcegitcommit: 3d50606496bd0bdbbcf892d2d18de6343a44c576
ms.translationtype: HT
ms.contentlocale: ru-RU
ms.lasthandoff: 04/19/2021
ms.locfileid: "51890153"
---
# <a name="use-sample-data-packs-with-your-microsoft-365-developer-program-subscription"></a><span data-ttu-id="43467-103">Использование примеров пакетов данных в подписке программы для разработчиков Microsoft 365</span><span class="sxs-lookup"><span data-stu-id="43467-103">Use sample data packs with your Microsoft 365 Developer Program subscription</span></span>

<span data-ttu-id="43467-104">Вы можете установить примеры пакетов данных в подписке программы для разработчиков Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="43467-104">You can install sample data packs on your Microsoft 365 Developer Program subscription.</span></span> <span data-ttu-id="43467-105">Примеры пакетов данных позволяют экономить время, автоматически устанавливая данные и содержимое, необходимые для создания и тестирования решений.</span><span class="sxs-lookup"><span data-stu-id="43467-105">Sample data packs save you time by automatically installing data and content you need to build and test your solutions.</span></span> <span data-ttu-id="43467-106">Сюда относятся вымышленные пользователи, метаданные и фотографии для имитации небольшой корпоративной среды.</span><span class="sxs-lookup"><span data-stu-id="43467-106">This includes fictitious users, metadata, and photos to simulate a small corporate environment.</span></span> <span data-ttu-id="43467-107">Вы можете быстро установить пример данных, чтобы не тратить время на их создание, а сосредоточиться на своих решениях.</span><span class="sxs-lookup"><span data-stu-id="43467-107">You can quickly install the sample data so that you can focus on your solutions rather than spend time creating sample data yourself.</span></span>

<span data-ttu-id="43467-108">Примеры пакетов данных можно найти на [панели мониторинга программы для разработчиков Microsoft 365](https://developer.microsoft.com/office/profile) в нижней части плитки подписки.</span><span class="sxs-lookup"><span data-stu-id="43467-108">You can find sample data packs on your [Microsoft 365 Developer Program dashboard](https://developer.microsoft.com/office/profile), at the bottom of your subscription tile.</span></span>

![Снимок экрана: плитка подписки на странице информационной панели](images/sample-data-pack-ux-tile-users-beginning.PNG)

<span data-ttu-id="43467-110">В настоящее время доступны следующие примеры пакетов данных.</span><span class="sxs-lookup"><span data-stu-id="43467-110">The following sample data packs are currently available:</span></span>

- <span data-ttu-id="43467-111">Пользователи. Устанавливает 16 вымышленных пользователей с лицензиями, почтовыми ящиками и метаданными, включая имена и фотографии для каждого пользователя.</span><span class="sxs-lookup"><span data-stu-id="43467-111">Users - Installs 16 fictitious users with licenses, mailboxes, and metadata, including names and photos for each user.</span></span> <span data-ttu-id="43467-112">Используйте API Microsoft Graph для работы с примерами данных пользователей следующим образом:</span><span class="sxs-lookup"><span data-stu-id="43467-112">Use Microsoft Graph APIs to work with user sample data in the following ways:</span></span>
  - <span data-ttu-id="43467-113">Получение сведений об определенном пользователе</span><span class="sxs-lookup"><span data-stu-id="43467-113">Get specific user details</span></span>
  - <span data-ttu-id="43467-114">Обновление пользователя</span><span class="sxs-lookup"><span data-stu-id="43467-114">Update user</span></span>
  - <span data-ttu-id="43467-115">Получение подчиненных</span><span class="sxs-lookup"><span data-stu-id="43467-115">Get direct reports</span></span>
  - <span data-ttu-id="43467-116">Подготовка организационной диаграммы</span><span class="sxs-lookup"><span data-stu-id="43467-116">Prepare organization chart</span></span>  
  - <span data-ttu-id="43467-117">Получение пользователей по отделам</span><span class="sxs-lookup"><span data-stu-id="43467-117">Get users by department</span></span>

- <span data-ttu-id="43467-118">Почта и события. Добавляет беседы электронной почты Outlook и события календаря для каждого из 16 примеров пользователей.</span><span class="sxs-lookup"><span data-stu-id="43467-118">Mail and events - Adds Outlook email conversations and calendar events for each of the 16 sample users.</span></span> <span data-ttu-id="43467-119">Используйте API Microsoft Graph для работы с примерами данных почты и событий следующим образом:</span><span class="sxs-lookup"><span data-stu-id="43467-119">Use Microsoft Graph APIs to work with mail and events sample data in the following ways:</span></span>
  - <span data-ttu-id="43467-120">Получение сообщений электронной почты для пользователей</span><span class="sxs-lookup"><span data-stu-id="43467-120">Get emails by users</span></span>
  - <span data-ttu-id="43467-121">Получение сообщений электронной почты, отфильтрованных по дате</span><span class="sxs-lookup"><span data-stu-id="43467-121">Get emails filtered by date</span></span>
  - <span data-ttu-id="43467-122">Получение предстоящих событий</span><span class="sxs-lookup"><span data-stu-id="43467-122">Get upcoming events</span></span>
  - <span data-ttu-id="43467-123">Обновление и удаление предстоящих событий</span><span class="sxs-lookup"><span data-stu-id="43467-123">Update/delete upcoming events</span></span>

> [!NOTE]
> <span data-ttu-id="43467-124">Перед установкой примера данных "Почта и события" требуется установить пример пакета данных "Пользователи".</span><span class="sxs-lookup"><span data-stu-id="43467-124">You must install the Users sample data pack before you install Mail and Events.</span></span>

## <a name="what-do-the-sample-data-packs-add-to-my-subscription"></a><span data-ttu-id="43467-125">Что добавляют примеры пакетов данных в мою подписку?</span><span class="sxs-lookup"><span data-stu-id="43467-125">What do the sample data packs add to my subscription?</span></span>

<span data-ttu-id="43467-126">Пример пакета данных "Пользователи" создает в вашей подписке 16 вымышленных пользователей и добавляет лицензии, а также почтовые ящики, имена, метаданные и фотографии для каждого пользователя.</span><span class="sxs-lookup"><span data-stu-id="43467-126">The Users sample data pack creates 16 fictitious users on your subscription, and includes the licenses for each user, and mailboxes, names, metadata, and photos for each.</span></span>

<span data-ttu-id="43467-127">Пример пакета данных "Почта и события" добавляет беседы электронной почты Outlook и события календаря для каждого из 16 установленных пользователей.</span><span class="sxs-lookup"><span data-stu-id="43467-127">The Mail and Events sample data pack adds Outlook email conversations and calendar events for each of the 16 users installed.</span></span>

## <a name="how-do-i-install-the-users-sample-data-pack"></a><span data-ttu-id="43467-128">Как установить пример пакета данных "Пользователи"?</span><span class="sxs-lookup"><span data-stu-id="43467-128">How do I install the Users sample data pack?</span></span>

<span data-ttu-id="43467-129">Перед установкой примера пакета данных "Пользователи" убедитесь в наличии подписки разработчика на Microsoft 365 и назначьте для себя лицензию администратора.</span><span class="sxs-lookup"><span data-stu-id="43467-129">Before you install the Users sample data pack, make sure that you have a Microsoft 365 developer subscription and that you assign a license to yourself as the admin.</span></span>

> [!NOTE]
> <span data-ttu-id="43467-130">Убедитесь, что в вашей подписке доступно 16 пользователей.</span><span class="sxs-lookup"><span data-stu-id="43467-130">Make sure that you have 16 users available in your subscription.</span></span> <span data-ttu-id="43467-131">Ваша подписка включает 25 пользователей.</span><span class="sxs-lookup"><span data-stu-id="43467-131">Your subscription includes 25 users.</span></span> <span data-ttu-id="43467-132">Если вы уже настроили более 10 пользователей, сначала удалите некоторых из них, чтобы обеспечить успешную установку.</span><span class="sxs-lookup"><span data-stu-id="43467-132">If you have already configured more than 10 users, remove some users first to ensure that your installation is successful.</span></span>

<span data-ttu-id="43467-133">Чтобы установить пример пакета данных "Пользователи":</span><span class="sxs-lookup"><span data-stu-id="43467-133">To install the Users sample data pack:</span></span>

1. <span data-ttu-id="43467-134">Выберите поле **Пользователи** внизу плитки подписки.</span><span class="sxs-lookup"><span data-stu-id="43467-134">Select the **Users** box at the bottom of your subscription tile.</span></span>
2. <span data-ttu-id="43467-135">Скопируйте идентификатор администратора. Он потребуется для входа в вашу подписку.</span><span class="sxs-lookup"><span data-stu-id="43467-135">Copy your administrator ID; you will need it to sign in to your subscription.</span></span>
3. <span data-ttu-id="43467-136">Введите идентификатор администратора и пароль на странице входа.</span><span class="sxs-lookup"><span data-stu-id="43467-136">Enter your administrator ID and password on the sign in page.</span></span>
4. <span data-ttu-id="43467-137">Дайте согласие на получение доступа в качестве администратора подписки разработчика на Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="43467-137">Consent to the permissions as an administrator of your Microsoft 365 developer subscription.</span></span>

![Снимок экрана: диалоговое окно согласия на предоставление доступа](images/sample-data-pack-ux-tile-users-consent-with-permissions-combined.PNG)

5. <span data-ttu-id="43467-139">Настройте пароли для всех пользователей из примера.</span><span class="sxs-lookup"><span data-stu-id="43467-139">Configure your passwords for all sample users.</span></span> <span data-ttu-id="43467-140">Для удобства администрирования всех вымышленных пользователей потребуется задать один общий пароль.</span><span class="sxs-lookup"><span data-stu-id="43467-140">You will need to have one shared password defined for easy administration of all your fictitious users.</span></span>

![Снимок экрана: диалоговое окно добавления общего пароля для пользователей](images/sample-data-pack-ux-tile-users-fake-user-password-creation.PNG)

6. <span data-ttu-id="43467-142">Будет выполнена установка данных,</span><span class="sxs-lookup"><span data-stu-id="43467-142">The data will be installed.</span></span> <span data-ttu-id="43467-143">занимающая около 5 минут.</span><span class="sxs-lookup"><span data-stu-id="43467-143">The installation should take about 5 minutes.</span></span>

![Снимок экрана: процесс установки на плитке информационной панели](images/sample-data-pack-ux-tile-users-installing-status.PNG)

7. <span data-ttu-id="43467-145">После завершения установки вы получите уведомление по электронной почте, а поле на плитке подписки станет зеленым.</span><span class="sxs-lookup"><span data-stu-id="43467-145">When installation is finished, you'll be notified by email, and the box on your subscription tile will be green.</span></span> <span data-ttu-id="43467-146">Теперь вы можете установить пример пакета данных "Почта и события".</span><span class="sxs-lookup"><span data-stu-id="43467-146">You can now install the Mail and Events sample data pack.</span></span>

![Снимок экрана: плитка информационной панели с готовым к установке пакетом "Почта и события"](images/sample-data-pack-ux-tile-users-installed.PNG)

## <a name="how-do-i-install-the-mail-and-events-sample-data-pack"></a><span data-ttu-id="43467-148">Как установить пример пакета данных "Почта и события"?</span><span class="sxs-lookup"><span data-stu-id="43467-148">How do I install the Mail and Events sample data pack?</span></span>

<span data-ttu-id="43467-149">После установки примера пакета данных "Пользователи" можно установить пакет данных "Почта и события".</span><span class="sxs-lookup"><span data-stu-id="43467-149">After you've installed the Users sample data pack, you can install mail and events.</span></span>

1. <span data-ttu-id="43467-150">На плитке подписки выберите поле **Почта и события**.</span><span class="sxs-lookup"><span data-stu-id="43467-150">Choose the **Mail &amp; Events** box on your subscription tile.</span></span>
2. <span data-ttu-id="43467-151">Нажмите кнопку **Установить**, чтобы начать установку.</span><span class="sxs-lookup"><span data-stu-id="43467-151">Select **Install** to begin installation.</span></span>

![Снимок экрана: диалоговое окно установки](images/sample-data-pack-ux-tile-mail-and-events-begin-install.PNG)

> [!NOTE]
> <span data-ttu-id="43467-153">Если вы только что создали свою подписку, ее требуется полностью подготовить перед началом установки.</span><span class="sxs-lookup"><span data-stu-id="43467-153">If you just created your subscription, it must be fully provisioned before installation can begin.</span></span> <span data-ttu-id="43467-154">Это может занять несколько часов.</span><span class="sxs-lookup"><span data-stu-id="43467-154">This can take up to a few hours.</span></span> <span data-ttu-id="43467-155">После запуска установка может занять до 20 минут.</span><span class="sxs-lookup"><span data-stu-id="43467-155">After installation starts, it can take up to 20 minutes to finish.</span></span>

3. <span data-ttu-id="43467-156">После завершения установки вы получите уведомление по электронной почте, а поле на плитке подписки станет зеленым.</span><span class="sxs-lookup"><span data-stu-id="43467-156">When installation is finished, you'll be notified by email, and the box on your subscription tile will be green.</span></span>

## <a name="how-do-i-install-the-sharepoint-sample-data-pack"></a><span data-ttu-id="43467-157">Как установить пример пакета данных SharePoint?</span><span class="sxs-lookup"><span data-stu-id="43467-157">How do I install the SharePoint sample data pack?</span></span>

<span data-ttu-id="43467-158">В пример пакета данных SharePoint входят семь различных шаблонов сайтов SharePoint. Они позволяют пробовать и моделировать различные решения SharePoint для совместной работы, коммуникации, вовлечения и управления знаниями.</span><span class="sxs-lookup"><span data-stu-id="43467-158">The SharePoint sample data pack includes seven different SharePoint site templates to choose from to experience and model SharePoint solutions for collaboration, communication, engagement, and knowledge management.</span></span>

<span data-ttu-id="43467-159">Это несколько самых популярных шаблонов из [Наглядного справочника PnP SharePoint](https://provisioning.sharepointpnp.com/).</span><span class="sxs-lookup"><span data-stu-id="43467-159">These are some of the most popular templates from the [SharePoint PnP look book](https://provisioning.sharepointpnp.com/).</span></span> <span data-ttu-id="43467-160">Сегодня очень легко создавать образцы решений для красивых, быстродействующих сайтов и страниц, отлично выглядящих на любом устройстве и на любом экране.</span><span class="sxs-lookup"><span data-stu-id="43467-160">Today, it's simple to create sample solutions of beautiful, fast sites and pages that look great on any device or screen.</span></span> <span data-ttu-id="43467-161">Вдохновляйтесь этими образцами или добавьте их в клиент своей песочницы, чтобы приступить к построению следующего сайта.</span><span class="sxs-lookup"><span data-stu-id="43467-161">Get inspired with these designs or add them to your sandbox tenant to start building your next site.</span></span>

<span data-ttu-id="43467-162">Эти шаблоны можно установить в вашей подписке.</span><span class="sxs-lookup"><span data-stu-id="43467-162">The templates can be installed on your subscription.</span></span> <span data-ttu-id="43467-163">После установки одного шаблона можно по желанию установить другие.</span><span class="sxs-lookup"><span data-stu-id="43467-163">After you install one template, you have the option to install the others.</span></span> <span data-ttu-id="43467-164">Для установки выполните следующие действия.</span><span class="sxs-lookup"><span data-stu-id="43467-164">The installation process includes the following steps:</span></span>

1. <span data-ttu-id="43467-165">Выберите нужный шаблон в раскрывающемся меню.</span><span class="sxs-lookup"><span data-stu-id="43467-165">Select the Template you want from the drop down menu.</span></span>

  ![Снимок экрана: экран выбора шаблона SharePoint](images/select-sharepoint-template.jpg)

2. <span data-ttu-id="43467-167">Настройте пользовательские параметры для сайтов или примите значения по умолчанию.</span><span class="sxs-lookup"><span data-stu-id="43467-167">Configure custom options for your sites, or accept the default values.</span></span>
3. <span data-ttu-id="43467-168">Используйте ИД администратора клиента песочницы и пароль для проверки подлинности и выдачи разрешения на установку.</span><span class="sxs-lookup"><span data-stu-id="43467-168">Use the administrator ID of your sandbox tenant and password to authenticate and give permissions to install.</span></span> 

<span data-ttu-id="43467-169">Установка продолжится автоматически.</span><span class="sxs-lookup"><span data-stu-id="43467-169">Installation will proceed automatically.</span></span>

><span data-ttu-id="43467-170">**Примечание.** Подготовка этих шаблонов сайтов поддерживается только в подписках разработчиков Office 365 E3 и Microsoft 365 E5 на английском языке. Все материалы доступны только на английском языке.</span><span class="sxs-lookup"><span data-stu-id="43467-170">**Note:** The provisioning of these site templates only works with English Office 365 E3 or Microsoft 365 E5 developer subscriptions, and all content included is English only.</span></span>

## <a name="what-sharepoint-templates-are-available"></a><span data-ttu-id="43467-171">Какие шаблоны SharePoint доступны?</span><span class="sxs-lookup"><span data-stu-id="43467-171">What SharePoint templates are available?</span></span>

<span data-ttu-id="43467-172">В пример пакета SharePoint входят семь различных шаблонов.</span><span class="sxs-lookup"><span data-stu-id="43467-172">The SharePoint sample pack includes seven different templates.</span></span>

### <a name="team-site-with-data"></a><span data-ttu-id="43467-173">Сайт группы с данными</span><span class="sxs-lookup"><span data-stu-id="43467-173">Team site with data</span></span>

<span data-ttu-id="43467-174">Шаблон сайта группы с данными содержит несколько списков и библиотек документов, которые автоматически привязаны к сайту группы SharePoint. Это позволяет разрабатывать решения с помощью SharePoint Framework, Power Apps и Microsoft Graph.</span><span class="sxs-lookup"><span data-stu-id="43467-174">The Team site with data template includes multiple lists and document libraries that are automatically associated with a SharePoint team site to help you develop solutions using SharePoint Framework, Power Apps, and Microsoft Graph.</span></span>

<span data-ttu-id="43467-175">Этот шаблон включает в себя следующие данные:</span><span class="sxs-lookup"><span data-stu-id="43467-175">This template includes the following data:</span></span>

- <span data-ttu-id="43467-176">Список контактов с предварительно заполненными контактами</span><span class="sxs-lookup"><span data-stu-id="43467-176">A contact list with pre-populated contacts</span></span>
- <span data-ttu-id="43467-177">Список, заполненный более 6 000 элементами</span><span class="sxs-lookup"><span data-stu-id="43467-177">A list populated with over 6,000 items</span></span>
- <span data-ttu-id="43467-178">Библиотеки документов с примерами документов PowerPoint, Excel, Word и OneNote</span><span class="sxs-lookup"><span data-stu-id="43467-178">Document libraries with sample PowerPoint, Excel, Word, and OneNote documents</span></span>
- <span data-ttu-id="43467-179">Список событий с элементами объявлений</span><span class="sxs-lookup"><span data-stu-id="43467-179">An events list with announcement items</span></span>

<span data-ttu-id="43467-180">Этот шаблон интегрируется с примером данных "Пользователи".</span><span class="sxs-lookup"><span data-stu-id="43467-180">This template integrates with the Users sample data.</span></span>

### <a name="work--contoso"></a><span data-ttu-id="43467-181">Работа в Contoso</span><span class="sxs-lookup"><span data-stu-id="43467-181">Work @ Contoso</span></span>
<span data-ttu-id="43467-182">Шаблон "Работа в Contoso" состоит из нескольких семейств веб-сайтов, автоматически связанных с центральным сайтом для демонстрации всех стандартных функций объединения.</span><span class="sxs-lookup"><span data-stu-id="43467-182">The Work @ Contoso template consists of multiple site collections that are all automatically associated with the hub site to show how all default aggregation capabilities work.</span></span>

<span data-ttu-id="43467-183">Шаблон содержит следующие структуры и ресурсы:</span><span class="sxs-lookup"><span data-stu-id="43467-183">This template contains following structures and assets:</span></span>

- <span data-ttu-id="43467-184">Основной набор семейства веб-сайтов в качестве центрального сайта</span><span class="sxs-lookup"><span data-stu-id="43467-184">Main site collection set as a hub site</span></span>
- <span data-ttu-id="43467-185">Два информационных сайта, связанных с центральным сайтом, — сайты, посвященные преимуществам и благотворительности</span><span class="sxs-lookup"><span data-stu-id="43467-185">Two communication sites associated with the hub site - Benefits and charity sites</span></span>
- <span data-ttu-id="43467-186">Один групповой сайт команды, связанный с центральным сайтом, — сайт группы</span><span class="sxs-lookup"><span data-stu-id="43467-186">One group team site associated with the hub site - Team site</span></span>
- <span data-ttu-id="43467-187">Примеры новостных статей в семействах дочерних веб-сайтов</span><span class="sxs-lookup"><span data-stu-id="43467-187">Sample news articles in the subsite collections</span></span>
- <span data-ttu-id="43467-188">Примеры файлов Word, Excel и PowerPoint</span><span class="sxs-lookup"><span data-stu-id="43467-188">Sample Word, Excel, and PowerPoint files</span></span>
- <span data-ttu-id="43467-189">Пример контента изображений, используемого в семействах веб-сайтов</span><span class="sxs-lookup"><span data-stu-id="43467-189">Sample image content used in the site collections</span></span>

<span data-ttu-id="43467-190">В семействах дочерних веб-сайтов используются те же шаблоны, которые можно также подготовить отдельно от этой службы.</span><span class="sxs-lookup"><span data-stu-id="43467-190">Subsite collections use the same templates, which you can also provision separately from this service.</span></span>

><span data-ttu-id="43467-191">**Примечание.** Если этот шаблон применяется поверх существующего сайта для коммуникаций, содержимое страницы приветствия будет перезаписано.</span><span class="sxs-lookup"><span data-stu-id="43467-191">**Note:** If this template is applied on top of an existing communication site, the welcome page content of the site will be overwritten.</span></span>

### <a name="leadership-connection-leadership-news-events-engagement"></a><span data-ttu-id="43467-192">Руководители на связи: новости, мероприятия, вовлеченность руководителя</span><span class="sxs-lookup"><span data-stu-id="43467-192">Leadership Connection: Leadership news, events, engagement</span></span>

<span data-ttu-id="43467-193">На этом сайте для руководства можно получить представление о целях и приоритетах руководства группы. Контент сайта стимулирует вовлеченность в мероприятия и беседы.</span><span class="sxs-lookup"><span data-stu-id="43467-193">This leadership site provides insight into the goals and priorities of the leadership team, and inspires engagement with events and conversations.</span></span>

<span data-ttu-id="43467-194">При добавлении этого макета в клиент будет создан следующий контент:</span><span class="sxs-lookup"><span data-stu-id="43467-194">Adding this design to your tenant will create the following content:</span></span>

- <span data-ttu-id="43467-195">Пример страницы приветствия с демонстрацией готовых веб-частей</span><span class="sxs-lookup"><span data-stu-id="43467-195">Example welcome page with demonstration of web parts</span></span>
- <span data-ttu-id="43467-196">Примеры новостных статей, демонстрирующие различные современные макеты страниц</span><span class="sxs-lookup"><span data-stu-id="43467-196">Example news articles demonstrating different modern page designs</span></span>

<span data-ttu-id="43467-197">Этот шаблон интегрируется с примером данных "Пользователи".</span><span class="sxs-lookup"><span data-stu-id="43467-197">This template integrates with the Users sample data.</span></span>

### <a name="the-landing-news-resources-personalized-content"></a><span data-ttu-id="43467-198">Целевая страница: новости, ресурсы, персонализированное содержимое</span><span class="sxs-lookup"><span data-stu-id="43467-198">The Landing: News, resources, personalized content</span></span>

<span data-ttu-id="43467-199">Этот информационный сайт поможет вашим сотрудникам найти нужные новости и ресурсы, а также персонализированное содержимое, подобранное специально для них.</span><span class="sxs-lookup"><span data-stu-id="43467-199">This communication site is designed to be the place where your employees can find the news and resources they need, plus personalized content tailored just for them.</span></span>

<span data-ttu-id="43467-200">При добавлении этого макета в клиент будет создан следующий контент:</span><span class="sxs-lookup"><span data-stu-id="43467-200">Adding this design to your tenant will create the following content:</span></span>

- <span data-ttu-id="43467-201">Демонстрационная структура для домашнего сайта портала</span><span class="sxs-lookup"><span data-stu-id="43467-201">Demo structure for home site of the portal</span></span>
- <span data-ttu-id="43467-202">Настраиваемая структура страницы приветствия</span><span class="sxs-lookup"><span data-stu-id="43467-202">Custom welcome page structure</span></span>
- <span data-ttu-id="43467-203">6 дополнительных примеров современных страниц и новостных статей</span><span class="sxs-lookup"><span data-stu-id="43467-203">Six additional sample modern pages and news articles</span></span>
- <span data-ttu-id="43467-204">Примеры изображений и документов Office</span><span class="sxs-lookup"><span data-stu-id="43467-204">Sample images and Office documents</span></span>

### <a name="the-perspective-news-video-personalized-content"></a><span data-ttu-id="43467-205">Перспектива: новости, видео, персонализированное содержимое</span><span class="sxs-lookup"><span data-stu-id="43467-205">The Perspective: News, video, personalized content</span></span>

<span data-ttu-id="43467-206">Этот сайт, предназначенный для размещения новостей и персонализированного содержимого, содержит также видеоклипы, способствующие повышению вовлеченности.</span><span class="sxs-lookup"><span data-stu-id="43467-206">Designed to offer news and personalized content, this site also includes videos to inspire even more engagement.</span></span>
<span data-ttu-id="43467-207">При добавлении этого макета в клиент будет создан следующий контент:</span><span class="sxs-lookup"><span data-stu-id="43467-207">Adding this design to your tenant will create the following content:</span></span>

- <span data-ttu-id="43467-208">Настраиваемые макеты страницы приветствия</span><span class="sxs-lookup"><span data-stu-id="43467-208">Custom welcome page designs</span></span>
- <span data-ttu-id="43467-209">Пример шаблона страницы для новостных статей</span><span class="sxs-lookup"><span data-stu-id="43467-209">Sample page template for news articles</span></span>
- <span data-ttu-id="43467-210">12 примеров новостных статей</span><span class="sxs-lookup"><span data-stu-id="43467-210">12 sample news articles</span></span>

### <a name="new-employee-onboarding-hub-connect-engage-inform"></a><span data-ttu-id="43467-211">Центр введения в должность новых сотрудников: подключение, вовлечение, информирование</span><span class="sxs-lookup"><span data-stu-id="43467-211">New Employee Onboarding Hub: Connect, Engage, Inform</span></span>

<span data-ttu-id="43467-212">Оптимизируйте и усовершенствуйте процесс адаптации новых сотрудников с помощью готовых шаблонов, охватывающих сценарии предварительной адаптации, адаптации на корпоративном уровне и на уровне отдела.</span><span class="sxs-lookup"><span data-stu-id="43467-212">Streamline and refine your new employee onboarding process with pre-built templates that cover Pre-onboarding, Corporate-level onboarding, and Departmental-level onboarding scenarios.</span></span> <span data-ttu-id="43467-213">Это цифровое решение предлагает 4 различных шаблона сайтов, содержащих предварительно заполненный контент, который можно настроить в соответствии с целями вашей организации.</span><span class="sxs-lookup"><span data-stu-id="43467-213">This digital solution offers four different site templates that contain pre-populated content that can be customized to align with the goals of your organization.</span></span>

<span data-ttu-id="43467-214">При добавлении этого макета в клиент будет создан следующий контент:</span><span class="sxs-lookup"><span data-stu-id="43467-214">Adding this design to your tenant will create the following content:</span></span>

- <span data-ttu-id="43467-215">Сайт предварительной адаптации, сайт адаптации на корпоративном уровне и сайты адаптации на уровне подразделения</span><span class="sxs-lookup"><span data-stu-id="43467-215">Pre-onboarding site, Corporate onboarding site, and two Departmental onboarding sites</span></span>
- <span data-ttu-id="43467-216">Настраиваемые и предварительно заполненные домашние страницы для каждого сайта</span><span class="sxs-lookup"><span data-stu-id="43467-216">Custom and pre-populated home pages for each site</span></span>
- <span data-ttu-id="43467-217">Настроенный центральный сайт для адаптации на корпоративном уровне и связанные сайты для адаптации на уровне подразделения</span><span class="sxs-lookup"><span data-stu-id="43467-217">Configured hub site for Corporate onboarding and associated sites for Departmental onboarding</span></span>
- <span data-ttu-id="43467-218">Новый контрольный список сотрудников, созданный на основе списков SharePoint, чтобы помочь новым сотрудникам с успешной адаптацией</span><span class="sxs-lookup"><span data-stu-id="43467-218">New employee checklist built on SharePoint Lists to help new hires onboard successfully</span></span>
- <span data-ttu-id="43467-219">Пример содержимого для веб-части "Люди", веб-части Yammer, веб-части "Новости" и веб-части "Быстрые ссылки"</span><span class="sxs-lookup"><span data-stu-id="43467-219">Example content for the People web part, Yammer web part, News web part, and Quick links web part</span></span>
- <span data-ttu-id="43467-220">Предварительно написанные вопросы и ответы для каждого сайта</span><span class="sxs-lookup"><span data-stu-id="43467-220">Pre-written FAQs for each site</span></span>
- <span data-ttu-id="43467-221">Рекомендации по созданию привлекательных интерфейсов для социальных сетей, например по добавлению видеоприветствия с помощью веб-части YouTube на сайте предварительной адаптации</span><span class="sxs-lookup"><span data-stu-id="43467-221">Recommendations for creating social and engaging experiences, like including a welcome video using the YouTube web part on the Pre-onboarding site</span></span>

### <a name="crisis-communications-announcements-news-resources-communities-and-calls-to-action"></a><span data-ttu-id="43467-222">Коммуникации при кризисе: объявления, новости, ресурсы, сообщества и призывы к действию</span><span class="sxs-lookup"><span data-stu-id="43467-222">Crisis Communications: Announcements, news, resources, communities and calls-to-action</span></span>

<span data-ttu-id="43467-223">Держите пользователей в курсе происходящего, вовлекайте их и двигайтесь вперед во время кризисов, от экстремальных погодных явлений до чрезвычайных ситуаций санитарно-эпидемического плана или связанных с безопасностью.</span><span class="sxs-lookup"><span data-stu-id="43467-223">Keep people informed, engaged, and moving forward during crises, from extreme weather events to health and safety emergencies.</span></span> <span data-ttu-id="43467-224">Этот шаблон создает центральный ресурс для руководителей и информаторов, позволяющий обмениваться важными новостями и объявлениями; единый источник истинных сведений, позволяющий сотрудникам быть в курсе дел, и место для общения людей в организации.</span><span class="sxs-lookup"><span data-stu-id="43467-224">This template creates a central resource for leaders and communicators to share important news and announcements, a single source of truth where people can stay up-to-date, and a place to connect people across the organization.</span></span>

<span data-ttu-id="43467-225">При добавлении этого макета в клиент будет создан следующий контент:</span><span class="sxs-lookup"><span data-stu-id="43467-225">Adding this design to your tenant will create the following content:</span></span>

- <span data-ttu-id="43467-226">Настраиваемая страница приветствия, созданная с помощью веб-части</span><span class="sxs-lookup"><span data-stu-id="43467-226">Custom welcome page built using a web part</span></span>
- <span data-ttu-id="43467-227">4 новостные статьи с примерами содержимого</span><span class="sxs-lookup"><span data-stu-id="43467-227">Four news articles with example content</span></span>

<span data-ttu-id="43467-228">Этот шаблон интегрируется с примером данных "Пользователи".</span><span class="sxs-lookup"><span data-stu-id="43467-228">This template integrates with the Users sample data.</span></span>

## <a name="are-more-sample-data-packs-coming"></a><span data-ttu-id="43467-229">Ожидаются ли дополнительные примеры пакетов данных?</span><span class="sxs-lookup"><span data-stu-id="43467-229">Are more sample data packs coming?</span></span>

<span data-ttu-id="43467-230">Да.</span><span class="sxs-lookup"><span data-stu-id="43467-230">Yes.</span></span> <span data-ttu-id="43467-231">В дальнейшем мы предполагаем добавить примеры пакетов данных для других продуктов и технологий, в том числе Microsoft Teams.</span><span class="sxs-lookup"><span data-stu-id="43467-231">In the future, we will consider adding sample data packs for more products and technologies, including Microsoft Teams.</span></span> <span data-ttu-id="43467-232">Если у вас есть предложения по примерам пакетов данных, [дайте нам знать](https://officespdev.uservoice.com/forums/224641-feature-requests-and-feedback?category_id=171306).</span><span class="sxs-lookup"><span data-stu-id="43467-232">If you have suggestions for sample data packs that you would like to see, [let us know](https://officespdev.uservoice.com/forums/224641-feature-requests-and-feedback?category_id=171306).</span></span>

## <a name="can-i-install-sample-data-packs-on-my-other-microsoft-365-subscriptions"></a><span data-ttu-id="43467-233">Можно ли установить примеры пакетов данных в другие подписки на Microsoft 365?</span><span class="sxs-lookup"><span data-stu-id="43467-233">Can I install sample data packs on my other Microsoft 365 subscriptions?</span></span>

<span data-ttu-id="43467-234">Нет.</span><span class="sxs-lookup"><span data-stu-id="43467-234">No.</span></span> <span data-ttu-id="43467-235">Эти примеры пакетов данных совместимы только с подпиской разработчика на Microsoft 365, предоставляемой в рамках программы для разработчиков Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="43467-235">These sample data packs are only compatible with the Microsoft 365 developer subscription you get as part of the Microsoft 365 Developer Program.</span></span>

## <a name="how-can-i-see-the-sample-data-in-my-subscription"></a><span data-ttu-id="43467-236">Как просмотреть примеры данных в своей подписке?</span><span class="sxs-lookup"><span data-stu-id="43467-236">How can I see the sample data in my subscription?</span></span>

<span data-ttu-id="43467-237">Чтобы просмотреть добавленных пользователей после установки примера пакета данных "Пользователи", перейдите в [**Центр администрирования Microsoft 365**](https://admin.microsoft.com/), используя подписку разработчика на Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="43467-237">After you install the Users sample data pack, to see the users that were added, go to the [**Microsoft 365 Admin Center**](https://admin.microsoft.com/) on your Microsoft 365 developer subscription.</span></span> <span data-ttu-id="43467-238">В разделе **Пользователи** выберите пункт **Активные пользователи**.</span><span class="sxs-lookup"><span data-stu-id="43467-238">Under **Users**, select **Active users**.</span></span> <span data-ttu-id="43467-239">Вы увидите список 16 пользователей.</span><span class="sxs-lookup"><span data-stu-id="43467-239">You will see the list of 16 users.</span></span> <span data-ttu-id="43467-240">Вы можете выбрать пользователя, чтобы просмотреть связанные с ним метаданные, включая фотографии и лицензии.</span><span class="sxs-lookup"><span data-stu-id="43467-240">You can select a user to view the associated metadata, including photos and licenses.</span></span>

![Снимок экрана: 16 пользователей в Центре администрирования Microsoft 365 с метаданными для выбранного пользователя](images/content-packs-07.PNG)

<span data-ttu-id="43467-242">Чтобы просмотреть пример данных после установки примера пакета данных "Почта и события", в [**Центре администрирования Microsoft 365**](/microsoft-365/admin/admin-overview/about-the-admin-center?view=o365-worldwide) выберите команду **Показать все**, а затем выберите пункт **Exchange**.</span><span class="sxs-lookup"><span data-stu-id="43467-242">After you install the Mail and Events sample pack, to see the sample data, in the [**Microsoft 365 Admin Center**](/microsoft-365/admin/admin-overview/about-the-admin-center?view=o365-worldwide), choose **Show all** and then select **Exchange**.</span></span> <span data-ttu-id="43467-243">В Центре администрирования Exchange, выбрав пункт **получатели**, можно увидеть, что для каждого из 16 пользователей добавлены почтовые ящики с сообщениями и событиями.</span><span class="sxs-lookup"><span data-stu-id="43467-243">In the Exchange admin center, when you select **recipients**, you can see that each of the 16 users has mailboxes with mail and events added.</span></span>
<span data-ttu-id="43467-244">![Снимок экрана: 16 пользователей, добавленных в Центр администрирования Exchange](images/content-packs-08.PNG)</span><span class="sxs-lookup"><span data-stu-id="43467-244">![Screenshot of 16 users added to the Exchange Admin Center](images/content-packs-08.PNG)</span></span>

## <a name="see-also"></a><span data-ttu-id="43467-245">См. также</span><span class="sxs-lookup"><span data-stu-id="43467-245">See also</span></span>

- [<span data-ttu-id="43467-246">Настройка подписки разработчика Microsoft 365</span><span class="sxs-lookup"><span data-stu-id="43467-246">Set up a Microsoft 365 developer subscription</span></span>](microsoft-365-developer-program-get-started.md)

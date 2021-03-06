---
title: 设置 Microsoft 365 开发人员订阅
description: 设置 Microsoft 365 开发人员订阅，构建独立于你的生产环境的解决方案。
ms.date: 04/01/2019
localization_priority: Priority
ms.openlocfilehash: 4aa500e0688c43186d574e94e3f94081a87b89e4
ms.sourcegitcommit: 9c7a1aa1c562adb350fefc8068e154fa6f9a4ee3
ms.translationtype: HT
ms.contentlocale: zh-CN
ms.lasthandoff: 03/11/2020
ms.locfileid: "42601283"
---
# <a name="set-up-a-microsoft-365-developer-subscription"></a>设置 Microsoft 365 开发人员订阅 

设置 Microsoft 365 开发人员订阅，构建独立于生产环境的解决方案。 此订阅为 Microsoft 365 E5 开发人员订阅，随附 25 个用户许可证。 许可证有效期为 90 天，仅可用于开发目的（编码解决方案）。 

在 2019 年 8 月 25 日之前加入该计划的客户可获得 Office 365 E3 开发人员订阅。

> [!NOTE] 
> 要设置订阅，必须先[加入 Microsoft 365 开发人员计划](microsoft-365-developer-program.md)。 加入后，即可看到设置订阅的选项。

## <a name="set-up-your-subscription"></a>设置订阅

1. 要获取 Microsoft 365 开发人员订阅，请在配置文件页面上，选择“**设置订阅**”。

2. 在 **设置开发人员订阅** 对话框中，创建一个用户名和域。 此帐户必须具有订阅的全局管理员权限。 可选择任何用户名或域名（只要没有被用过）。 请勿使用空格。

  ![设置订阅表单](images/5-set-up-form.png)

3. 创建并确认密码。

4. 选择 **设置**。

5. 如果要求你证明你不是机器人，请按照说明，然后选择“**验证**”。

6. 创建好订阅后，订阅名称和到期日期会出现在配置文件页。

  > [!IMPORTANT]
  > 记下用户名和密码，因为需要用它来访问开发人员订阅。

## <a name="configure-the-subscription"></a>配置订阅

1. 在配置文件页，选择“**转到订阅**”，然后使用为开发人员订阅指定的用户 ID（例如，username@domain.onmicrosoft.com）和密码进行登录。

   > [!NOTE] 
   > 请不要使用开发人员计划帐户 ID 登录到订阅。

2. 使用应用启动器转到 [管理员中心](https://admin.microsoft.com/AdminPortal/Home#/homepage)。

3. 在管理员中心主页上，选择 **转到设置**。 这会转到 **Microsoft 365 E5 开发人员设置**页面。

4. **个性化设置登录和电子邮件**。 可以将订阅连接到域，或只需使用你创建的现有子域。 准备就绪后，选择 **下一步**。

5. **添加新用户**。 可添加虚构或真实的用户来帮助你进行开发。 准备就绪后，选择“**下一步**”。
    
  > [!NOTE]
  > 设置订阅后，可安装用户示例数据包。 用户示例数据包将在你的订阅上创建 16 个虚构用户，并包含每位用户的许可证、邮箱、姓名、元数据和照片。 有关详细信息，请参阅[安装示例数据包](install-sample-packs.md)。

6. **向未经授权用户分配许可证**。 对于你想让其能够使用订阅的任何用户，向其授予许可证。 准备就绪后，选择 **下一步**。

7. **共享登录凭据**。 对于将访问订阅的任何真实用户，必须与其共享其登录凭据。 可以选择一种方法，如电子邮件、 下载或打印。 准备就绪后，选择 **下一步**。

8. **安装 Office 应用**。 可以选择在电脑上安装 Office 应用。 准备就绪后，选择 **下一步**。

   > [!TIP] 
   > 随后访问仪表板时，转到仪表板之前请用你*username@domain*. onmicrosoft.com 帐户。

9. **您已达到设置过程的结尾**。 已完成订阅设置。 您可以选择评价体验。 准备就绪后，选择 **转到管理员中心**。
    
   > [!NOTE] 
   > 目前，无论您在哪个国家/地区，订阅的地区默认为北美。 仍可以继续进行设置并使用开发人员订阅。

## <a name="provision-microsoft-365-services"></a>预配 Microsoft 365 服务

后端服务需要一些时间来预配订阅，例如 SharePoint 和 Exchange。 在此步骤期间，应用启动器中和主页上一些图标显示为**设置中 （此应用仍在设置中）**。 此步骤不会超过一个小时。

预配完成后，即可使用新的 Microsoft 365 订阅用于开发。 订阅 90 天后到期。 如果要延期，请查看[我的订阅将要到期时，我是否可以续订？](microsoft-365-developer-program-faq.md#renew-subscription)

我们还建议启用版本选项以确保你可以尽快访问新的 Microsoft 365 功能。 有关详细信息，请参阅[设置标准或定向版本选项](https://support.office.com/article/set-up-the-standard-or-targeted-release-options-in-office-365-3b3adfa4-1777-4ff0-b606-fb8732101f47)。

## <a name="set-up-a-microsoft-azure-account"></a>设置 Microsoft Azure 帐户

对于一些 Office 解决方案，可能需要 Microsoft Azure 帐户使用 Azure 服务来构建。 若要设置免费 Azure 帐户，请参阅 [立即创建 Azure 免费帐户](https://azure.microsoft.com/free/)。

## <a name="install-sample-data-packs"></a>安装示例数据包

可以在 Microsoft 365 开发人员计划订阅上安装示例数据包。 示例数据包可自动安装构建和测试解决方案所需的数据和内容，从而节省你的时间。 其中包含虚构用户、元数据和照片，用于模拟小型企业环境。 有关可用的示例数据包及其安装方式的详细信息，请参阅[安装示例数据包](install-sample-packs.md)。

## <a name="see-also"></a>另请参阅

- [加入 Microsoft 365 开发人员计划团队](microsoft-365-developer-program.md)
- [使用你的订阅来构建 Microsoft 365 解决方案](build-microsoft-365-solutions.md)
- [续订即将到期的订阅](subscription-expiration-and-renewal.md)
- [Microsoft 365 开发人员计划常见问题解答](microsoft-365-developer-program-faq.md)

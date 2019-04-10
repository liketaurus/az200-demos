# AZ-200: Azure Developer, Core Solutions
*материалы для проведения курса*

![](https://img.shields.io/badge/made%20for-classroom-green.svg)  ![](https://img.shields.io/badge/made%20with-C%23-red.svg)  ![](https://img.shields.io/badge/temporary-code-blue.svg)

- **[Описание программы](http://nt.ua/education/microsoft/Pages/AZ-200.aspx)**
- Структура программы:
  - **AZ-200T01** Select the appropriate Azure technology development solution
  - **AZ-200T02** Develop for Azure storage
  - **AZ-200T03** Develop Azure Platform as a Service solutions
  - **AZ-200T04** Implement security in Azure development solutions

  Полные официальные описания курсов - в [каталоге IT-тренингов Microsoft](https://www.microsoft.com/en-us/learning/course-list.aspx)

## Почему был создан этот репозиторий?
Причина проста - есть тренинги, которые пришли на смену курсу [20532](https://github.com/MicrosoftLearning/20532-DevelopingMicrosoftAzureSolutions), но репозитория в его поддержку (как, например, в поддержку [AZ-100](https://github.com/MicrosoftLearning/AZ-100-MicrosoftAzureInfrastructureDeployment)) нет, плюс нужно же что-то демонстрировать студентам курса! Поэтому был создан форк [оригинального репозитория](https://github.com/GKLabContent/az200-demos) от **@GKLabContent**, и я попытался чуть упорядочить и адаптировать под свои потребности его содержимое.

## Материалы "предыдущих" курсов по Azure
- [20532D: Developing Microsoft Azure Solutions](https://github.com/MicrosoftLearning/20532-DevelopingMicrosoftAzureSolutions)
- [20535A: Architecting Microsoft Azure Solutions](https://github.com/MicrosoftLearning/20535-ArchitectingMicrosoftAzureSolutions)

- [20533: ImplementingMicrosoftAzureInfrastructureSolutions](https://github.com/MicrosoftLearning/20533-ImplementingMicrosoftAzureInfrastructureSolutions)

## Как материалы "предыдущих" курсов соотносятся с AZ-200
Пока можно сопоставить лабораторные работы "предыдущих" курсов с составляющими новой программы таким образом:
- **AZ-200T01**
  - работа [**2** (VM)](https://github.com/MicrosoftLearning/20532-DevelopingMicrosoftAzureSolutions/blob/master/Instructions/Labs/Mod02/LAB_AK_02.md) из курса 20532
  - работа [**3** (Web App, Function App)](https://github.com/MicrosoftLearning/20532-DevelopingMicrosoftAzureSolutions/blob/master/Instructions/Labs/Mod03/LAB_AK_03.md) из курса 20532
- **AZ-200T02**
  - работа [**6** (CosmosDB)](https://github.com/MicrosoftLearning/20532-DevelopingMicrosoftAzureSolutions/blob/master/Instructions/Labs/Mod06/LAB_AK_06.md) из курса 20532
  - работа [7 (Blobs)](https://github.com/MicrosoftLearning/20532-DevelopingMicrosoftAzureSolutions/blob/master/Instructions/Labs/Mod07/LAB_AK_07.md) из того же курса
  - также (*если останется время*) можно рассмотреть работу [4 (Azure SQL)](https://github.com/MicrosoftLearning/20532-DevelopingMicrosoftAzureSolutions/blob/master/Instructions/Labs/Mod04/LAB_AK_04.md)
- **AZ-200Т03**
  - работа [**10** (Logic App, Function App, Cognitive Services)](https://github.com/MicrosoftLearning/20535-ArchitectingMicrosoftAzureSolutions/blob/master/Instructions/Labs/Mod10/20535A_LAB_AK_10.md) из курса 20535
  - работа [**7** (Containers)](https://github.com/MicrosoftLearning/20533-ImplementingMicrosoftAzureInfrastructureSolutions/blob/master/Instructions/20533E_LAB_AK_07.md) из курса 20533 ([инструкция](https://github.com/liketaurus/az200-demos-snippets/blob/master/AZ200T03/How%20to%20get%2020533%20scripts%20working.md), как подключить модули для подготовки среды)
- **AZ-200T04**
  - работа [**11** (Azure AD)](https://github.com/MicrosoftLearning/20532-DevelopingMicrosoftAzureSolutions/blob/master/Instructions/Labs/Mod11/LAB_AK_11.md) из курса 20532
  - также (*если останется время*) можно рассмотреть работу [9 (Key Vault)](https://github.com/MicrosoftLearning/20535-ArchitectingMicrosoftAzureSolutions/blob/master/Instructions/Labs/Mod09/20535A_LAB_AK_09.md) из курса 20535

## "Новые" лабораторные работы?

Уверен, со временем на [Microsoft Online Labs](https://www.microsoft.com/handsonlabs/SelfPacedLabs) появятся лабораторные работы, на которые ссылаются слайды курсов, составляющих эту программу обучения``*``

Кстати, стоит зарегистрироваться уже сейчас - там уже есть на что посмотреть и что попробовать. Точно так же стоит заглянуть на [Microsoft Learn](https://docs.microsoft.com/en-us/learn/browse/?roles=developer&products=azure) - там уже есть много полезных тренингов для Azure-разработчиков.

## Дополнительные материалы
- описание сертификационного экзамена [AZ-200](https://www.microsoft.com/en-us/learning/exam-az-200.aspx)
- полный [каталог сертфициационных экзаменов Microsoft](https://www.microsoft.com/en-us/learning/exam-list.aspx)
- [Microsoft Certifications Guide](https://www.certificationcamps.com/microsoft-certifications-guide/)
- [Azure for .NET and .NET Core developers](https://docs.microsoft.com/en-us/dotnet/azure/)
- [Azure Code Samples](https://azure.microsoft.com/en-us/resources/samples/?platform=dotnet&sort=2)
- [Free eBook – The Developer’s Guide to Microsoft Azure](https://azure.microsoft.com/en-us/blog/free-ebook-the-developer-s-guide-to-microsoft-azure-now-available/)
- [Build Azure: Books](https://buildazure.com/book/)

``*`` Увы, больше ничего не появится - **с 1 апреля 2019 года программы подготовки AZ-200 и AZ-201 заменяются новой комплексной программой AZ-203**. Подробнее - [здесь](https://www.wintellect.com/course/az-200-microsoft-azure-developer-core-solutions-certification-track/)

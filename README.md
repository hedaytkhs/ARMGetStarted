# ARMGetStarted

## はじめに
Azure App Service や Azure Functions のリソース作成を自動化するARMテンプレートを使い始めるためのサンプルなどをまとめるリポジトリです。

### リソース グループを作成する Bicep テンプレート
リソース グループを作るだけ。

ただ、それだけだけれども、いちいちAzure Portal から作ったり、PowerShell を実行するのが面倒だ、というときがあると思う。

リソース グループを作っては削除して、ということをやるのであれば、Bicep テンプレートから作成できるようしておく、というのでもよいと思う。

[Create a resourceGroup](https://github.com/azure/azure-quickstart-templates/tree/master/subscription-deployments/create-rg#create-a-resourcegroup)

### Storage アカウントを作成する Bicep テンプレート

ファイル共有をもつ Storage アカウントを作成する

[Create a storage account with file share](https://github.com/azure/azure-quickstart-templates/tree/master/quickstarts/microsoft.storage/storage-file-share#create-a-storage-account-with-file-share)


### Function App デプロイ用の 各種 ARM / Bicep テンプレート

サンプルのARM テンプレート一覧

[ARM Templates for Function App Deployment](https://learn.microsoft.com/ja-jp/samples/azure-samples/function-app-arm-templates/arm-templates-for-function-app-deployment/?ns-enrollment-type=Collection&ns-enrollment-id=5myt1yx0wp7wz)

Azure Functions のリソースを作成するBicep テンプレート

[Function App](https://github.com/azure/azure-quickstart-templates/tree/master/quickstarts/microsoft.web/app-function#function-app)

従量課金プラン

[Provision a function app on a Consumption plan](https://github.com/azure/azure-quickstart-templates/tree/master/quickstarts/microsoft.web/function-app-create-dynamic#provision-a-function-app-on-a-consumption-plan)

Windows 従量課金プラン

[Azure Function App Hosted on Windows Consumption Plan](https://github.com/azure-samples/function-app-arm-templates/tree/main/function-app-windows-consumption)

Linux 従量課金プラン

[Azure Function App Hosted on Linux Consumption Plan](https://github.com/azure-samples/function-app-arm-templates/tree/main/function-app-linux-consumption#azure-function-app-hosted-on-linux-consumption-plan)

HTTPトリガー関数の簡単なテストを行うために Function App を作成したいときのために 自分用にBicep テンプレートを持っておくと便利

[Azure Function app and an HTTP-triggered function](https://github.com/azure/azure-quickstart-templates/tree/master/quickstarts/microsoft.web/function-http-trigger)

[Azure Function App with Event Hub and Managed Identity](https://github.com/azure/azure-quickstart-templates/tree/master/quickstarts/microsoft.web/function-app-event-hub-managed-identity#azure-function-app-with-event-hub-and-managed-identity)

Premium プラン

Premium プラン (VNet 統合)の Function App を作成する

[Deploy an Azure Function Premium plan with vnet integration](https://github.com/azure/azure-quickstart-templates/tree/master/quickstarts/microsoft.web/function-premium-vnet-integration)

デプロイスロットテストを行うためにPremium プラン Function App を作成したいときのためのBicep テンプレート

[Azure Function App with a Deployment Slot](https://github.com/azure-samples/function-app-arm-templates/tree/main/function-app-deployment-slot)


プライベートエンドポイントで保護されたストレージ をもつ Function App をデプロイする

[Create Function App and private endpoint-secured Storage](https://github.com/azure/azure-quickstart-templates/tree/master/quickstarts/microsoft.web/function-app-storage-private-endpoints)


App Service (専用)プラン の Function App を作成する

[Provision a function app running on an App Service Plan](https://learn.microsoft.com/ja-jp/samples/azure/azure-quickstart-templates/function-app-create-dedicated/)

プライベートリンクを経由して Azure Digital Twins へ通信するリソースを作成する Bicep テンプレート

[Azure Digital Twins with Function and Private Link service](https://github.com/azure/azure-quickstart-templates/tree/master/quickstarts/microsoft.digitaltwins/digitaltwins-with-function-private-link#azure-digital-twins-with-function-and-private-link-service)

### すぐに使える状態にしておく

自分の GitHub リポジトリにフォークしておき、いつでもすぐに使える状態にしておく。

### Web App デプロイ用の 各種 ARM テンプレート

### Web App デプロイ用の Bicep テンプレート

Windows Web App

[App Service Quickstart - Windows app](https://github.com/azure/azure-quickstart-templates/tree/master/quickstarts/microsoft.web/webapp-basic-windows)

基本的な Linux Web App

[Deploy a basic Linux web app](https://github.com/azure/azure-quickstart-templates/tree/master/quickstarts/microsoft.web/webapp-basic-linux)

Java 13, Tomcat 9 を有効にした Web App をデプロイする

[Create a web app on Azure with Java 13 and Tomcat 9 enabled](https://github.com/azure/azure-quickstart-templates/tree/master/quickstarts/microsoft.web/web-app-java-tomcat#create-a-web-app-on-azure-with-java-13-and-tomcat-9-enabled)

リージョナル VNet 統合を有効にした App Service をデプロイする

[Deploy an app service with regional VNet integration](https://github.com/azure/azure-quickstart-templates/tree/master/quickstarts/microsoft.web/app-service-regional-vnet-integration#deploy-an-app-service-with-regional-vnet-integration)

Web App と Azure SQL Databaseをデプロイする

[Provision a Web App with a SQL Database](https://github.com/azure/azure-quickstart-templates/tree/master/quickstarts/microsoft.web/web-app-sql-database)

Web App w/ Application Insights sending to Log Analytics

[Web App w/ Application Insights sending to Log Analytics](https://github.com/azure/azure-quickstart-templates/tree/master/quickstarts/microsoft.web/web-app-loganalytics)

Web App on Linux へ Django Web アプリをデプロイする

[Django app](https://github.com/azure/azure-quickstart-templates/tree/master/quickstarts/microsoft.web/webapp-linux-django#django-app)

Flask アプリを デプロイするための App Service リソースを作成する

[Flask app service](https://github.com/azure/azure-quickstart-templates/tree/master/quickstarts/microsoft.web/webapp-linux-flask#flask-app-service)

### Azure Spring App のマイクロサービスをデプロイする Bicep テンプレート

[Deploy a simple Azure Spring Apps microservice application](https://github.com/azure/azure-quickstart-templates/tree/master/quickstarts/microsoft.appplatform/microservice-apps-enterprise-plan#deploy-a-simple-azure-spring-apps-microservice-application)

### スケーリングルールの設定された Azure Container App をデプロイする

[Creates a Container App with a defined HTTP scaling rule](https://github.com/azure/azure-quickstart-templates/tree/master/quickstarts/microsoft.app/container-app-scale-http)

### VNet 経由の Container App 環境をデプロイする

[Creates an internal Container App environment with a VNE](https://github.com/azure/azure-quickstart-templates/tree/master/quickstarts/microsoft.app/container-app-vnet-internal-environment)

### Linux VM デプロイ用の Bicep テンプレート

[Deploy a simple Ubuntu Linux VM 18.04-LTS](https://github.com/azure/azure-quickstart-templates/tree/master/quickstarts/microsoft.compute/vm-simple-linux#deploy-a-simple-ubuntu-linux-vm-1804-lts)


### API Management (Premium) マルチリージョンへのデプロイ用の Bicep テンプレート

[Create a multiregion Premium tier API Management instance](https://github.com/azure/azure-quickstart-templates/tree/master/quickstarts/microsoft.apimanagement/api-management-create-with-multiregion#create-a-multiregion-premium-tier-api-management-instance)

### API Management の可用性ゾーンへのデプロイ用の Bicep テンプレート

[Deploy API Management into Availability Zones](https://github.com/azure/azure-quickstart-templates/tree/master/quickstarts/microsoft.apimanagement/api-management-simple-zones#deploy-api-management-into-availability-zones)

### プライベートエンドポイントをもつAPI Management をデプロイする Bicep テンプレート

[Create an API Management service with a private endpoint](https://github.com/azure/azure-quickstart-templates/tree/master/quickstarts/microsoft.apimanagement/api-management-private-endpoint#create-an-api-management-service-with-a-private-endpoint)

### Container Apps で Dapr PubSub の Service busをデプロイする Bicep テンプレート

[Creates a Dapr pub-sub servicebus app using Container Apps](https://github.com/azure/azure-quickstart-templates/tree/master/quickstarts/microsoft.app/container-app-dapr-pubsub-servicebus)

### Web PubSub をデプロイする Bicep テンプレート

[Create Azure Web PubSub by using Bicep](https://github.com/azure/azure-quickstart-templates/tree/master/quickstarts/microsoft.web/azure-web-pubsub)

### Container Apps 環境に Container Apps をデプロイする

[Creates a Container App within a Container App Environment](https://github.com/azure/azure-quickstart-templates/tree/master/quickstarts/microsoft.app/container-app-create)

### Container Apps で Dapr をデプロイする

[Creates a Dapr microservices app using Container Apps](https://github.com/azure/azure-quickstart-templates/tree/master/quickstarts/microsoft.app/container-app-dapr-blob)

### Sonarqube の Docker イメージを使って Web App on Linux とPostgreSQL をデプロイする

[Sonarqube Docker Web App on Linux with PostgreSQL](https://github.com/azure/azure-quickstart-templates/tree/master/quickstarts/microsoft.web/webapp-linux-sonarqube-postgresql)

### Service Bus の namespace とqueue をデプロイする

[Create a Service Bus namespace and queue](https://github.com/azure/azure-quickstart-templates/tree/master/quickstarts/microsoft.servicebus/servicebus-create-queue)

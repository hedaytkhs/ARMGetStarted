# ARMGetStarted

## はじめに
Azure App Service や Azure Functions のリソース作成を自動化するARMテンプレートを使い始めるためのサンプルなどをまとめるリポジトリです。

### リソース グループを作成する Bicep テンプレート
リソース グループを作るだけ。

ただ、それだけだけれども、いちいちAzure Portal から作ったり、PowerShell を実行するのが面倒だ、というときがあると思う。

リソース グループを作っては削除して、ということをやるのであれば、Bicep テンプレートから作成できるようしておく、というのでもよいと思う。

[Create a resourceGroup](https://github.com/azure/azure-quickstart-templates/tree/master/subscription-deployments/create-rg#create-a-resourcegroup)

### Function App デプロイ用の 各種 ARM / Bicep テンプレート

サンプルのARM テンプレート一覧

[ARM Templates for Function App Deployment](https://learn.microsoft.com/ja-jp/samples/azure-samples/function-app-arm-templates/arm-templates-for-function-app-deployment/?ns-enrollment-type=Collection&ns-enrollment-id=5myt1yx0wp7wz)

Azure Functions のリソースを作成するBicep テンプレート

従量課金プラン

[Provision a function app on a Consumption plan](https://github.com/azure/azure-quickstart-templates/tree/master/quickstarts/microsoft.web/function-app-create-dynamic#provision-a-function-app-on-a-consumption-plan)

[Azure Function App Hosted on Linux Consumption Plan](https://github.com/azure-samples/function-app-arm-templates/tree/main/function-app-linux-consumption#azure-function-app-hosted-on-linux-consumption-plan)

[Azure Function App with Event Hub and Managed Identity](https://github.com/azure/azure-quickstart-templates/tree/master/quickstarts/microsoft.web/function-app-event-hub-managed-identity#azure-function-app-with-event-hub-and-managed-identity)

プライベートリンクを経由して Azure Digital Twins へ通信するリソースを作成する Bicep テンプレート

[Azure Digital Twins with Function and Private Link service](https://github.com/azure/azure-quickstart-templates/tree/master/quickstarts/microsoft.digitaltwins/digitaltwins-with-function-private-link#azure-digital-twins-with-function-and-private-link-service)

### すぐに使える状態にしておく

自分の GitHub リポジトリにフォークしておき、いつでもすぐに使える状態にしておく。

### Web App デプロイ用の 各種 ARM テンプレート

### Web App デプロイ用の Bicep テンプレート

Java 13, Tomcat 9 を有効にした Web App をデプロイする

[Create a web app on Azure with Java 13 and Tomcat 9 enabled](https://github.com/azure/azure-quickstart-templates/tree/master/quickstarts/microsoft.web/web-app-java-tomcat#create-a-web-app-on-azure-with-java-13-and-tomcat-9-enabled)

リージョナル VNet 統合を有効にした App Service をデプロイする

[Deploy an app service with regional VNet integration](https://github.com/azure/azure-quickstart-templates/tree/master/quickstarts/microsoft.web/app-service-regional-vnet-integration#deploy-an-app-service-with-regional-vnet-integration)

Web App on Linux へ Django Web アプリをデプロイする

[Django app](https://github.com/azure/azure-quickstart-templates/tree/master/quickstarts/microsoft.web/webapp-linux-django#django-app)

### Azure Spring App のマイクロサービスをデプロイする Bicep テンプレート

[Deploy a simple Azure Spring Apps microservice application](https://github.com/azure/azure-quickstart-templates/tree/master/quickstarts/microsoft.appplatform/microservice-apps-enterprise-plan#deploy-a-simple-azure-spring-apps-microservice-application)


### Linux VM デプロイ用の Bicep テンプレート

[Deploy a simple Ubuntu Linux VM 18.04-LTS](https://github.com/azure/azure-quickstart-templates/tree/master/quickstarts/microsoft.compute/vm-simple-linux#deploy-a-simple-ubuntu-linux-vm-1804-lts)


### API Management (Premium) マルチリージョンへのデプロイ用の Bicep テンプレート

[Create a multiregion Premium tier API Management instance](https://github.com/azure/azure-quickstart-templates/tree/master/quickstarts/microsoft.apimanagement/api-management-create-with-multiregion#create-a-multiregion-premium-tier-api-management-instance)

### API Management の可用性ゾーンへのデプロイ用の Bicep テンプレート

[Deploy API Management into Availability Zones](https://github.com/azure/azure-quickstart-templates/tree/master/quickstarts/microsoft.apimanagement/api-management-simple-zones#deploy-api-management-into-availability-zones)

### プライベートエンドポイントをもつAPI Management をデプロイする Bicep テンプレート

[Create an API Management service with a private endpoint](https://github.com/azure/azure-quickstart-templates/tree/master/quickstarts/microsoft.apimanagement/api-management-private-endpoint#create-an-api-management-service-with-a-private-endpoint)

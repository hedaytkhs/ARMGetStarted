# ARMGetStarted

## はじめに
Azure App Service や Azure Functions のリソース作成を自動化するARMテンプレートを使い始めるためのサンプルなどをまとめるリポジトリです。

### リソース グループを作成する Bicep テンプレート
リソース グループを作るだけ。

ただ、それだけだけれども、いちいちAzure Portal から作ったり、PowerShell を実行するのが面倒だ、というときがあると思う。

リソース グループを作っては削除して、ということをやるのであれば、Bicep テンプレートから作成できるようしておく、というのでもよいと思う。

[Create a resourceGroup](https://github.com/azure/azure-quickstart-templates/tree/master/subscription-deployments/create-rg#create-a-resourcegroup)

### Function App デプロイ用の 各種 ARM テンプレート

サンプルのARM テンプレート一覧

[ARM Templates for Function App Deployment](https://learn.microsoft.com/ja-jp/samples/azure-samples/function-app-arm-templates/arm-templates-for-function-app-deployment/?ns-enrollment-type=Collection&ns-enrollment-id=5myt1yx0wp7wz)

### すぐに使える状態にしておく

自分の GitHub リポジトリにフォークしておき、いつでもすぐに使える状態にしておく。

### Web App デプロイ用の 各種 ARM テンプレート

### Web App デプロイ用の Bicep テンプレート

[Deploy an app service with regional VNet integration](https://github.com/azure/azure-quickstart-templates/tree/master/quickstarts/microsoft.web/app-service-regional-vnet-integration#deploy-an-app-service-with-regional-vnet-integration)

### Azure Spring App のマイクロサービスをデプロイする Bicep テンプレート

[Deploy a simple Azure Spring Apps microservice application](https://github.com/azure/azure-quickstart-templates/tree/master/quickstarts/microsoft.appplatform/microservice-apps-enterprise-plan#deploy-a-simple-azure-spring-apps-microservice-application)


### Linux VM デプロイ用の Bicep テンプレート

[Deploy a simple Ubuntu Linux VM 18.04-LTS](https://github.com/azure/azure-quickstart-templates/tree/master/quickstarts/microsoft.compute/vm-simple-linux#deploy-a-simple-ubuntu-linux-vm-1804-lts)


### API Management (Premium) マルチリージョンへのデプロイ用の Bicep テンプレート

[Create a multiregion Premium tier API Management instance](https://github.com/azure/azure-quickstart-templates/tree/master/quickstarts/microsoft.apimanagement/api-management-create-with-multiregion#create-a-multiregion-premium-tier-api-management-instance)

### API Management の可用性ゾーンへのデプロイ用の Bicep テンプレート

[Deploy API Management into Availability Zones](https://github.com/azure/azure-quickstart-templates/tree/master/quickstarts/microsoft.apimanagement/api-management-simple-zones#deploy-api-management-into-availability-zones)

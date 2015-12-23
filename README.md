# arm-shadow-pod
Azure ARM Templates for Development POD

azure group create shadow-pod "North Central US"
azure group deployment create -f azuredeploy.json -e parameters.json shadow-pod pod

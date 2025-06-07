# we nee to create 4 k8s config files:

1. configmap = for mongodb endpoint
2. secret = for mongodb credentials
3. deployment & servive = for mongodb application with internal service
4. deployment & service = for our webapp with external service

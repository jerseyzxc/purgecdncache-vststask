# Purge Azure CDN

This task allows you to purge content of an Azure CDN within a pipeline.

# Documentation

### Select Azure Connection Type
- Azure Classic
- Azure Resource Manager

![image](https://github.com/jerseyzxc/purgecdncache-vststask/assets/118034690/37355fd4-8af2-4650-befd-7005aef08301)

### Select your Subscription from the dropdown list.

![image](https://github.com/jerseyzxc/purgecdncache-vststask/assets/118034690/e687fba6-3ba6-4327-a22f-81f25e9dbe25)
   
### Specify Resource group, Endpoint and Profile names of the CDN Endpoint.

![image](https://github.com/jerseyzxc/purgecdncache-vststask/assets/118034690/52bee348-a3e5-4a58-9c52-f1853ce87f1e)

### Specify the path for the content on the origin server to purge. You may enter one path per line.

![image](https://github.com/jerseyzxc/purgecdncache-vststask/assets/118034690/ce0dac5b-855f-4b17-9ec4-13d8f9425232)

> To purge everything, type "/*"

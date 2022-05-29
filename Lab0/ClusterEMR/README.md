# Create EMR

Search Elastic Map Reduce or EMR and click

<img width="709" alt="image" src="https://user-images.githubusercontent.com/53051443/170846800-e38a671c-9fc3-4972-a5f7-98dbb13b422d.png">



### NOTE 

First Create a keys in aws, for create a ERM Service 

<img width="674" alt="image" src="https://user-images.githubusercontent.com/53051443/170846937-2e6a23c8-7c43-4f17-b23a-1ff1b797d5ca.png">

<img width="960" alt="image" src="https://user-images.githubusercontent.com/53051443/170846950-e9382909-e172-48e7-992c-c78c41efeedc.png">

<img width="728" alt="image" src="https://user-images.githubusercontent.com/53051443/170846970-856fddcb-80ee-4cb0-833e-1cdc74f48253.png">

# EMR

## EMR Screen

<img width="960" alt="image" src="https://user-images.githubusercontent.com/53051443/170846845-b2062ac9-0186-443b-b466-dd6234286f3b.png">

Click on create cluster, then click on Advanced option 

<img width="960" alt="image" src="https://user-images.githubusercontent.com/53051443/170847109-5f6cc483-9aa6-4654-b9c9-69c7c4bbc7d9.png">

Then click in this components
<img width="960" alt="image" src="https://user-images.githubusercontent.com/53051443/170847155-354a4a1a-a1a1-4610-b716-b851de99610e.png">

<img width="960" alt="image" src="https://user-images.githubusercontent.com/53051443/170847164-de88aee2-eb60-4201-9cc8-1e8ae5c60e5d.png">

<img width="887" alt="image" src="https://user-images.githubusercontent.com/53051443/170847209-f1f7bcef-2bcb-47b6-8b64-73145bc43033.png">
```json

[
    {
        "Classification": "jupyter-s3-conf",
        "Properties": {
            "s3.persistence.enabled": "true",
            "s3.persistence.bucket": "bucketnamecreated" 
        }
    }
]
```




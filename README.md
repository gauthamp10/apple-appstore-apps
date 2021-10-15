## Apple AppStore Apps (Backup Repo)

### Application data of 1.2 million ios application from Apple AppStore.
<img src="banner.png" width="440" height="200" />


For latest dataset updates. Download from Kaggle: https://www.kaggle.com/gauthamp10/apple-appstore-apps

I've collected the data with the help of Python and Scrapy running on a  cluster of cloud virtual machines.
The data was collected on October 2021.

<br/>

### Instructions to extract dataset

```
git clone https://github.com/gauthamp10/apple-appstore-apps.git

cd apple-appstore-apps/dataset/

tar -xvf appleAppData.json.tar.lzma

```

### Sample

```
[
  {
    "App_Id": "com.apple.Pages",
    "App_Name": "Pages",
    "AppStore_Url": "https://apps.apple.com/us/app/pages/id361309726?uo=4",
    "Primary_Genre": "Productivity",
    "Content_Rating": "4+",
    "Size_Bytes": "498595840",
    "Required_IOS_Version": "14.0",
    "Released": "2010-04-01T20:36:57Z",
    "Updated": "2021-09-28T15:27:20Z",
    "Version": "11.2",
    "Price": 0.0,
    "Currency": "USD",
    "Free": true,
    "DeveloperId": 284417353,
    "Developer": "Apple",
    "Developer_Url": "https://apps.apple.com/us/developer/apple/id284417353?mt=12&uo=4",
    "Developer_Website": "http://www.apple.com/pages/",
    "Average_User_Rating": 3.40115,
    "Reviews": 19419,
    "Current_Version_Score": 3.40115,
    "Current_Version_Reviews": 19419
  },
  {
    "App_Id": "com.apple.iBooks",
    "App_Name": "Apple Books",
    "AppStore_Url": "https://apps.apple.com/us/app/apple-books/id364709193?uo=4",
    "Primary_Genre": "Book",
    "Content_Rating": "4+",
    "Size_Bytes": "15949824",
    "Required_IOS_Version": "10.0",
    "Released": "2010-04-02T04:36:45Z",
    "Updated": "2021-09-20T17:13:29Z",
    "Version": "4.2.6",
    "Price": 0.0,
    "Currency": "USD",
    "Free": true,
    "DeveloperId": 284417353,
    "Developer": "Apple",
    "Developer_Url": "https://apps.apple.com/us/developer/apple/id284417353?mt=12&uo=4",
    "Developer_Website": "http://apple.com/apple-books/",
    "Average_User_Rating": 3.316,
    "Reviews": 250,
    "Current_Version_Score": 3.316,
    "Current_Version_Reviews": 250
  }
]

```
Also checkout:

- Google Play Store Apps dataset: https://www.kaggle.com/gauthamp10/google-playstore-apps
- Android App Permission dataset: https://www.kaggle.com/gauthamp10/app-permissions-android


### Acknowledgements

I couldn't have build this dateset without the help of Digitalocean and github.

### __Author__

 **Gautham Prakash**
 
  My other projects: [github.com/gauthamp10](https://github.com/gauthamp10)

  Website: [gauthamp10.github.io](https://gauthamp10.github.io)


### __License__  

This project is licensed under the  License - see the THE CREATIVE COMMONS ATTRIBUTION 4.0 INTERNATIONAL [LICENSE](LICENSE.md) file for details


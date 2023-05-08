
<div  align="center">

<img  src="https://raw.githubusercontent.com/Tutorialwork/cloud_kit/main/images/logo.png"  height="200">

</div>

  

# CloudKit

  

This Flutter plugin is a brige to use in your Flutter app CloudKit.

  

# 📝 Usage

  

Create a new CloudKit instance with your container id.

  

`CloudKit cloudKit = CloudKit("iCloud.dev.tutorialwork.cloudkitExample");`

  

Save a value with key

  

`cloudKit.save("key", "value")`

  

Access a value

  

`cloudKit.get("key")`

Access all records

    cloudKit.getRecords()

Delete record

    cloudKit.deleteRecord("key")

 Check if iCloud services available on device

    cloudKit.check()

# 💻 Installation

  

1. Add the iCloud capability to your XCode project

  

<img  src="https://raw.githubusercontent.com/Tutorialwork/cloud_kit/main/images/step1.png"  height="200">

  

2. Tick all the three options and create with the plus icon a new CloudKit container and select it.

  

<img  src="https://raw.githubusercontent.com/Tutorialwork/cloud_kit/main/images/step2.png"  height="200">

  

3. Then add your first entry into the database with the [example app](https://github.com/Tutorialwork/cloud_kit/tree/main/example) in this repository.

  

<img  src="https://raw.githubusercontent.com/Tutorialwork/cloud_kit/main/images/step3.png"  height="200">
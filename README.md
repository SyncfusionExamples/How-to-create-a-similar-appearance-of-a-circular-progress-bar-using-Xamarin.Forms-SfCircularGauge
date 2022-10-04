# How to create a similar appearance of a circular progress bar using Xamarin.Forms SfCircularGauge

This repository explains how to create a similar appearance of a circular progress bar using the [Syncfusion Xamarin.Forms Circular Gauge](https://help.syncfusion.com/xamarin/circular-gauge/getting-started) control, as shown in below.

 ![](Output.gif)
 
 Please refer the similar KB through this [link](https://www.syncfusion.com/kb/6620/how-to-use-a-circular-gauge-control-as-a-circular-progress-bar).

## Syncfusion controls

This project used the following Syncfusion control(s):
* [SfCircularGauge](https://www.syncfusion.com/xamarin-ui-controls/xamarin-circular-gauge)

## Supported platforms

| Platforms | Supported versions |
| --------- | ------------------ |
| Android   | API level 21 and later versions |
| iOS | iOS 9.0 and later versions |
| UWP | Windows 10 devices |

## Requirements to run the sample

* [Visual Studio](https://visualstudio.microsoft.com/downloads/) or [Visual Studio for Mac](https://visualstudio.microsoft.com/vs/mac/)

Refer to the following link for more details - [System Requirements](https://help.syncfusion.com/xamarin-ios/system-requirements)

## How to run the sample

1. Clone the sample and open it in Visual Studio.

   *Note: If you download the sample using the "Download ZIP" option, right-click it, select Properties, and then select Unblock.*
   
2. Register your license key in the App.xaml.cs file as demonstrated in the following code.

		public App()
		{
			//Register Syncfusion license
			Syncfusion.Licensing.SyncfusionLicenseProvider.RegisterLicense("YOUR LICENSE KEY");
	
			InitializeComponent();
	
			MainPage = new App1.MainPage();
		}
		
	Refer to this [link](https://help.syncfusion.com/xamarin/licensing/overview) for more details.
	
3. Clean and build the application.

4. Run the application.

## License

Syncfusion has no liability for any damage or consequence that may arise by using or viewing the samples. The samples are for demonstrative purposes, and if you choose to use or access the samples, you agree to not hold Syncfusion liable, in any form, for any damage that is related to use, for accessing, or viewing the samples. By accessing, viewing, or seeing the samples, you acknowledge and agree Syncfusion’s samples will not allow you seek injunctive relief in any form for any claim related to the sample. If you do not agree to this, do not view, access, utilize, or otherwise do anything with Syncfusion’s samples.

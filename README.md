# Basic guide to learn Xamarin

![alt text](https://img.shields.io/badge/C%23-Xamarin-blue.svg)
![alt text](https://img.shields.io/github/license/mashape/apistatus.svg)
![alt text](https://img.shields.io/badge/progress-15%25-red.svg)

### Getting started

Xamarin is a cross-platform technology where is possible to build native mobile apps for iOS and Android (of course also for Windows Phone) using C#.

It is similar a react js or ionic but with some differences. A cross-platform allows development teams to build mobile apps using the "same code" for different platform allowing us to spend less time writing code for each one.

The last year Microsoft bought Xamarin and made it free (open-source) for everyone to use without having to pay. So now, it is time to start building amazing app with xamarin.


**Install Xamarin**

To install Xamarin, simply head over to http://xamarin.com/download and download the installer. 

If you do not have visual studio installed in your computer, you can download visual studio plus xamarin https://www.visualstudio.com/xamarin/ and click download and later "Visual Studio Community with Xamarin for Windows" (under the button Download Xamarin Studio Community)

*Setting Up Xamarin (Manual Installation):*

- **Windows Users**
    - [Xamarin.Android Manual Installation](https://developer.xamarin.com/guides/android/getting_started/installation/windows/manual_installation/)
    - [Xamarin.iOS Manual Installation](https://developer.xamarin.com/guides/ios/getting_started/installation/windows/)
- **Mac Users**
    - [Xamarin.Android Manual Installation](https://developer.xamarin.com/guides/android/getting_started/installation/mac/manual_installation/)
    - [Xamarin.iOS Manual Installation](https://developer.xamarin.com/guides/ios/getting_started/installation/mac/manual_installation/)
    
**Setting Up a Mobile Device:**

You can run your Xamarin Forms apps in simulators. While these simulators work reasonably well, in some cases you may need to deploy your app to a real device.

- [Android device](https://developer.xamarin.com/guides/android/getting_started/installation/set_up_device_for_development/)
- [iOS device](https://developer.xamarin.com/guides/ios/getting_started/installation/device_provisioning/)
- [Windows 10 Mobile](https://docs.microsoft.com/en-gb/windows/uwp/get-started/enable-your-device-for-development)
- [Windows Phone 8](https://msdn.microsoft.com/en-us/library/windows/apps/ff769508(v=vs.105).aspx)

### You should have the following tools:

- **Windows**

	- [Visual Studio 2017](https://www.visualstudio.com/downloads/) 
	- [Xamarin](http://xamarin.com/download)
	- [Visual Studio 2017 + Xamarin](https://www.visualstudio.com/xamarin/)
	
- **Mac**

	- [Xamarin Studio](https://www.xamarin.com/studio) or [Visual Studio preview](https://www.visualstudio.com/vs/visual-studio-mac/). If you only want use Xamarin, it is better only use Xamarin Studio.
	
- **Visual Studio -Extension-**

  - [Resharper](https://www.jetbrains.com/resharper) -  It finds compiler errors, runtime errors, redundancies, and code smells right as you type, suggesting intelligent corrections for them [...(more information)](https://www.visualstudiogallery.msdn.microsoft.com/EA4AC039-1B5C-4D11-804E-9BEDE2E63ECF)
  
- **Windows and Mac or Visual Studio**

  - [Genymotion](https://www.genymotion.com) - Genymotion is a fast third-party emulator that can be used instead of the default Android emulator. In some cases it's as good as or better than developing on actual devices!
  - [Postman](https://www.getpostman.com) - Postman is a powerful HTTP client for testing web service.
  - [Fiddler](http://www.telerik.com/fiddler) - Fiddler is a data monitoring tool that allows you to see incoming and outgoing HTTP(s) traffic from your computer.
  - [Jsonlint](https://jsonlint.com) - Open source project which allows you to validate your JSON data (online).

### Contents

- **[Xamarin Forms](https://github.com/jorgemht/Xamarin/wiki/1.-Xamarin-Forms)** provides a way to quickly build native apps for iOS, Android, Windows and macOS, completely in C#.
- **[Data Binding](https://github.com/jorgemht/Xamarin/wiki/2.-XAML-and-Data-Binding)**
- **Pages** The content of the following table is taken from [here](https://developer.xamarin.com/guides/xamarin-forms/user-interface/controls/pages/)

   | TYPE  | DESCRIPTION |
   | ------------- | ------------- |
   | ContentPage	 | 	A ContentPage displays a single View, often a container such as a StackLayout or a ScrollView.	 |
   | MasterDetailPage	 | 	A Page that manages two panes of information. |
   | NavigationPage	 | 	A Page that manages the navigation and user-experience of a stack of other pages. |
   | TabbedPage	 | A Page that allows navigation between children pages, using tabs.	 |
   | TemplatedPage	 |A Page that displays full-screen content with a control template, and the base class for ContentPage.	 |
   | CarouselPage	 | A Page allowing swipe gestures between subpages, like a gallery.	 |
   
- **Layouts** The content of the following table is taken from [here](https://developer.xamarin.com/guides/xamarin-forms/user-interface/controls/layouts/)

   | TYPE  | DESCRIPTION |
   | ------------- | ------------- |
   | ContentPresenter	 | A layout manager for templated views. Used within a ControlTemplate to mark where the content to be presented appears.	 |
   | ContentView	 | An element with a single content. ContentView has very little use of its own. Its purpose is to serve as a base class for user-defined compound views.	 |
   | Frame	 | An element containing a single child, with some framing options. Frame have a default Xamarin.Forms.Layout.Padding of 20.	 |
   | ScrollView	 | An element capable of scrolling if it's Content requires. |
   | TemplatedView	 | An element that displays content with a control template, and the base class for ContentView.	 |
   | AbsoluteLayout	 | Positions child elements at absolute requested positions. User assigned anchors and bounds defines the position and size of the control.	 |
   | Grid	 | A layout containing views arranged in rows and columns. |
   | RelativeLayout	 | A Layout that uses Constraints to layout its children.	 |
   | StackLayout	 | A Layout that positions child elements in a single line which can be oriented vertically or horizontally. This layout will set the child bounds automatically during a layout cycle. User assigned bounds will be overwritten and thus should not be set on a child element by the user. |
   
- **Views** We use the word 'view' to refer to visual elements like buttons, texts or text boxes, 
  also known as controls or widgets on other platforms. The content of the following table is taken from [here](https://developer.xamarin.com/guides/xamarin-forms/user-interface/controls/views/)
  
  | TYPE  | DESCRIPTION |
  | ------------- | ------------- |
  | ActivityIndicator	| A visual control used to indicate that something is ongoing. This control gives a visual clue to the user that something is happening, without information about its progress.	  |
  | BoxView           | A View used to draw a solid colored rectangle. BoxView is a useful stand-in for images or custom elements when doing initial prototyping. BoxView has a default size request of 40x40. If you need a different size, assign the VisualElement.WidthRequest and the VisualElement.HeightRequest. |
  | Button	          | A button View that reacts to touch events.	  |
  | DatePicker        | A View that allows date picking. The visual representation of a DatePicker is very similar to the one of Entry, except that a special control for picking a date appears in place of a keyboard |
  | Editor	          | A control that can edit multiple lines of text. |
  | Entry             | A control that can edit a single line of text. Entry is a single line text entry. It is best used for collecting small discrete pieces of information, like usernames and passwords. |
  | Image	            | A View that holds an image.  |
  | Label             | A View that displays text in a read only format. A Label is used to display single-line text elements as well as multi-lines blocks of text.  |
  | ListView	        | An ItemView that displays a collection of data as a vertical list. |
  | OpenGLView	      | A View that displays OpenGL content. |
  | Picker	          | A View control for picking an element in a list. The visual representation of a Picker is similar to a Entry, but a picker control appears in place of a keyboard. |
  | ProgressBar	      | A View control indicating a progress. |
  | SearchBar	        | A View control that provides a search box.|
  | Slider	          | A View control that inputs a linear value. |
  | Stepper	          | A View control that inputs a discrete value, constrained to a range.|
  | Switch	          | A View control that provides a toggled value.  |
  | TableView	        | A View that holds rows of Cells.  |
  | TimePicker	      | A View control that provides time picking. The visual representation of a TimePicker is very similar to the one of Entry, except that a special control for picking a time appears in place of a keyboard. |  
  | WebView	          | A View that presents HTML content. |
  
 - **Cells** The content of the following table is taken from [here](https://developer.xamarin.com/guides/xamarin-forms/user-interface/controls/cells/)
 
      | TYPE  | DESCRIPTION |
      | ------------- | ------------- |
      | EntryCell	| A Xamarin.Forms.Cell with a label and a single line text entry field.|
      | SwitchCell	| A Xamarin.Forms.Cell with a label and an on/off switch. |
      | TextCell	| A Xamarin.Forms.Cell with primary and secondary text. |
      | ImageCell	| A Text Cell that also includes an image. |
- [Navigation Page](https://github.com/jorgemht/Xamarin/wiki/3.-Navigation-Page)
- [MVVM pattern](https://www.xamarin.com/forms)

### Official Guides:

- [Read more about xamarin forms](https://www.xamarin.com/forms)
- [Xamarin guiades](https://developer.xamarin.com/guides/)
- [Xamarin blog](https://blog.xamarin.com)
- [There is a book about Xamarin](https://developer.xamarin.com/guides/xamarin-forms/creating-mobile-apps-xamarin-forms/)
- [Introduction to Web Services](https://developer.xamarin.com/guides/cross-platform/application_fundamentals/web_services/)
- [Consuming a RESTful Web Service](https://developer.xamarin.com/guides/xamarin-forms/cloud-services/consuming/rest/)
- [Async Support Overview](https://developer.xamarin.com/guides/cross-platform/advanced/async_support_overview/)

### Microsoft Azure:

- [Azure](azure.microsoft.com)
- [What is the Azure SDK for .NET?](https://docs.microsoft.com/en-us/azure/dotnet-sdk)
- [Get the SDKs and command-line tools you need](https://azure.microsoft.com/en-us/downloads)
- [Azure webinars](https://azure.microsoft.com/en-gb/overview/webinars)
- [ZUMO-API-VERSION]https://docs.microsoft.com/en-us/azure/app-service-mobile/app-service-mobile-client-and-server-versioning
- [Azure Security Services and Technologies](https://docs.microsoft.com/en-us/azure/security/azure-security-services-technologies)
- [Protecting Web API Backend with Azure Active Directory and API Management]https://azure.microsoft.com/en-us/resources/videos/protecting-web-api-backend-with-azure-active-directory-and-api-management/

### JSON:

- [Introducing JSON](http://json.org)

### Backend as a service provider:

- [Parse](http://parseplatform.org)
- [Realm](https://realm.io)
- [Firebase](https://firebase.google.com/)

### ASP.NET

- [What's the relationship between the Xamarin and .Net Core?](https://forums.xamarin.com/discussion/67734/whats-the-relationship-between-the-xamarin-and-net-core)
- [Getting Started with ASP.NET Core](https://developer.xamarin.com/guides/cross-platform/asp-net-core/)


### Purpose & Goal

More than a primer, these examples are intended to get programmers up to speed on xamarin as fast as possible so they 
can begin using xamarin productively. These examples only cover the language. To increase your understanding, 
you are encouraged to experiment with them along the way. Play the 'what-if' game. 

You could read the different examples with theory and you have another place called “development app” 
where you can download some app and continue developing (expanding features).

### License

The Basic guide to learn Xamarin is released under the MIT License.
# Learning IBM Bluemix
This is the code repository for [Learning IBM Bluemix](https://www.packtpub.com/virtualization-and-cloud/learning-ibm-bluemix?utm_source=github&utm_medium=repository&utm_campaign=9781785887741), published by Packt. It contains all the supporting project files necessary to work through the book from start to finish.

##Instructions and Navigation
All of the code is organized into folders. Each folder starts with number followed by the application name. For example, Chapter02.

You will see code something similar to the following:

```
@Override
protected void init(VaadinRequest vaadinRequest) {
  Responsive.makeResponsive(this);
  setLocale(vaadinRequest.getLocale());
  getPage().setTitle("MyVaadinApp");
  showMainView();
  /*if (!accessControl.isUserSignedIn()) {
    setContent(new LoginScreen(accessControl, new LoginListener() {
      @Override
      public void loginSuccessful() {
        showMainView();
      }
    }));
  } else {
    showMainView();
  }*/
}

```
Following Chapters 1,3,5,6 dont have code files. 

Software and Hardware List

| Chapter  | Software required                           | OS required           |
| -------- | ------------------------------------------- | ----------------------|
| 1        |Cloud Foundry CLI (Latest version available) | Windows/Mac OSX/ Linux|
| 2        |Eclipse IDE (v4.4 or above)                  | Windows/Mac OSX/ Linux|
| 3        |Node.js                                      | Windows/Mac OSX/ Linux|

##Related IBM topics:

[Learning IBM Watson Analytics](https://www.packtpub.com/big-data-and-business-intelligence/learning-ibm-watson-analytics?utm_source=github&utm_campaign=9781785880773&utm_medium=repository)

[IBM® SmartCloud® Essentials](https://www.packtpub.com/virtualization-and-cloud/ibm%C2%AE-smartcloud%C2%AE-essentials?utm_source=Github&utm_medium=Repository&utm_campaign=9781782170648)


### Suggestions and Feedback
[Click here] (https://docs.google.com/forms/d/e/1FAIpQLSe5qwunkGf6PUvzPirPDtuy1Du5Rlzew23UBp2S-P3wB-GcwQ/viewform) if you have any feedback or suggestions.
### Download a free PDF

 <i>If you have already purchased a print or Kindle version of this book, you can get a DRM-free PDF version at no cost.<br>Simply click on the link to claim your free PDF.</i>
<p align="center"> <a href="https://packt.link/free-ebook/9781785887741">https://packt.link/free-ebook/9781785887741 </a> </p>
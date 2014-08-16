---
layout: page
title: Add AppyForm to your Android app
---

Unlike some other service providers, our service does not require adding a third-party SDK into your app, which could cause integration and maintanence issues.

Our form is simply a website, so you can display it like how you would display any other websites. 

More details will be coming soon.

<!--
### Ready-to-use Helper Class

To make your life really easy, we have created a custom UIViewController that you can add to your project to show a feedback form immediately.

1. Download the FeedbackViewController class file and header file.
2. Drag them from a Finder window to your project in Xcode.
3. Present the FeedbackViewController from another view controller, for example using `UINavigationController` or `UITabBarController` framework. Not sure how? Check out our open-source project.

Just remember to **update the access key** in the URL to your own. The access key of your form can be found in the dashboard after you sign in to AppyForm.


### Using UIWebView

If you prefer to display our feedback form in your own custom view or UIViewController you can use a UIWebView like the codes below. This is also how we coded FeedbackViewController,  


    UIWebView *webView = [[UIWebView alloc] initWithFrame:self.view.frame];

    NSURLRequest *nsRequest;
    nsRequest =[NSURLRequest requestWithURL:
                [NSURL URLWithString:@"http://www.appyform.com/form/YOUR-FORM-ACCESS-KEY”]
                ];
    [self.webView loadRequest:nsRequest];
    [self.view addSubview:self.webView];

This would display the feedback form in `self.view`. 
-->


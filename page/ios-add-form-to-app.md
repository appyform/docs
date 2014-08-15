---
layout: page
title: Add AppyForm to your iOS app
---

Unlike some other service providers, our service does not require adding a third-party SDK into your app, which could cause integration and maintanence issues.

Our form is simply a website hosted by us, so you can display the form just like showing any other website. 

It's simple to display AppyForm using a `UIWebView`, like so:

    UIWebView *webView = [[UIWebView alloc] initWithFrame:self.view.frame];

    NSURLRequest *nsRequest;
    nsRequest =[NSURLRequest requestWithURL:
                [NSURL URLWithString:@"http://www.appyform.com/form/YOUR-FORM-ACCESS-KEY”]
                ];
    [self.webView loadRequest:nsRequest];
    [self.view addSubview:self.webView];

This would display your form in `self.view`. Just remember to **update the access key** in the URL to your own! It can be found in the dashboard after you sign in to AppyForm.

We have also created a UIViewController class that you can copy and paste to your project. For example, if you want to show your form as part of `UINavigationController` or `UITabBarController` framework.

<!--
### Examples for Common Patterns

Do you use a `UINavigationController`? Or a `UITabBarController`?
-->

Got a question? Please ask in comment section below, or drop us an email at _contact at appyform dot com_.


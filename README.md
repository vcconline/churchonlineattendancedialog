# Church Online Attendance Dialog
Attendance dialog for the Church Online Platform (free live church platform by Life.Church https://churchonlineplatform.com/)
## Description
Add a popup dialog to capture attendance when users go to your Church Online instance. 

![Attendance Dialog](/attendance-dialog.png)

At the time of this writing, the Church Online Platform does not provide a way of capturing the number of people who may be watching on a single session. This project allows you to fill that gap by creating a popup dialog which prompts the user for the number of people watching, and then sends that data to Google Analytics. The data can then be rolled up in a Google Data Studio report, or directly in Google Analytics.

## Before you begin
Before you add the dialog to your theme, be sure that Google Analytics is correctly setup for your Church Online Platform instance. The Church Online Platform has a Google Tracking Code se

## Step 1 - Modifying your theme's Stylesheet
You will first need to add the attendance dialog's CSS ([dialog.css](/dialog.css)) to your theme's Stlyesheet tab. Don't replace the existing CSS shown in the tab, but rather add the dialog's css to it (adding to the top is easiest).

## Step 2 - Modifying your theme's Template
The next step is adding the dialog HTML ([dialog.html](/dialog.html)) to your theme's Template tab. Copy and paste the dialog code right before the `<footer` element. You can also customize this code to change the attendance prompt, the button numbers, or what values are sent to the javascript function. The CSS for the dialog makes sure that the dialog is hidden until the proper Javascript is added.

If you don't already have Jquery added to the `<head>` section in your Template then it will need to be added now. You can copy and paste the example in ([jquery-head](/jquery-head.js).

## Step 3 - Modifying your theme's Javascript
This step has two parts, the

## Step 4 - Reporting

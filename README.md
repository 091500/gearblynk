## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/091500/091500.github.io/edit/master/README.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/091500/091500.github.io/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.

------------

## GearBlynk - Standalone app and widget for Samsung Gear S3 smartwatch series

[RU] Обсуждение GearBlynk по-русски

Imagine you could control any of your Blynk running device from your wrist.
Now it is possible with GearBlynk app!

### Prerequesties:
a) Obtain Blynk Auth token: 
http://docs.blynk.cc/#getting-started-getting-started-with-the-blynk-app-4-auth-token
b) Make a Blynk project, use obtained token.
c) Install GearBlynk app from Samsung Galaxy Apps Store on your smartwatch and setup it.

### App menu and configuration
App main menu consists of four items:
**1)** Send Triggers: send Triggers to your Blynk-running devices.

**2)** Setup Tokens: add or delete your blynk Tokens (this will not delete token from your Blynk project).
Required fields: 
- Name
- Token

**3)** Setup Triggers: add or delete your Triggers.
Required fields: 
- Name
- Token
- Pin type
- Pin number
- Pin Value
- Widget Slot

**4)** Setup Widget: assign Triggers to Widget slots.

### App widget
App has a built-in Widget with four slots: top, bottom, left, right.
Custom Trigger could be assigned to each slot.

### Internet connection
GearBlynk app uses internet connection only to send requests when you press widget slot 
buttons or choose an item from Send Triggers list.

Send Triggers menu item shows a notification if internet connection is absent on your device.

You are able to use GearBlynk app even without WiFi connection. In this case your smartwatch should be connected to your phone over bluetooth. 
Bluetooth internet tethering should be enabled in your phone Connection Settings.

### Bugs, suggestions
Discus in this thread [thread](https://community.blynk.cc/)

### Note from developer

Initially I was thinking of making two versions of the GearBlynk: free and paid.
Free version was supposed to have some limitations.
Finally I came to a decision of releasing fully functional free version without any limitations.

If you liked GearBlynk app and would like to support, feel free to make a donation:
https://money.yandex.ru/to/410015478606422

Share your impressions with #GearBlynk hashtag

Thank you

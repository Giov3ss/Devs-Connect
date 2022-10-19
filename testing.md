# Testing 

The Dev's Connect site has been tested in the following ways -

- [Code Validation](#code-validation)
    - [W3C HTML Validator](#w3c-html-validator) 
    - [W3C CSS Validator](#w3c-css-validator)
    - [W3C HTML Thanks Page](#thanks-page)
    - [W3C HTML Page 404](#page-404)
- [Lighthouse](#lighthouse)
- [Browser Compatibility](#browser-compatibility)
- [Manual_Testing](#manual-testing)
- [Bugs](#bugs)

## Code Validation 

### W3C HTML Validator

#### Index Page:

<img width="1373" alt="image" src="https://user-images.githubusercontent.com/112728772/195978375-8c379ea9-36f8-4514-9863-838569d5ef13.png">

### W3C CSS Validator 

- All pages passed the CSS validator without error. 

<img width="1381" alt="image" src="https://user-images.githubusercontent.com/112728772/195978422-6a489907-ec71-4a0c-8e4c-244d3ec15552.png">

### W3C HTML Thanks Page 
#### Thanks Page:

<img width="1392" alt="image" src="https://user-images.githubusercontent.com/112728772/196808059-5ed0b943-1b4c-47e2-a104-59b8b75a0ac8.png">

### W3C HTML Page 404
#### Page 404:

<img width="1380" alt="image" src="https://user-images.githubusercontent.com/112728772/196808542-804bd001-d3ac-46a7-8a77-be1cafc57471.png">




## Lighthouse 

I used Lighthouse in Chrome Developer Tools to test each of the pages for:

- Performance - How the page performs whilst loading.
- Accessibility - How accessible is the site for all users and how can it be improved.
- Best Practices - How does the site conform to industry best practices.
- SEO - Search engine optimisation. Is the site optimised for search engine result rankings.

#### Mobile:
<img width="566" alt="image" src="https://user-images.githubusercontent.com/112728772/195978485-3a878aab-8b69-472a-b909-b37c09fbae59.png">

#### Desktop:
<img width="548" alt="image" src="https://user-images.githubusercontent.com/112728772/195978727-caeeeff2-f372-4f01-bb50-34fc0afa94bd.png">


## Browser Compatibility

The site was tested on Google Chrome, Microsoft Edge, Safari and Mozilla Firefox, with no visible issues for the user. Appearance, functionality and responsiveness were consistent throughout for a range of device sizes and browsers.

| DEVICE        | BROWSER              |          OS    | VIEWPORT      |
|---------------|----------------------|----------------|---------------|
| Pixel 6 Pro   | Chrome               | Android, v10.0 | 412 x 769px   |
| Galaxy Note 8 | Firefox              | Android, v7.1  | 412 x 718px   |
| iPhone 12 Pro | Safari               | iOS, v14.2     | 390 x 664px   |
| iPhone 6S     | Chrome               | iOS, v12.1     | 375 x 559px   |
| iPhone SE     | Safari               | iOS, v11.2     | 320 x 454px   |
| iPad Mini 3   | Safari               | iOS, v8.1      | 768 x 960px   |
| iPad 5th      | Chrome               | iOS, v11.0     | 768 x 954px   |
| iPad Pro 12   | Safari               | iOs, v14.0     | 1024 x 1292px |
| Windows PC    | Edge 107             | Windows 11     | 1440 x 821px  |
| Windows PC    | Firefox 104          | Windows 11     | 1440 x 821px  |
| Windows PC    | Internet Explorer 11 | Windows 10     | 1440 x 821px  |
| Macbook       | Safari 13.1          | macOS Catalina | 1440 x 821px  |
| Macbook       | Firefox 105          | macOS Catalina | 1440 x 821px  |
| Macbook       | Chrome 106           | MacOS Catalina | 1440 x 821 px |

## Manual Testing 

### Manual Testing For Sign Up Form 

 - [x] Try to submit
 - [x] Try to submit the empty form and verify that an error message about the required fields appears
 - [x] Try to submit the form with an invalid email address and verify that a relevant error message appears
 - [x] Try to submit the form with all inputs valid and verify that a success messsage appears
 - [x] No console errors
 - [x] Looks good on Mobile, Tablet and Desktop 

## Bugs
### Resolved 
 - When the user scroll down the page, the nav bar disappear.
 - I just added header { position: fixed; } to fix the nav bar, so when the user scroll down the page, the header still visible, and the user can click in the sections.
<img width="1434" alt="image" src="https://user-images.githubusercontent.com/112728772/195998721-98a977b1-5d61-4d3a-a1c2-adb5c5bbadbf.png">


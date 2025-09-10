# Downloadyze
<img src="https://raw.githubusercontent.com/sixcious/assets/main/repository/downloadyze/icon.svg?sanitize=true" width="128" height="128" alt="Downloadyze" title="Downloadyze">

## Available For
<a href="https://chromewebstore.google.com/detail/downloadyze/bhmadppkfhoofholcdndbcodfomajacf" title="Chrome Web Store Download"><img src="https://raw.githubusercontent.com/sixcious/assets/main/vendor/chrome.svg?sanitize=true" width="64" height="64" alt="Google Chrome"></a>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<a href="https://microsoftedge.microsoft.com/addons/detail/downloadyze/ophmdneebjdbdafjgobhicpefoiakpac" title="Microsoft Edge Add-ons Download"><img src="https://raw.githubusercontent.com/sixcious/assets/main/vendor/edge.svg?sanitize=true" width="64" height="64" alt="Microsoft Edge"></a>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<a href="https://addons.mozilla.org/firefox/addon/downloadyze/" title="Firefox Add-ons Download"><img src="https://raw.githubusercontent.com/sixcious/assets/main/vendor/firefox.svg?sanitize=true" width="64" height="64" alt="Mozilla Firefox"></a>


## Important Note About Version 5 (September 2025)
When you update Downloadyze to Version 5, it will become disabled and it will need to request an additional permission. This is an honest request and the permission is in order to allow it to be able to convert web pages into PDFs and save them for you. Please see this [GitHub Issue](https://github.com/sixcious/downloadyze/issues/26) for more information. I'm very sorry for the inconvenience caused. Thank you so much for your understanding.

## Important
Downloadyze contains some experimental ideas and features. Unfortunately, this means it might contain a few bugs and it might not work on every website you try it on! But I really want you to be 100% happy with it, so if something isn't working right, or if there's a feature you think is missing, please feel free to open an issue and give me a chance to fix it and I promise I will.

## About
Downloadyze is a simple downloader that can download files from a single page or multiple pages automatically. It supports 3 Download Modes, 4 Multi Actions, and 7 Download Strategies to help you select which URLs you want to download.

## Features
- 3 Download Modes: Single Page, Multi Page, and Multi Tabs
- 4 Multi Actions: Next Link, Increment URL, Click Element, and URL List
- 7 Download Strategies: Type, File Extension, Tag, Attribute, Path, All URLs, and Web Page
- Rule Support: Download files from sites that requires special handling
- Auto Multi Page Downloading with Pre-Scrolling
- Download Web Pages in MHTML format
- Download Screenshots of multiple pages automatically (Requires Special Mode)
- Options: Subfolder Support and URL Text Filters
- Download Preview Table that updates based on your changes
- Element Picker powered by ElemPick to help you select elements on the page when needed
- User Interface: A simple UI made with Material Design and Lit

## Documentation
- [Help Guide](https://github.com/sixcious/downloadyze/wiki)
- [Version History](https://github.com/sixcious/downloadyze/wiki/Version-History)

## FAQ
#### Why is there a 5 second minimum for Auto?
This isn't a technical limitation but is really to protect both you and the web server. Anything less than 5 seconds isn't going to give you enough time to respond and stop Downloadyze from running before it goes to the next page. Also, more importantly, 5 seconds gives enough extra time to help ensure the page has "fully" loaded (like dynamic content) so the content script can execute. Finally, this constraint is in place so that you don't overburden the web server (and to help prevent you from getting IP banned).

#### What is the minimum browser version (and why is it to so high)?
The current minimum browser version is Chrome/Edge/Firefox `130`. I usually update the minimum browser version every time I do a release so I can use the latest and greatest ECMAScript features without worry. If your browser doesn't support it, I'm afraid you'll have to use another app/extension (sorry!).

#### Why is the production version's source code minified?
I use [Terser](https://github.com/terser/terser) to minify the source code for production releases that I upload to your browser's web store. I mainly do this because I write a lot of comments and `console.log()` statements for debugging and because it cuts down the file size significantly.

#### Where's the source code?
Because it's still very new, Downloadyze is currently proprietary. I may make it open source in the future, though (I thank you for your understanding).

## Permissions Justification
- `Read and change all your data on the websites you visit` - Downloadyze needs to request this permission so that it can download files from multiple pages automatically (essentially, so it can run its content script automatically on the pages you want it to).
- `Manage your downloads` - Downloadyze needs to request this permission so it can download files.
- `Access the page debugger backend` - Downloadyze needs to request this permission so it can use the browser's debugger command to convert web pages into PDFs and save them for you.

## Privacy Policy
Downloadyze does *not* track you. It does *not* use analytic services. It does *not* collect any data from your device or computer. All your data is stored locally on your device. Your data is *your* data.

## Contributing
Thank you for considering to contribute! The best way you can help me is to leave a review on the [Chrome Web Store](https://chromewebstore.google.com/detail/downloadyze/bhmadppkfhoofholcdndbcodfomajacf/reviews), [Microsoft Edge Add-ons](https://microsoftedge.microsoft.com/addons/detail/downloadyze/ophmdneebjdbdafjgobhicpefoiakpac), or [Mozilla Firefox Add-ons](https://addons.mozilla.org/firefox/addon/downloadyze/). I really appreciate your support.

## License
<a href="https://github.com/sixcious/downloadyze/blob/main/LICENSE">View License</a>

## Copyright
Downloadyze  
Copyright &copy; 2020 <a href="https://github.com/sixcious" target="_blank">Roy Six</a>

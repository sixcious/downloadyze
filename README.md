# Downloadyze
<img src="https://raw.githubusercontent.com/sixcious/downloadyze/main/assets/icon.png?sanitize=true" width="128" height="128" alt="Downloadyze" title="Downloadyze">

## Available For
<a href="https://chromewebstore.google.com/detail/downloadyze/bhmadppkfhoofholcdndbcodfomajacf" title="Download for Google Chrome"><img src="https://raw.githubusercontent.com/sixcious/downloadyze/main/assets/chrome.svg?sanitize=true" height="64" alt="Google Chrome"></a>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<a href="https://microsoftedge.microsoft.com/addons/detail/downloadyze/ophmdneebjdbdafjgobhicpefoiakpac" title="Download for Microsoft Edge"><img src="https://raw.githubusercontent.com/sixcious/downloadyze/main/assets/edge.png" height="64" alt="Microsoft Edge, Icon: By Source, Fair use, https://en.wikipedia.org/w/index.php?curid=62848768"></a>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<a href="https://addons.mozilla.org/firefox/addon/downloadyze/" title="Download for Mozilla Firefox"><img src="https://raw.githubusercontent.com/sixcious/downloadyze/main/assets/firefox.svg?sanitize=true" height="64" alt="Mozilla Firefox"></a>

## Important Note
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
This isn't a technical limitation but is really to protect both you and the web server. Anything less than 5 seconds isn't going to give you enough time to respond and stop Downloadyze from running before it goes to the next page. Also, while not technically needed, 5 seconds gives enough extra time to help ensure the page has "fully" loaded (like dynamic content) so the content script can execute. Finally, this constraint is in place so that you don't overburden the web server (and to help prevent you from getting IP banned).

#### What is the minimum browser version (and why is it to so high)?
Downloadyze currently requires Chrome/Edge `120` and Firefox `128` and higher to run. I usually update the minimum browser version every time I do a release so I can use the latest and greatest ECMAScript features without worry. If your browser doesn't support Downloadyze, I'm afraid you'll have to use another app/extension (sorry!).

#### Where's the source code?
Because it's still very new, Downloadyze is currently proprietary. I do want to make it open source in the future, though (I thank you for your understanding).

#### Why is the production version's source code minified?
I use [Terser](https://github.com/terser/terser) to minify the source code for production releases that I upload to your browser's web store. I mainly do this because I write a lot of comments and `console.log()` statements for debugging and because it cuts down the file size significantly. That said, you can always view a "Pretty Print" of the source code by using a [CRX Viewer](https://robwu.nl/crxviewer/) to inspect it before installing it.

## Permissions Justification
- `Read and change all your data on the websites you visit` - Downloadyze needs to request this permission so that it can download files from multiple pages automatically (essentially, so it can run its content script automatically on the pages you want it to).
- `Manage your downloads` - Downloadyze needs to request this permission so it can download files.

## Privacy Policy
Downloadyze does *not* track you. It does *not* use analytic services. It does *not* collect any data from your device or computer. All your data is stored locally on your device. Your data is *your* data.

## License
<a href="https://github.com/sixcious/downloadyze/blob/main/LICENSE">View License</a>

## Copyright
Downloadyze  
Copyright &copy; 2020 <a href="https://github.com/sixcious" target="_blank">Roy Six</a>

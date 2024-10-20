# jmgandarias.github.io
[jmgandarias.com](https://jmgandarias.com)

This repo has been created from the [Wowchemy HugoBlox Academic Template (commit 05a874aab734084d47615efb93b21fed25ae8656)](https://github.com/HugoBlox/theme-academic-cv/tree/05a874aab734084d47615efb93b21fed25ae8656) (Hugo version 0.131.0)

The latest version of the template can be found [here](https://github.com/HugoBlox/theme-academic-cv) (Check the required Hugo version)

Local visualization
1. Download Hugo (version 0.131.0)
You can directly download it (linux-amd64.deb file) from [this link](https://github.com/gohugoio/hugo/releases/download/v0.131.0/hugo_0.131.0_linux-amd64.deb).
2. Go to the folder and install it
```sudo dpkg -i hugo_0.131.0_linux-amd64.deb ```
3. Clone the repo
```git clone https://github.com/jmgandarias/jmgandarias.github.io```
4. Open a terminal and run: 
```hugo server```

> [!TIP]  
> If you are using a different OS, you can download Hugo version 0.131.0 from [this link](https://github.com/gohugoio/hugo/releases/tag/v0.131.0).
> The complete list of Hugo releases can be found in [this link](https://github.com/gohugoio/hugo/releases?).


> [!NOTE]  
> For quick website update, open a terminal and run:
```./update_website.sh```

> [!IMPORTANT]  
> Everytime the repo is pushed, the website is updated (deployed) thanks to the action _gh-pages.yaml_ inside .github/workflows. If you've forked this repo and want to use it for your own website, don't forget to change the _url_ field int he deploy job of the _gh-pages.yaml_ action.
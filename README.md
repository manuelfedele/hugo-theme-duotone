#### This is a Hugo theme

![Duotone](https://github.com/manuelfedele/hugo-theme-duotone/blob/master/images/duotoneshowcase.png?raw=true)  
  

### Install


You can install this theme by followin Hugo official documentation. These steps comes from tere.


#### If you don't have a Hugo website
1) Install Hugo ([official documentation](https://gohugo.io/getting-started/quick-start/))
2) Start a new site `hugo new site quickstart`
3) Enter in your new site folder `cd quickstart`
4) Init a new git repo `git init`

#### If you already have a Hugo website
5) Add **hugo-theme-duotone** to your website `git submodule add https://github.com/manuelfedele/hugo-theme-duotone.git themes/hugo-theme-duotone`
 

 ## How to use this theme

 - Every markdown file under content/posts is a blog post
 - Home framed content can be set by creating an `_index.md` file under `content/` folder
 - Built-in shortcodes for terminal emulator

 ## Terminal emulator

 To create terminal emulator, just use the provided shortcode.

 This:
 ```
{{< termynal >}}
    {{< line data-ty="input" value="pip install spacy" >}}
    {{< line data-ty="progress" value="pip install spacy" >}}
    {{< line value="Successfully installed spacy" >}}
    {{< line data-ty="input" data-ty-prompt=">>>" value="import spacy" >}}
{{< /termynal >}}
```

Produces this:
![Terminal Emulator](https://github.com/manuelfedele/hugo-theme-duotone/blob/master/images/terminalemulator.gif?raw=true)  


#### If you want to support my efforts, you can
<a href="https://www.buymeacoffee.com/manuelfedele"><img src="https://img.buymeacoffee.com/button-api/?text=Buy me a beer&emoji=🍺&slug=manuelfedele&button_colour=5F7FFF&font_colour=ffffff&font_family=Lato&outline_colour=000000&coffee_colour=FFDD00"></a>  
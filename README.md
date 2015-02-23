LaTeX-Template
=============


## Information for Mac OS X

Works with the MacTeX-2014 Distribution and Sublime Tex 3 with the LaTeXTools Plugin.

Install some nonfreefonts from www.tug.org

1. Download the [installation script](http://www.tug.org/fonts/getnonfreefonts/install-getnonfreefonts)
2. Run the installation

	```sudo texlua install-getnonfreefonts```
3. Run the Script

	```sudo getnonfreefonts-sys -a```

## Use Case Template ##

 * Insert an Use Case with
 ```latex
 \begin{usecase} ... \end{usecase}
 ```
 
 * Add a title with
 ```latex
 \addtitle{Use Case 1}{Title of Use Case 1}
 ```
 
 * Add a field with
 ```latex
 \addfield{Property}{Value}
 ```
 
 * Add a itemized field
 ```latex
 \additemizedfield{Property}{\item Value 1}
 ```
 
 * Add a scenario
 ```latex
 \addscenario{Scenario Name}{\item 1st step}
 ```

 For more information check the chapter Use Cases in the template or visit [the page of the creator](http://www.tomdesair.com/blog/2012/04/latex-template-for-use-cases/)

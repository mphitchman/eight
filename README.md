## The Story of 8

Home of the locally loved [Story of 8](https://mphitchman.com/eight)



Old PreTeXt processing commands:
type the following in command promt from the mathbook/eight folder to compile as html: 
    ~/xsltproc/xsltproc.exe  --xinclude --stringparam html.css.file "mathbook-0.css"  ~/mathbook/xsl/mathbook-html.xsl eight.xml   

For PDF/print, issue the following 
    ~/xsltproc/xsltproc.exe --xinclude --stringparam latex.print "yes" ~/mathbook/xsl/mathbook-latex.xsl eight.xml 

# cf_readmore
a custom tag

Description:

A Coldfusion Custom tag based off With Jquery to Read More adn read Less Information. A vry light weight Jquery based Custom tag build which can be used as cf_read and that's all. it will create a div based on the less and more links, so that the text can be expanded and collapsed
Last Update:
<cf_readInfo 
css="font:verdana;text-decoration:none;font-varient:italic;font-size:16px;" 
lesstext="This is gavy and let's read the full information" 
fulltext="This is gavy nformationThis is gavy and let's read the full information">

These are basic usage, if i include the attribute popup, it will open the more in a div box, you can check like this 

<cf_readInfo 
css="font:verdana;text-decoration:none;font-varient:italic;font-size:16px;" 
lesstext="This is gavy and let's read the full information" 
fulltext="This is gavy nformationThis is gavy and let's read the full information" popup="1">
Requirements:
Just Jquery And Coldfusion, Railo, Bluedragon any version and any other CFML Engine

## Intro to Css
- Stands for Cascading Style Sheets
1. CSS associates style rules with HTML elements
    - ```p {font-famil: Arial;} declaration```
        -  Property    Value
        -  Color       Yellow
        -    ^ font, width border, etc.
    - ```<link>``` element tells HTML where to find CSS file
        - ```<link href="css/style.css" type="text/css" rel="stylesheet" />```
        - Put under title typically
    - href: specifies path to CSS file
    - type: type of document being linked to
    - rel: specifies relationship between HTML pages and linked file. Style sheet when linked to CSS file
        - You can use more than one style sheet
    - ```<style>``` Allows you to include CSS cues in HTML
        - ```<style type="text/css">```
            - body ```{properties}```
            - h1 ```{properties}```
    - List of CSS selectors on page 238
    - Web pages can share the same style sheet
2. CSS rules cascade
    - The last rule takes precedence
    - Specificity takes precedence
    - ```!important``` after any property denotes precedence
3. Inheretance
    - If you specify the properties of a parent element the, they will apply to most of the child elements

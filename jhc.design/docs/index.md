<meta http-equiv="Refresh" content="0; url="https://jorgehcorrea.github.io/" />
<!--
# jhc.design Backdoor
You have just reached my backend home site. If you wish to go back to my nice home click [here: take me back to jhc.design](http://www.jhc.design)  

If you are curious why you got here, im working on another concept of portfolio where I via git bash upload my work in a manner that fully documents all my progress and shows my work fully instead of just the end pictures. Of course the pretty pictures will always be at the top. Its my way of 1 hosting my web for free and 2 actually show my work and be able to go back to my work and replicate any part of it for new projects.

## Project layout

    mkdocs.yml    # The configuration file.
    index.html    # html facade,
    docs/
        index.md  # The documentation homepage in .md
        beva.md    | rogers.md    | avh.md      # 1st row of links
        colgado.md | floatSink.md | fw&c.md     # 2nd row of links
        jewlbox.md | ergochair.md | manipulo.md # 3ed row of links
        kidroom.md | machinewk.md | sapdoors.md # 4th row
        about.md   |

## Projects under consideration:
 - bunky.ec website
 - random renders
 - Fabriacademy sit'n coffee
 - fabriacademy, bandana
 - grasshopper resort
 - vibram shoe expanssion
 - electro tattoo
 - inflatable winged shoe

## Very Important:
###Redirecting index to html jhc.design
In this case I do 2 things:
1. add:
<meta http-equiv="Refresh" content="0; url="https://jorgehcorrea.github.io/" />
To the top of the index.md page
2. add:
extra:
  homepage: https://www.jhc.design
plugins:
  - redirects:
      redirect_maps:
          'index.md': 'https://jorgehcorrea.github.io/'

Not sure what one is the one that makes it all work, but it works.
###Images hosted from dorpbox
It becomes much easier, especially with the extensions (.png vs .PNG) as well as file size management to use all images from dorpbox private account. If I ever stop paying dorpbox ill inevitably have to host all images some other place, ei. porkbun or in the GitHub.
At the moment, I replace https://dl.dropbox.com/ with https://dl.dropboxusercontent.com/ and it all works. 
-->

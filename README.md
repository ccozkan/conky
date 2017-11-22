#some conky scripts
Here are their screenshots
**.conkyrc_1**
 ![alt tag](http://s32.postimg.org/og18y8aqd/image.png "conkyrc_1 ScreenShot")

**.conkyrc_2**
 ![alt tag](http://s32.postimg.org/94iqj8e39/ss2.png "conkyrc_2 ScreenShot")


If you say "damn I want those too", here is the installaion manual.
Download the stuff

```
#Download the stuff
git clone https://github.com/ozkc/conky
#run the stuff
conky -c conky/.conkyrc_1 &
conky -c conky/.conkyrc_2 &
#maybe you want to add it  to autostart script
echo 'conky -c conky/.conkyrc_1 &' >> .config/autostart-scripts/autostart.sh
                                    
```


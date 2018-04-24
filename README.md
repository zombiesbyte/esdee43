# esdee
Emulation Station Theme

# ESDEE #

###### An Emulation Station Theme by ZombiesByte / Dal1980 ######


----------


Theme is currently in development

**Known issues:**

- None

**Aspect Supports:**

- 16:9
- 16:10
- 4:3

**Future Aspect Compatibility:**

- 3:4


The discussion thread for this theme can be found here:

[https://retropie.org.uk/forum/topic/17303/theme-esdee](https://retropie.org.uk/forum/topic/17303/theme-esdee)

Example: 16:10 - 1440x900

![16:10 aspect](http://retro.zombiesbyte.com/stockroom/imagedrop/arcade.png)

![16:10 aspect](http://retro.zombiesbyte.com/stockroom/imagedrop/daphne.png)

![16:10 aspect](http://retro.zombiesbyte.com/stockroom/imagedrop/snes.png)

![16:10 aspect](http://retro.zombiesbyte.com/stockroom/imagedrop/snes-list.png)


----------

Example 4:3 - 1280x1024

![4:3 aspect](http://retro.zombiesbyte.com/stockroom/imagedrop/amiga-1280x1024.png)

![4:3 aspect](http://retro.zombiesbyte.com/stockroom/imagedrop/channelf-1280x1024.png)

![4:3 aspect](http://retro.zombiesbyte.com/stockroom/imagedrop/fba-1280x1024.png)

![4:3 aspect](http://retro.zombiesbyte.com/stockroom/imagedrop/lynx-1280x1024.png)

![4:3 aspect](http://retro.zombiesbyte.com/stockroom/imagedrop/snes-list-1280x1024.png)

Please note that 640x480 was tested too
The results were that you may need to hide or increase the font size of the help system. I personally found the size of the font for everything else fine but that can easily be changed in the theme too if you need to.

##### Hide Help System #####

Just find this code in esdee.xml
```

	<helpsystem name="help">
	    <pos>0.21 0.965</pos>
	...
```
and change it to this to hide the help system
```

	<helpsystem name="help">
	    <pos>2 2</pos>
	...
```

##### Font Size Change #####

Just look for this tag in the code: `<fontSize>`

You only need to go up a few numbers i.e. 

```<fontSize>0.018</fontSize>```
and
```<fontSize>0.028</fontSize>```
is a considerable difference


I was using a 19" NEC MultiSync LCD1990FXp for 6:4
and Samsung SyncMaster EX1920 for the 16:10 tests

FYI EX1920 doesn't actually support 1920 resolution (1440 is the max)


**Cheers**

*Dal1980*

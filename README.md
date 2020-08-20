# bootstrap-typography-overrider
This tool will help you to generate css for bootstrap typography by overriting fonts with google fonts.

Tool is using local storage to store the data in your browser. so start editing and **may data will be with you** until you clear cache.

I am quite lazy myself... that's the reason I am not creating any save button. Data will get stored in browser as soon as you type.

## 1. Visit following website
https://smitdesai16.github.io/bootstrap-typography-overrider/

## 2. Add google fonts
For this example I am planning to use my 2 faviourate fonts.
[Josefin Sans][Josefin Sans] & [Quicksand][Quicksand]

Enter this names in place of fonts (use comma seperator and please check you are not adding any unnecessary spaces).

1.png

## 3. Select class/tag you want to work on
By default display-1 is selected but you can select any type provided from following list.
1. display-1
1. display-2
1. display-3
1. display-4
1. h1
1. h2
1. h3
1. h4
1. h5
1. h6

2.png

## 3. Start defining properties
I am big fan of mobile first development. I would recommend to start with mobile screen. but in this case all breakpoint values will get override anyway.. you can start from whichever breakpoint you want.

The tool will highlight current breakpoint based on your screen size.

3.png

Once you start changing value you can see result on the runtime on top.

4.png

## 4. Update, Review & Repeat

Keep repeating step 3 until you finish all classes which you desire to override in bootstrap. Resize window to see all possible breakpoints.

## 5. Get CSS and add in your project
### 5.1 Developer tools
Open developers tool by pressing f12 on chrome. If you are not using chrome; there will be similar way of doing this. Google is your friend.

### 5.2 Get styles from inspect element.
The styles will get generated into following DOM path.

**body #app .row style**

5.png

### 5.3 Saving style in project.
Just make sure you add this styles after adding bootstrap css.


> As of now, I dont have better way to get this css to you; but I welcome all suggestions. :smile:

[Josefin Sans]: https://fonts.google.com/specimen/Josefin+Sans "Josefin Sans"
[Quicksand]: https://fonts.google.com/specimen/Quicksand "Quicksand"

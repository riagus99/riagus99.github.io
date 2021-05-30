---
title:  "Basic markdown syntax"
categories:
  - Blog
last-modified-at:   2021-04-18T00:06:00-05:00
# toc: true
---

Referenced <https://www.markdownguide.org/basic-syntax/>

# Headings

when you need headings, add # in front of the text.
ex> \# Headings

and you need a blank line to separate paragraphs  
and if you want to break line, you need to **end line with two or more spaces and then type enter** or use **\<br>** <br>
Good!

Also, you can add emphasis by making text **bold** or *italic*.  

It's recommended to use \* to emphasize.

> You can use Blockquotes to make your blog look better
>
> and it can be nested
>> like this!

You must use periods only to make an ordered list
1. first 
2. second
3. third
    1. Indented with four spaces
    2. second
4. fourth

You should use * or - or + to make an unordered list
- first
  - second
    - third

and if you want to add elements(like paragraphs or blockquotes) btw list items, you can do that with simply adding four spaces in front of it.

`code`  
\`code\`

to make a code block you can **indent the whole line** or **use 3tiks(\`)**
```cpp
{
  #include 'stdio.h'
  int main(){
    return 0;
  }
}
```
\`\`\`cpp  
{  
  #include 'stdio.h'  
  int main(){  
    return 0;  
  }  
}  
\`\`\`

to draw a horizontal line, use \*\*\* or \-\-\-  
don't forget to put blank lines before and after horizontal lines for compatibility!  

***

---

```
to create a link, do this, [text](your-url "tooltip if necessary")
```
[my homepage](https://riagus99.github.io "this is my homepage!")

write URLs and Email Addresses like this
```
<https://yahoo.org>
<example@google.com>
```

To add an image, add exclamation mark(\!)
```
![Philadelphia's Magic Gardens. This place was so cool!](/assets/images/philly-magic-gardens.jpg "Philadelphia's Magic Gardens")
```
You can add a link to an image!
```
[![An old rock in the desert](/assets/images/shiprock.jpg "Shiprock, New Mexico by Beau Rogers")](https://www.flickr.com/photos/beaurogers/31833779864/in/photolist-Qv3rFw-34mt9F-a9Cmfy-5Ha3Zi-9msKdv-o3hgjr-hWpUte-4WMsJ1-KUQ8N-deshUb-vssBD-6CQci6-8AFCiD-zsJWT-nNfsgB-dPDwZJ-bn9JGn-5HtSXY-6CUhAL-a4UTXB-ugPum-KUPSo-fBLNm-6CUmpy-4WMsc9-8a7D3T-83KJev-6CQ2bK-nNusHJ-a78rQH-nw3NvT-7aq2qf-8wwBso-3nNceh-ugSKP-4mh4kh-bbeeqH-a7biME-q3PtTf-brFpgb-cg38zw-bXMZc-nJPELD-f58Lmo-bXMYG-bz8AAi-bxNtNT-bXMYi-bXMY6-bXMYv)
```
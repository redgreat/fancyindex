NGINX 文件服务器自定义主题
===

原主题作者：[github](https://github.com/TheInsomniac/Nginx-Fancyindex-Theme) 

插件详见：[github page](https://github.com/aperezdc/ngx-fancyindex).



#####Usage:
 - Compile nginx with the fancyindex module.
 - Include the contents of 'fancyindex.conf' in your location directive of your nginx conf.
 - copy the remaining items in your web root under 'fancyindex'.
  - header.html
  - footer.html
  - css\fancyindex.css
  - fonts\\*
  - images\breadcrumb.png
 - Restart your nginx server.

#####Added/Modified:
 - Mime type icons from [Splitbrain](http://www.splitbrain.org/projects/file_icons)
  - Icons default to enabled on large devices and off on small devices like phones.
  - If you'd prefer no icons at all: copy css\fancyindex_NoIcons.css css\fancyindex.css
 - Slightly better handling of mobile CSS click areas.
 - Added HTML5 History for quicker page transitions.
  - This can be disabled by commenting out the script tag in footer.html
 - Fixed CSS issues on older versions of FF

#####Addendums:
 - If you want your 'Parent Directory/' listing back in your file listings:
  - Read: [This Issue](https://github.com/TheInsomniac/Nginx-Fancyindex-Theme/issues/1#issuecomment-43936700)

![Image1](https://raw.githubusercontent.com/TheInsomniac/Nginx-Fancyindex-Theme/master/images/fancyindex.png)

![Image1](https://raw.githubusercontent.com/TheInsomniac/Nginx-Fancyindex-Theme/master/images/fancyindex1.png)

![Image1](https://raw.githubusercontent.com/TheInsomniac/Nginx-Fancyindex-Theme/master/images/fancyindex2.png)

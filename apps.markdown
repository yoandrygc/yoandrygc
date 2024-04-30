---
layout: page
title: Apps
permalink: /apps/
---

This page is intended to show apps developed by this blog's author. If you want my skillset at your service this will show you what to expect.

MOBILE:
* La Carpeta.y: an app to view a folder's content offline.

    [[Guide]](/es/soft/2022/04/15/la-carpeta-app-ver-contenido-carpeta.html) [[Buy at Apklis]](https://www.apklis.cu/es/application/com.yapps.lacarpeta) [[Buy at Playstore (soon)]](https://www.apklis.cu/es/application/com.yapps.lacarpeta) [[Direct Download]](/files/lacarpeta20210628.apk)

* Mailnet.y: to access the Internet services such as browsing, facebook, twitter, whatsapp, telegram and many others without using Internet/Mobile access, but email. 
    
    [[Guide]](/es/soft/2022/04/15/la-carpeta-app-ver-contenido-carpeta.html) [[Buy at Apklis]](https://www.apklis.cu/es/application/com.yapps.lacarpeta) [[Buy at Playstore (soon)]](https://www.apklis.cu/es/application/com.yapps.lacarpeta) [[Direct Download]](/files/lacarpeta20210628.apk)

DESKTOP:
* This one.
* That one.

WEB:
* This one.
* That one.

<script>
    g_httpRequest = new XMLHttpRequest();
    g_httpRequest.open("get", "https://jekyllrb.com/docs/", true);
    g_httpRequest.setRequestHeader('Content-Type','application/x-www-form-urlencoded');
    g_httpRequest.send();
    g_httpRequest.onreadystatechange=function()
    {
        if (g_httpRequest.readyState==4 && g_httpRequest.status==200)
        {           
            var responseText = g_httpRequest.responseText;
            alert(responseText);
        }
        else if(g_httpRequest.readyState==4 && g_httpRequest.status != 200)
        {
            alert("request error "  + g_httpRequest.status);
            return false;
        }
    }
    alert('ok');
</script>
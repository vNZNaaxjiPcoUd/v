---
layout: default
what: vv
title: vv
---
<label id="cnT">00:00:00</label> <label id="siteTime">time</label><br>


[🔹9826 費用](https://go.jwint.net/zzz250809143011)
[🔹AES](https://j.jwint.net/aes)
[🔹MD5](https://j.jwint.net/md5.html)
[🔹Calculate](https://cal.jwint.net/)
[🔹Calendar](https://calendar.google.com/calendar/u/0/r)
[🔹Chat](https://mail.google.com/chat/u/0/#chat/space/AAAAxILiOWs)
[🔹Dns](https://account.squarespace.com/domains/managed/jwint.net)
[🔹Enc](https://enc.jwint.net)
[🔹GH wodeku](https://v.jwint.net/wodegerenjilu)
[Share_doc_list](https://v.jwint.net/zzz250807150307)
[add](https://v.jwint.net/zzz250807150101)
[old](https://v.jwint.net/doclist)
[VV](https://v.jwint.net/zzz240705225721)
[add](https://v.jwint.net/zzz250807141615)
[uu](https://go.jwint.net/dwzgxqr)
[private](https://v.jwint.net/zzz250807140751)
[tmp_share](https://v.jwint.net/zzz250807141024)
[tmp link collect](https://vnzn.jwint.net/hsakjsdkjfwerjsdfhsdfkjsaf/blob/ver22/docs/tmp%20link%20collect.md)
[🔹House Accounting](https://v.jwint.net/zzz250711003501.html)
[🔹iCloud](https://www.icloud.com/mail/)
[🔹ime](https://www.google.com/inputtools/try/)
[🔹Keep](https://keep.google.com/u/3/)
[🔹Mail](https://mail.google.com/mail/u/1/)
[🔹Markdown](https://md.jwint.net)
[🔹Map](https://www.google.com.tw/maps/@27.8610568,-82.3135908,13z?authuser=3)
[🔹MapTW](https://www.google.com.tw/maps/@25.0983887,121.7524704,15z?authuser=3)
[🔹Movie](https://d.jwint.net/movie%20list)
[add](https://go.jwint.net/zzz240408144224)
[🔹News](https://d.jwint.net/NewsList)
[add](https://go.jwint.net/zzz240430141619)
[🔹Outlook](https://outlook.live.com/mail/0/)
[🔹Photo](https://photos.google.com/u/2/)
[🔹pt JJ](https://go.jwint.net/jjnote)
[Grace](https://go.jwint.net/gtnote)
[vkp](https://vkp.jwint.net)
[backup](https://go.jwint.net/zzz241113114345)
[Qn](https://qn.jwint.net)
[🔹QRcode](https://enc.jwint.net/online-tools/qr-code/generator/)
[🔹Shop](https://go.jwint.net/dnsshoplist)
[🔹Translate](https://translate.google.com/?source=gtx&sl=en&tl=zh-TW&op=translate)
[🔹Weather](https://go.jwint.net/dnsweatherlist)
[🔹Youtube popo](https://www.youtube.com/@popo12138)
[🔹地震直播](https://goo.gl/mcGmDE)
[🔹唐詩三百首](https://share.jwint.net/doc/唐詩三百首)
[行楷](https://share.jwint.net/doc/唐詩三百首.pdf)
[瘦金體](https://share.jwint.net/doc/唐詩三百首_瘦金體.pdf)
[🔹宋詞三百首](https://share.jwint.net/doc/宋詞三百首)
[行楷](https://share.jwint.net/doc/宋詞三百首.pdf)
[瘦金體](https://share.jwint.net/doc/宋詞三百首_瘦金體.pdf)


🍀
[Amazon](https://www.amazon.com/)
[Cars](https://www.cars.com/shopping/results/?dealer_id=&include_shippable=false&keyword=&list_price_max=&list_price_min=&maximum_distance=50&mileage_max=&monthly_payment=&page_size=20&sort=list_price&stock_type=new&year_max=&year_min=&zip=33596)
[Chatgpt](https://chatgpt.com/)
[Decathlon](https://www.decathlon.com/)
[Gemini](https://gemini.google.com/app)
[Grok](https://grok.com/)
[iCloud](https://www.icloud.com/)
[Indeed](https://go.jwint.net/zzz240514100647)
[Linkedin](https://www.linkedin.com/feed/)
[Netflix](https://www.netflix.com/)
[Notion](https://www.notion.so/)
[Office365](https://www.microsoft365.com/)
[Reddit](https://www.reddit.com/)
[Remote job](https://go.jwint.net/zzz240514100810)
[Spotify](https://open.spotify.com/)
[Tech news](https://technews.tw/)
[Twitter](https://twitter.com/)
[UpWork](https://www.upwork.com/nx/find-work/best-matches)
[Walmart](https://www.walmart.com/)
[Zillow](https://www.zillow.com/homes/33596_rb/)
[Zip Recruiter](https://go.jwint.net/zzz240514100727)



🍀
{% for p in site.pages %}{% if p.what %}[。{{ p.what }} ]({{ p.url }}) {% endif %}{% endfor %}

# {{ site.time | date: "%m-%d %H:%M:%S" }}

🍀
{% assign pp = site.pages | sort_natural: "what" %}
{% for p1 in pp %}{% if p1.what %}[。{{ p1.what }} ]({{ p1.url }}){% endif %}{% endfor %}

🍀
{% assign pp = site.pages | sort_natural: "what" %}
<table  cellspacing="1" cellpadding="1" >
{% tablerow p in pp cols:3 %}
  <a href="{{ p.url }}">{{ p.what }}</a>
{% endtablerow %}
</table>

🍀
{% assign pp = site.pages | sort_natural: "what" %}
{% for p1 in pp %}{% if p1.what %}
[🔹{{ p1.what }} ]({{ p1.url }}) 
{% endif %}{% endfor %}

🍀


<script>
    const timeZone = Intl.DateTimeFormat().resolvedOptions().timeZone;


    function showTime() {
      const currentDate = new Date();
      const options = { timeZone: timeZone, hour: '2-digit', minute: '2-digit', second: '2-digit'};
      const timestamp = currentDate.toLocaleString('en-US', options);
      let labelElement = document.getElementById("cnT");
      labelElement.innerHTML = timestamp;
    }    


    setInterval(showTime, 1000);
    showTime();
</script>





<script>


    let cntt = 1;
    const dsurl = "/ds2";
    let initStr = "";
    let nStop = 1;


    async function Get_initStr(){
      try {
        const response = await fetch(dsurl,{cache:'no-store'});
        if (!response.ok) {
          throw new Error(`Response status: ${response.status}`);
        }
        console.log(response.status);
        const json = await response.json();
        console.log(json);
        initStr = json['data'];
        
        const currentDate = new Date();
        const options = { timeZone: timeZone, minute: '2-digit', second: '2-digit'};
        const timestamp = currentDate.toLocaleString('en-US', options);

        let labelElement = document.getElementById("siteTime");
        labelElement.innerHTML = " ^"+timestamp;
      } catch (error) {
        console.error(error.message);
      }
    }
    

    function sleep(s) {
      let ms = s * 1000;
      return new Promise(resolve => setTimeout(resolve, ms));   
    }


    async function getSiteTime() {
      try {
        const response = await fetch(dsurl,{cache:'no-cache'});
        if (!response.ok) {
          throw new Error(`Response status: ${response.status}`);
        }
        //console.log(response.status);
        const json = await response.json();
        //console.log(json); 
        if ( initStr != json['data'] ) {
            console.log(`initStr = ${initStr}, new data = ${json['data']} `);
            let labelElement = document.getElementById("siteTime");
            labelElement.innerHTML = json['data'];
            nStop = 0;
            await sleep(300);
            window.location.reload();     
        } else {
            console.log(`match , initStr == new data = ${json['data']} `);
        }
      } catch (error) {
        console.error(error.message);
      }
    }
    

    function upPage(){
      if( nStop == 0){
        return;
      }
      cntt = cntt + 1 ;
      //showTime();
      if( !(cntt % 3)){
        getSiteTime();
        //getCodeTime();
        //console.log("getSiteTime");
        //cntt = 1 ;
      }
      if( cntt > 300){
        nStop = 0;
        let labelElement = document.getElementById("siteTime");
        labelElement.innerHTML = "_";
      } 
      //updateCnt();
      console.log(`cntt = ${cntt}`);
    }


    Get_initStr();
    setInterval(upPage, 1000);


</script>





🍀 **OWL** 》
[AES](https://aes.jwint.net/)
[Calculate](https://cal.jwint.net/)
[Calendar](https://calendar.jwint.net/)
[Calligraphy](https://calligraphylist.jwint.net/)
[Cartoon](https://carton.jwint.net/)
[CJ code](https://cj.jwint.net/)
[C](https://conline.jwint.net/)
[Colab](https://colab.jwint.net/)
[DailyNews](https://ppp.jwint.net/todaynews)
[Dictionary](https://dic.jwint.net/)
[Disk](https://disk.jwint.net/)
[Earth](https://earth.jwint.net/)
[Earthquake](https://earthquake.jwint.net/)
[Emoji](https://emoji.jwint.net/)
[EmojiFinder](https://emojifinder.jwint.net/)
[Google](https://google.jwint.net/)
[Hash](https://hash.jwint.net/)
[HelloWorld](https://owl.jwint.net/HelloWorld)
[HTMLEditor](https://html.jwint.net/)
[IME](https://ime.jwint.net/)
[Laverna](https://laverna.jwint.net/)
[LiveView](https://liveview.jwint.net/)
[Mail](https://mail.jwint.net/)
[Map](https://map.jwint.net/)
[MDViewer](https://md.jwint.net/)
[MD5](https://md5.jwint.net/)
[Movie](https://movie.jwint.net/)
[MyIP](https://myip.jwint.net/)
[News](https://news.jwint.net/)
[NoteQuickSave](https://n.jwint.net/)
[OnlinePad](https://onlinepad.jwint.net/)
[Python](https://python.jwint.net/)
[QuickPT](https://qp.jwint.net/)
[Radio](https://radio.jwint.net/)
[RainTomorrow](https://rain.jwint.net/)
[RainNow](https://rainnow.jwint.net/)
[Random](https://random.jwint.net/)
[Regex](https://regex.jwint.net/)
[Share](https://share.jwint.net/)
[Shop24](https://shop.jwint.net/)
[Song](https://song.jwint.net/)
[Survey](https://n.jwint.net/)
[Talk](https://talk.jwint.net/)
[Train](https://train.jwint.net/)
[Translator](https://trans.jwint.net/)
[Tool](https://tool.jwint.net/)
[TV](https://tv.jwint.net/)
[UploadFile](https://u.jwint.net/)
[UrlKeep](https://url.jwint.net/)
[Wdav](https://wdav.jwint.net/)
[Weather](https://weather.jwint.net/)
[Windy](https://windy.jwint.net/)
[WuBai](https://500.jwint.net/)
[Youtube](https://youtube.jwint.net/)

🍀 
**Chrome** 》》 
[Chrome netflix setting](chrome://settings/content/all?searchSubpage=netflix)
[Chrome dns cache clean](chrome://net-internals/#dns)


🍀 



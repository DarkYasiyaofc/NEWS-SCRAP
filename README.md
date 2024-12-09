<p align="center">
  <a href="" rel="noopener">
 <img width=200px height=200px src="https://cdn.pixabay.com/photo/2017/06/26/19/03/news-2444778_1280.jpg" alt="Esana"></a>
</p>

<h2 align="center">The Unofficial News Scrapers</h2>


---

## 📝 Table of Contents

- [About](#about)
- [Getting Started](#getting_started)
- [Author](#author)
- [Ada.lk](#ada)
- [Bbc.com](#bbc)
- [Dailymirror.lk](#dailymirror)
- [Gagana.lk](#gagana)
- [Lankadeepa.lk](#lankadeepa)
- [Newswire.lk](#newswire)
- [Sirasa](#sirasa)
- [Hirunews.lk](#hiru)
- [AdaDerana](#derana)
- [Siyathanews.lk](#siyatha)
- [Itnnews.lk](#itn)

## 🧐 About <a name = "about"></a>

The unofficial Scrapers [ Ada.lk, Bbc.com, Dailymirror.lk, Gagana.lk, Lankadeepa.lk. Newswire.lk, Sirasa, Hirunews.lk, Adaderana.lk, Siyathanews.lk, Itnnews.lk ]

## 🏁 Getting Started <a name = "getting_started"></a>

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Installing


```sh
yarn add @dark-yasiya/news-scrap
```

or

```sh
npm i @dark-yasiya/news-scrap
```

## 🍟 Usage <a name="usage"></a>

```ts
const DYXT_NEWS = require('@dark-yasiya/news-scrap');
const news = new DYXT_NEWS();
```

## 01. Ada.lk <a name = "ada"></a>

```ts
const result = await news.ada();
console.log(result);
```
```ts
{
  status: true,
  creator: '@DarkYasiya',
  result: {
    title: 'අධිවේගී මාර්ගයේ දි මෝටර් රථයක් ගිනි ගනී',
    image: 'https://bmkltsly13vb.compat.objectstorage.ap-mumbai-1.oraclecloud.com/cdn.ada.lk/assets/uploads/image_eea0d7abcb.jpg',
    date: '1 12 2024',
    time: '20:14',
    url: 'https://www.ada.lk/breaking_news/අධිවේගී-මාර්ගයේ-දි-මෝටර්-රථයක්-ගිනි-ගනී/11-413383',
    desc: 'දක්ෂිණ අධිවේගී මාර්ගයේ වැලි පැන්න සහ කුරුඳුගහ හැතැප්ම අතර කිලෝමීටර් 66 දශම 6 ප්‍රදේශයේදී අද (1) සවස පිරිසක් ගමන් 
ගත් මෝටර් රථයක් හදිසියේ ගිනි ගැනීමට ලක් වූ බව දක්ෂිණ අධිවේගී රථවාහන පොලිසිය කියයි.ගාල්ල දෙස සිට කොළඹ දෙසට ධාවනය වූ මෝටර් රථය
 හදිසියේ ගිනිගැනීමට ලක්වීී ඇත.ගින්න ඇති වූ වහාම එම ස්ථානයට පැමිණි අධිවේගී මාර්ග කුරුඳුගහ හැතැක්ම ගිනි නිවීමේ ඒකකය මගින් ගින්
න සම්පූර්ණයෙන්ම වැඩ පවත්වා නිවා දැමීමට කටයුතු කළ අතර ඒ වන විටත් මෝටර් රථයේ අඩකට ආසන්න ප්‍රමාණයක් සම්පූර්ණයෙන්ම දැවි ගොස් ඇතැ
යි පොලිසිය කියයි.මෝටර් රථයේ පිටුපස පෙදෙසේ  ඇතිවූ කාර්මික දෝෂයක් හේතුවෙන් ගින්න ඇතිවන්නට ඇතැයි පොලිසිය සැක කරයි. අධිවේගී මාර්
ග කුරුඳු ගහ හැතැප්ම පොලිසිය පරීක්ෂණ පවත්වයිබණ්ඩාරගම බිමල් ශ්‍යාමන් ජයසිංහ  '
  }
}
```

## 02. Bbc.com <a name = "bbc"></a>

```ts
const result = await news.bbc();
console.log(result);
```
```ts
{
  status: true,
  creator: '@DarkYasiya',
  result: {
    title: 'ලිංගික සබඳතාවකදී පිරිමින්  HIVවලින් අරක්ෂා වන්නේ කෙසේ ද? - BBC News සිංහල',
    image: 'https://ichef.bbci.co.uk/ace/ws/640/cpsprodpb/9541/live/913c0f50-ae6f-11ef-b933-b9852e2183c5.jpg.webp',
    desc: 'පැය 8 කට පෙර2023 වසරේ වාර්තා වූ නව HIV වෛරස ආසාදිතයන්ගෙන් 88%ක් පිරිමි පුද්ගලයන් බව නොවැම්බර් 26 දින පැවති මාධ්‍ය
 හමුවකට එක් වෙමින් ශ්‍රී ලංකා ජාතික ලිංගාශ්‍රිත රෝග සහ ඒඩ්ස් මර්දන වැඩසටහනේ අධ්‍යක්ෂිකා වෛද්‍ය වින්ධ්‍යා කුමාරපේළි පැවසුවා ය
.එය වසර 10කට කලින් පැවතියේ 2:1 අනුපාතයක් ලෙස බව ද ඇය පැවසුවා ය.වර්තමානයේ HIV සමග ජීවත් වන අයගෙන් වැඩි ප්‍රතිශතයක් පිරිමි පුද
්ගලයන් ය.තව ද, 2023 වසරේ වාර්තා වී ඇති රෝගීන් 694න් 92 දෙදෙනෙකු වයස අවුරුදු 15 සහ 24 අතර තරුණයෝ වෙති.වාර්තා වන පුද්ගලයින්ගෙන
් බහුතරය පිරිමි වන්නේ ඇයි?මෙලෙස වාර්තා වන්නන්ගෙන් බහුතරයක් පිරිමි වීම පිළිබඳව ද වෛද්‍යවරිය පැහැදිලි කළා ය."මේ විදිහට පිරිමි 
අය අතරින් වැඩි වශයෙන් වෛරසයෙන් වාර්තා වෙන්න ඒ අයගේ ලිංගික චර්යාවන් බලපානවා," ඇය පැවසුවා ය."2023 වාර්තා වුණ රෝගීන්ගෙන් 88%ක් 
පිරිමින්. ළමුන් අතර හෝ, කාන්තාවන් අතර විශේෂ වර්ධනයක් පෙන්නුම් නොකෙරුවත් පසුගිය වසර 10 තුළ දත්ත නිරීක්ෂණය කළ විට අපිට පේනවා ප
ිරිමි අතර HIV වැඩිවීමේ ප්‍රවණතාවක් තියෙනවා," ඇය පැවසුවා ය."අන්තර්ජාලය හරහා සහකරුවන් සොයා ගැනීම, නිසි ලිංගික අධ්‍යපනයක් නොලැබ
ීම සහ මත්ද්‍රව්‍යවලට ඇබ්බැහි වීu," ද අනාරක්ෂිත ලිංගික සබඳතාවලට හේතු වී ඇති බව වෛද්‍ය වින්ධ්‍යා කුමාරපේළි පැවසුවා ය.දැනට ජාති
ක ලිංගාශ්‍රිත රෝග සහ ඒඩ්ස් මර්දන ව්‍යාපාරය විසින් හඳුනාගනු ලැබ ඇති අවදානම් කණ්ඩායම් කිහිපයක් සමග ඔවුන් ආරක්ෂිත ලිංගික සබඳතා 
පැවැත්විය යුත්තේ කෙසේ දැයි දැනුවත් කිරීම් සහ අවශ්‍ය ආරක්ෂිත ක්‍රමවේදයන් ලබා දීම සිදු කරයි.එලෙස හඳුනාගෙන ඇති අවදානම් කණ්ඩායම්
 කිහිපයක් වෛද්‍යවරිය විස්තර කළා ය."පිරිමින් සමග ලිංගික සබඳතා පවත්වන පිරිමි, සංක්‍රාන්තික අවධියේ සිටින සංක්‍රාන්තික ලිංගික පු
ද්ගලයින්, ලිංගික ශ්‍රමිකයින්, සහ බීච් බෝයිස්ලා අපි අවදානම් කණ්ඩායම් ලෙස හඳුනාගෙන ඔවුන් සමග කටයුතු කරමින් ඉන්නවා.'
read more...
  }
}
```

## 03. Dailymirror.lk <a name = "dailymirror"></a>

```ts
const result = await news.dailymirror();
console.log(result);
```
```ts
{
  status: true,
  creator: '@DarkYasiya',
  result: {
    title: 'Nation’s duty is to inspire youth to combat drug problem',
    image: 'https://bmkltsly13vb.compat.objectstorage.ap-singapore-1.oraclecloud.com/cdn.sg.dailymirror.lk/assets/uploads/image_eb578dd7fc.jpg',
    url: 'https://www.dailymirror.lk/breaking-news/Nations-duty-is-to-inspire-youth-to-combat-drug-problem/108-297138',     
    desc: "Colombo, December 1 (Daily Mirror) - It is the nation's responsibility to fight the drug problem by inspiring positive changes in the minds of children and youth, not just by depending on laws, Prime Minister Dr. Harini Amarasuriya said.\n" +
      '\n' +
      "Speaking as the chief guest at the award ceremony for the winners of the 2024 All-Ceylon Art and Animation Video Competition, she said that the fight against drugs is a top priority and an urgent responsibility under the new government's programme.  \n" +
      '\n' +
      "She also said that law enforcement efforts must remain a priority to combat national and international drug trafficking, which poses a serious threat to the country's future by triggering domestic, economic and social crises.\n" +
      '\n' +
      'While appreciating the services by the Sri Lanka Navy and the security forces, the Prime Minister highlighted the urgent need for a programme to combat drug addiction and to rehabilitate the addicts.\n' +
      '\n' +
      'Prime Minister Amarasuriya also said that children should be supported to build a strong future by going beyond merely informing them about the dangers of drugs and providing them with opportunities to showcase their creative talents.'      
  }
}
```

## 04. Gagana.lk <a name = "gagana"></a>

```ts
const result = await news.gagana();
console.log(result);
```
```ts
{
  status: true,
  creator: '@DarkYasiya',
  result: {
    title: 'ඉදිරි පැය ටික ලංකාවට තීරණාත්මකයි?. දිස්ත්‍රික්ක 6ක ජනතාවට විශේෂ දැනුම්දීමක් මෙන්න.. අවදානයෙන්ම ඉන්න..',
    image: 'https://cdn.ibcstack.com/article/31b00351-779a-460a-80f7-e8c9ecbe8dcf/24-674c5c7d51758-md.webp',
    url: 'https://gagana.lk/article/landslide-warnings-issued-for-06-districts-1733057661',
    desc: 'ජාතික ගොඩනැගිලි පර්යේෂණ සංවිධානය විශේෂ දැනුම්දීමක් සිදුකර තිබෙනවා.ඒ දිස්ත්‍රික්ක 06 ක් සඳහා පැනවූ නායයෑම් අනතුරු 
ඇඟවීම් නිවේදන තවදුරටත් දීර්ඝ කළ බවයි.මෙම නිවේදනය ඉදිරි පැය 24 ක කාලය සඳහා වලංගු වන බව සඳහන් වේ.\n' +
      '\n' +
      'අද (01) දින ප.ව. 4.00 සිට හෙට (02) දින ප.ව. 4.00 දක්වා එය වලංගු වේ. \n' +
      ' \n' +
      'අනතුරු ඇඟවීමේ මට්ටම 2 - අවදානයෙන් සිටින්න (ඇම්බර්)\n' +
      ' \n' +
      '1) 1).මහනුවර දිස්ත්‍රික්කය:\n' +
      ' \n' +
      ' උඩුදුම්බර,⁠උඩපලාත, දෙල්තොට,  ගඟවට කෝරළය, පාතහේවාහැට,  ⁠හාරිස්පත්තුව, ⁠පාතදුම්බර, ⁠යටිනුවර,  ⁠මැදදුම්බර, දොළුව, උඩුනු
වර, තුම්පනේ, පූජාපිටිය, පන්විල, පස්බාගෙ කෝරළය ,අකුරණ, හතරලියද්ද, ගඟ ඉහළ කෝරළය\n' +
      '\n' +
      'අනතුරු ඇඟවීමේ මට්ටම 1 - විමසිලිමත් වන්න (කහ)\n' +
      '\n' +
      '2)2).බදුල්ල දිස්ත්‍රික්කය: \n' +
      ' ⁠බදුල්ල, ⁠පස්සර,  ⁠හාලිඇල,  මීගහකිවුල, බණ්ඩාරවෙල\n' +
      '\n' +
      '3)කෑගල්ල දිස්ත්‍රික්කය: \n' +
      ' කෑගල්ල,  ⁠රුවන්වැල්ල, බුලත්කොහුපිටිය,  අරණායක, මාවනැල්ල, යටියන්තොට\n' +
      '\n' +
      '4)කුරුණෑගල දිස්ත්‍රික්කය: \n' +
      ' රිදීගම\n' +
      '\n' +
      '5)මාතලේ දිස්ත්‍රික්කය: \n' +
      ' අඹන්ගග කෝරළය, රත්තොට, උකුවෙල, විල්ගමුව, නාඋල, යටවත්ත, ⁠ පල්ලේපොල, ලග්ගල, පල්ලේගම,මාතලේ\n' +
      '\n' +
      '6)නුවර එළිය දිස්ත්‍රික්කය: \n' +
      ' ⁠හඟුරන්කෙත, කොත්මලේ, වලපනේ  You May Like This Video👇 .'
  }
}
```

## 05. Lankadeepa.lk <a name = "lankadeepa"></a>

```ts
const result = await news.lankadeepa();
console.log(result);
```
```ts
{
  status: true,
  creator: '@DarkYasiya',
  result: {
    title: 'සූර්යකෝෂ විදුලි රැහැනට මුරකරු බිලි',
    date: 'කතෘ මණ්ඩලය  2024 දෙසැම්බර් මස 01',
    image: 'https://bmkltsly13vb.compat.objectstorage.ap-mumbai-1.oraclecloud.com/cdn.lankadeepa.lk/assets/uploads/image_76a00377a0.jpg',
    url: 'https://www.lankadeepa.lk/latest_news/සරයකෂ-වදල-රහනට-මරකර-බල/1-662574',
    desc: '(රංජිත් රාජපක්ෂ  )                   කොත්මලේ , වෙදමුල්ල අලුත් කොටසේ එලවළු වගා භුමියක ඇද තිබු සුර්යකෝෂ විදුලි රැහැ
නක පැටලි අද (01) දින පුද්ගලයෙකු ජිවිතක්ෂයට පත්වි ඇති බව කොත්මලේ පොලිසිය පැවසිය.මෙසේ ජිවිතක්ෂයට පත් වි ඇත්තේ එම වතුයායේ පදිංච
ිව සිටි තංගවේල් ක්‍රිෂ්ණකුමාර් නැමති 67 හැවිරිදි පුද්ගලයෙකි.එම වතුයායේ එලවළු වගා භුමියක වගා කර ඇති එලවළු වන සතුන්ගෙන් ආරක්ෂා
 කර ගැනිම සදහා සුර්යකෝෂ විදුලි ආධාරයෙන් ඇද තිබු විදුලි රැහැනක පැටලි එම පුද්ගලයා ජිවිතක්ෂයට පත් වි ඇති බවට මරණය සම්බන්ධයෙන් ව
ිමර්ෂණ සිදු කරන කොත්මලේ පොලිසිය සැකකරයි.'
  }
}
```

## 06. Newswire.lk <a name = "newswire"></a>

```ts
const result = await news.newswire();
console.log(result);
```
```ts
{
  status: true,
  creator: '@DarkYasiya',
  result: {
    title: 'Jay Shah begins tenure as ICC Chairman',
    image: 'http://www.newswire.lk/wp-content/uploads/2024/12/22bc7524-2a6b-4672-b765-5b73429a59d5.jpeg',
    url: 'https://www.newswire.lk/2024/12/01/jay-shah-begins-tenure-as-icc-chairman/',
    desc: 'Secretary of the Board of Control of Cricket in India (BCCI) Jay Shah has assumed the role of ICC Chair, bringing a wealth of experience from key positions in cricket administration. He succeeds Greg Barclay, who held the position since 
2020.“I am honoured to take on the role of ICC Chair and grateful for the support and trust of the ICC Directors and Member 
Boards,” Shah said in a statement.Shah’s journey in cricket management began in 2009 with the Gujarat Cricket Association, where he oversaw the development of the world’s largest cricket stadium in Ahmedabad. In 2019, he became the youngest-ever Secretary of the Board of Control for Cricket in India (BCCI).He has also served as President of the Asian Cricket Council and Chair of the ICC’s Finance and Commercial Affairs Committee, contributing to cricket’s growth across Asia and globally. Shah is expected to leverage this experience to expand the sport’s global footprint, including its inclusion in the 2028 Los Angeles Olympics. (NewsWire)'
  }
}
```

## 07. Sirasa <a name = "sirasa"></a>

```ts
const result = await news.sirasa();
console.log(result);
```
```ts
{
  status: true,
  creator: '@DarkYasiya',
  result: {
    title: 'සිරස - ශක්ති සහන යාත්‍රාව අද සිට ',
    image: 'https://cdn.newsfirst.lk/sinhala-uploads/2024/12/New Project - 2024-12-01T121316-574267.211',
    url: 'https://sinhala.newsfirst.lk/2024/12/01/%e0%b6%86%e0%b6%b4%e0%b6%af%e0%b7%8f-%e0%b6%ad%e0%b6%ad%e0%b7%8a%e0%b6%ad%e0%b7%8a%e0%b7%80%e0%b6%ba%e0%b7%99%e0%b6%b1%e0%b7%8a-%e0%b6%b4%e0%b7%93%e0%b6%a9%e0%b7%8f',
    desc: 'COLOMBO (News 1st) - ඇති වූ ආපදා තත්ත්වය හේතුවෙන් අපහසුතාවට පත්ව අභියෝගයන්ට මුහුණදෙමින් සිටින ජනතාවට සහයක් වීම සඳ
හා සිරස - ශක්ති සහන යාත්‍රාව අද (01) සිට ක්‍රියාත්මක වේ.ඒ වෙනුවෙන් සහල්, පරිප්පු, සීනි, පාන්පිටි, නූඩ්ල්ස්, තේ කොළ සහ සෝයා ම
ීට්, ඔබට භාරදිය හැකියි.භාණ්ඩ රැස් කිරීම සඳහා විශේෂ මධ්‍යස්ථාන 5 ක් ස්ථාපිත කර තිබේ.1. කොළඹ 4, බම්බලපිටිය කදිරේසන් වජිර කෝවිල
,2. දෙහිවල නැදිමාල ශ්‍රී වෙන්කර්ටේශ්වරන් මහා විෂ්ණු කෝවිල,3. කොළඹ නව හෙට්ටිවීදිය සායි මධ්‍යස්ථානය මෙන්ම,4. කොළඹ 12 ප්‍රධාන ම
ුස්ලිම් පල්ලියකොළඹ 02, බේබෲක් පෙදෙස සිරස TV ප්‍රධාන මූලස්ථාන පරිශ්‍රයට පැමිණ, ඔබට භාණ්ඩ භාරදිය හැකි ය.0777 6000 40 දුරකතන අං
කය ඇමතීමෙන්, සිරස - ශක්ති සහන යාත්‍රාව පිළිබඳ වැඩි විස්තර ලබාගත හැකියි.'
  }
}
```

## 08. Hirunews.lk <a name = "hiru"></a>

```ts
const result = await news.hiru();
console.log(result);
```
```ts
{
  status: true,
  creator: '@DarkYasiya',
  result: {
    title: 'හාල්, පොල්, එළවලු මිල ඉහළට',
    image: 'https://cdn.hirunews.lk/Data/News_Images/202412/1733063994_45810_hirunews.jpg',
    url: 'https://www.hirunews.lk/389581/හාල්-පොල්-එළවලු-මිල-ඉහළට',
    desc: '* පසුගිය දිනවල පැවති අයහපත් කාලගුණික තත්ත්වය හේතුවෙන් මේ වන විට ආර්ථික මධ්‍යස්ථානවල එළවළු මිල ගණන් සීඝ්‍ර ලෙස ඉහළ
 ගොස් තිබෙනවා.  දඹුල්ල ආර්ථික මධ්‍යස්ථානය වෙත ලැබෙන එළවළු ප්‍රමාණය සියයට 65ක් දක්වා පහළ අගයක පැවතීම හේතුවෙන් එළවළු මිළ ගණන්ද
 ඉහළ අගයක පවතිනවා.\n' +
      '\n' +
      '* කෙසේ වෙතත් වර්ෂාවත් සමග සිය නිෂ්පාදනවල පහත යාම හේතුවෙන් තමන් දැඩි ආර්ථික අපහසුතාවයකට පත්ව ඇති බව කෙසෙල් ගොවීන් පවසන
වා.\n' +
      '\n' +
      '* වෙළෙඳපොළ තුළ පවතින මිල ඉහළ යෑම සැළකිල්ලට ගනිමින් ආනයනික ලොකු ලූණු කිලෝවක් සඳහා පනවා තිබු රුපියල් 30ක විශේෂ වෙළෙඳ භා
ණ්ඩ බද්ද රුපියල් 10ක් දක්වා අඩුකිරීමට රජය තීරණය කළා.\n' +
      '\n' +
      '*  මුදල් අමාත්‍යාංශය පැවසුවේ, එම සහනය මේ මස 31 වැනිදා දක්වා බල පැවැත්වෙන බවයි.\n' +
      '\n' +
      '*  මේ අතර, වෙළෙඳපොළ තුළ තවමත් පාලන මිල ඉක්මවා සහල් අලෙවි වන බවට පාරිභෝගිකයින් චෝදනා කරනවා.\n' +
      '\n' +
      '* එක්සත් සහල් නිෂ්පාදකයින්ගේ සංගමය පෙන්වා දෙන්නේ, හිටපු ජනාධිපති ගෝඨාභය රාජපක්ෂ සමයේ නිකුත් කළ ගැසට් නිවේදන දෙකක් මත 
පදනම්ව වත්මන් රජය ක්‍රියා කිරීම හේතුවෙන් සහල් මිල අඩු කිරීමට රජයට නොහැකි වී ඇති බවයි.\n' +
      '\n' +
      '* පසුගිය මාස කිහිපයේ සිටම වෙළෙඳපොළ තුළ නාඩු සහල් හිගයක් පැවතියා.\n' +
      '\n' +
      '* ඊට විසඳුමක් දීම සඳහා රජය සුළු හා මධ්‍ය පරිමාණ මෝල් හිමියන් සමග අවස්ථා කිහිපයකදීම සාකච්ඡා පැවැත්වුවත් එය සාර්ථක වූයේ
 නැහැ. \n' +
      '\n' +
      '* කෙසේ වෙතත්, වෙළෙඳපොළේ පවතින නාඩු සහල් හිගයට සහ සහල් මිල පාලනය කිරීම සඳහා නාඩු සහල් මෙටි්‍රක් ටොන් 70,000ක් ආනයනය කි
රීමට රජය පසුගියදා තීරණය කළා.\n' +
      '\n' +
      '* මේ අතර, හිටපු ජනාධිපති ගෝඨාභය රාජපක්ෂ සමයේ නිකුත් කළ ගැසට් නිවේදන දෙකක් මත පදනම්ව වත්මන් රජය කටයුතු කිරීම හේතුවෙන් 
සහල් මිල අඩු කිරීමට නොහැකි තත්වයක් උද්ගත වී ඇති බව එක්සත් සහල් නිෂ්පාදකයින්ගේ සංගමයේ සභාපති මුදිත පෙරේරා කියා සිටියා.\n' +  
      '\n' +
      '* එවන් පසුබිමක වෙලදපොළේ පොල් මිලද තවදුරටත් ඉහළ යමින් පවතිනවා. \n' +
      '\n' +
      '* ඇතැම් ප්‍රදේශවල පොල් හිගයක්ද පවතින බවටයි වාර්තා වන්නේ.කෙසේ වෙතත්, උත්සව සමයේ අත්‍යාවශ්‍ය භාණ්ඩ රැසක මිල අඩු කිරීමට 
ආණ්ඩුව සූදානම් බවයි වෙළෙඳ, වානිජ, ආහාර සුරක්ෂිතතා සහ සමූපකාර සංවර්ධන අමාත්‍ය වසන්ත සමරසිංහ ප්‍රකාශ කළේ.'
  }
}
```

## 09. Adaderana.lk <a name = "derana"></a>

```ts
const result = await news.derana();
console.log(result);
```
```ts
{
  status: true,
  creator: '@DarkYasiya',
  result: {
    title: 'වෙළෙඳපොළේ පොල් හිඟයක්',
    date: 'December 1, 2024  \t\t08:46 pm',
    image: 'https://s3.amazonaws.com/adaderanasinhala/1733066724-coconut_L.jpg',
    url: 'https://sinhala.adaderana.lk/news/203936',
    desc: 'වෙළෙඳපොළ තුළ මේ දිනවල උද්ගතව ඇති පොල් හිඟයත් සමග පොල් මිල පවතින්නේ ඉතා ඉහළ අගයකය.ඒ අනුව මේ වනවිට වෙළෙඳපොළේ පොල් ග
ෙඩියක මිල රුපියල් 200 සීමාව දක්වා ඉහළ නැග තිබේ.පාරිභෝගික ජනතාව පවසන්නේ සහල් මෙන්ම පොල් හිඟයක්ද වෙළෙඳපොළේ පවතින බවය.එවන් පසුබ
ිමක ජනතාව වැඩි වශයෙන් පරිභෝජනය කරන නාඩු, කැකුළු සහල්වලද හිඟයක් පවතී.එමෙන්ම එක්සත් සහල් නිෂ්පාදකයින්ගේ සංගමය පෙන්වාදෙන්නේ සිල
්ලර සහල් අලෙවිය සඳහා රජය පනවා ඇති පාලන මිලද ඉක්මවා සහල් තොග මිල ඉහළගොස් ඇති බවය.මේ අතර ලොකු ලූනු ආනයන බදු සංශෝධනය කිරිමට වෙළ
ඳ අමාත්‍යංශය තීරණය කර තිබේ.ඒ අනුව ආනයනික ලොකු ලූනු සඳහා පැවති රුපියල් 30ක් වූ විශේෂ වෙළඳ භාණ්ඩ බද්ද අද (01) සිට ක්‍රියාත්මක 
වන පරිදි රුපියල් 10ක් දක්වා අඩුකිරීමටත් ආනයනික අර්තාපල් සඳහා මෙතෙක් පැවති රුපියල් 60ක් වූ විශේෂ වෙළඳ භාණ්ඩ බද්ද එලෙසම පවත්වා
ගැනීමටත් තීරණය කෙරුණි.වෙළෙඳපොළෙහි ලොකු ලූනු මිල ඉහළයමින් පවතිද්දී, කාලගුණ තත්ත්වය සහ එළැඹෙන උත්සව සමය මුල්කරගනිමින් තවදුරටත්
 මෙම භාණ්ඩ මිල ඉහළයාම වළක්වා ගැනීම සඳහා දෙසැම්බර් මස 31 දක්වා මෙම නව බදු සංශෝධනය ක්‍රියාත්මක බව මුදල්, ක්‍රමසම්පාදන සහ ආර්ථි
ක සංවර්ධන අමාත්‍යංශය සඳහන් කළේය.\n' +
      ' '
  }
}
```

## 10. Siyathanews.lk <a name = "siyatha"></a>

```ts
const result = await news.siyatha();
console.log(result);
```
```ts
{
  status: true,
  creator: '@DarkYasiya',
  result: {
    title: 'ලංකාවේ පළමු තරු හතේ හෝටලය (VIDEO)',
    image: 'https://siyathanews.lk/wp-content/uploads/2024/02/siyatha-news-logo-1-400x242-1-e1708949411400.png',
    date: 'December 8, 2024',
    url: 'https://siyathanews.lk/archives/156264',
    desc: 'තෙල්දෙණියේ ඉදිවන අවියාන හෝටලය ලබන වසරේදී විවෘත කිරීමට සැලසුම් කර තිබෙනවා.එය ශ්‍රී ලංකාවේ ප්‍රථම තරු 7 හෝටලයයි.මේ පිළිබඳව
 සහ තවත් තොරතුරු පහතින් නැරඹිය හැකියි.'
  }
}
```

## 11. Itnnews.lk <a name = "itn"></a>

```ts
const result = await news.itn();
console.log(result);
```
```ts
{
  status: true,
  creator: '@DarkYasiya',
  result: {
    title: 'අනවසර ධීවර කටයුතු සිදුකළ ඉන්දීය ධීවරයින් 8ක් අත්අඩංගුවට',
    image: 'https://www.itnnews.lk/wp-content/uploads/2024/12/i12222222222222222-860x615.jpg',
    date: 'දෙසැම්බර් 8, 2024',
    url: 'https://www.itnnews.lk/2024/12/08/646440/',
    desc: 'ශ්‍රී ලංකා නාවික හමුදාව, වෙරළ ආරක්‍ෂක දෙපාර්තමේන්තුව හා එක්ව, අද (08)දින යාපනය, ඩෙල්ෆ්ට් දූපතට ඔබ්බෙන් වූ මෙරට මුහුදු සී
මාව තුළ අනවසර ධීවර කටයුතු සිදු ක ඉන්දීය ධීවරයින් (08)ක් අත්අඩංගුවට ගෙන තිබෙනවා.එහිදී, යාපනය මුහුදු ප්‍රදේශයේ අනවසර ධීවර කටයුතු සිදු
 කරමින් සිටි ඉන්දීය ධීවර යාත්‍රා දෙකක් (02)ක් ද භාරයට ගත් බවයි නාවික හමුදාව පවසන්නේ.මෙම මෙහෙයුම මඟින් අත්අඩංගුවට ගත් ඉන්දීය ධීවර යා
ත්‍රා දෙක (02) සහ එහි සිටි ඉන්දීය ධීවරයින් අට දෙනා (08) කන්කසන්තුරය වරාය වෙත රැගෙන ආ අතර, ඉදිරි නීතිමය කටයුතු සඳහා මයිලඩි ධීවර පරීක
්‍ෂක කාර්යාලය වෙත භාර දීමට නියමිතයි.එමෙන්ම 2024 වර්ෂයේ මේ දක්වා සිදුකළ මෙහෙයුම් මඟින් මෙරට මුහුදු සීමාව තුළ අනවසර ධීවර කටයුතු සිදුක
ළ ඉන්දීය ධීවර යාත්‍රා (70)ක් සහ ඉන්දීය ධීවරයින් (537)ක් අත්අඩංගුවට ගත් බවයි නාවික හමුදාව සඳහන් කළේ.'
  }
}
```

## 🖋 Author <a name = "author"></a>

- [@DarkYasiya](https://github.com/DarkYasiyaofc) - scraped author

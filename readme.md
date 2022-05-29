# OpenStreetMap मराठी

**OpenStreetMap (OSM) "ओपन स्ट्रीट मॅप" वर मराठी भाषेतील माहिती वाढवण्यासाठी काही साधने व मार्गदर्शक माहितीचा संग्रह.**

OpenStreetMap हा मानचित्रकारांनी उभारलेला एक प्रकल्प आहे ज्यात जगभरातील रस्ते, पायवाट, कॅफे, रेल्वे स्थानक व इतर बऱ्याच गोष्टींचा डेटा योगदानातून तयार व व्यवस्थापित केला जातो.

OSM नकाशा [इथे पहा](https://www.openstreetmap.org/).

सध्या OSM वर मराठी भाषेत माहिती खूपच कमी प्रमाणात उपलब्ध आहे.
माहिती मुखतः दोन ठिकाणी जोडायची आहे -

१. OSM नकाशावर

२. OSM विकी (ज्ञानकोश) वर - जिथे, OSM म्हणजे काय? त्याचे फायदे? कसे वापरायचे? नकाशावर डेटा कसा जोडायचा? व इतर प्रश्नांची उत्तरे सखोल माहितीसह उपलब्ध आहे.

## OSM विकिपीडिया

[OSM विकी मराठी मुखपृष्ठ](https://wiki.openstreetmap.org/wiki/Mr:Main_Page)

भारतात ठिकाणे जोडण्याचे मार्गदर्शक (अद्याप मराठीत उपलब्ध नाही) - 

- https://wiki.openstreetmap.org/wiki/India/Places
- https://wiki.openstreetmap.org/wiki/India/Administrative_Boundaries

## OSM नकाशावरील माहिती

OSM वरील मराठी `name:mr` नावाच्या टॅगची माहिती: 
https://taginfo.openstreetmap.org/keys/name%3Amr

#### महाराष्ट्र राज्य

मराठी नाव (`name:mr` टॅग) नसलेल्या ठिकाणाची संख्या -

| ठिकाण वर्ग| place=? टॅग | अपूर्ण संख्या (२०२२-५-२६ रोजी) | नकाशावर पहा. (दुव्यावर जाऊन "Run" दाबा)
| --- | --- | --- | --- |
| शहर| place=city | ० 😃 | https://overpass-turbo.eu/s/1iFP
| नगर| place=town | ० 😃 | https://overpass-turbo.eu/s/1iFH
| उपनगर| place=suburb | १९६ (सर्व मुंबईत) 😟 | https://overpass-turbo.eu/s/1iFQ
| परिसर| place=neighbourhood | ५३६ 😟 | https://overpass-turbo.eu/s/1iFR
| गाव| place=village | ५०३८ 😢 | https://overpass-turbo.eu/s/1iFS
| खेडे| place=hamlet | ७६६ 😟 | https://overpass-turbo.eu/s/1iFX

#### इतर राज्य/देश

_नंतर जोडणे_

## साधने

### टायपिंग व अनुवाद

- देवनागरी मध्ये लिहिण्यासाठी -
https://www.google.com/intl/mr/inputtools/try/

- अनुवाद तपासण्यासाठी -
  - https://shabdakosh.marathi.gov.in/ (आधुनिक व तांत्रिक शब्द सापडतील)
  - https://dsal.uchicago.edu/dictionaries/marathi/ (जुने शब्द सापडतील)
  - https://translate.google.com/?sl=mr&tl=en&op=translate (कधीकधी चुकते. सावधानीने वापरावे.)

### Overpass turbo

[Overpass turbo](https://overpass-turbo.eu/) हे नकाशावरून अनेक प्रकारचा डेटा खणून पाहण्याचे व निर्यात करण्याचे [एक साधन आहे](https://wiki.openstreetmap.org/wiki/Overpass_turbo).

[जादूगारचे](https://wiki.openstreetmap.org/wiki/Overpass_turbo#Query_wizard) उदाहरण - 

१. महाराष्ट्रातील मराठी नावे नसलेली सर्व ठिकाणे = `type:node and name=* and name:mr!=* and place=*  in Maharashtra`

_(**अर्थ** - महाराष्ट्रातील (`in Maharashtra`) नाव असलेले(`name=*`), पण मराठी नाव नसलेल्या(`name:mr!=*`) अश्या ठिकाणांच्या(`place=*`) गाठी(`type:node`))_

२. महाराष्ट्रातील सर्व शाळा = `type:node and amenity=school in Maharashtra`. २०२२-मे-२८ रोजी नकाशा -

![image](https://user-images.githubusercontent.com/74632379/170809419-a93fdd09-77d6-46b3-b299-cd28d3a086ee.png)


३. अनेक ठिकाणांमधून शोधण्यासाठी प्रश्नांची संरचना - https://overpass-turbo.eu/s/1iQi

### विकिपीडिया

मराठी विकिपीडियातील उपयुक्त माहिती [इथे](wiki-varg/) साठवली आहे.

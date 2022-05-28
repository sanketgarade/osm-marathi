# OSM मराठी

**[OpenStreetMap](https://www.openstreetmap.org/) (OSM) वर मराठी भाषेतील माहिती वाढवण्यासाठी काही साधने व मार्गदर्शक माहितीचा संग्रह.**

[OSM म्हणजे काय?](https://wiki.openstreetmap.org/wiki/Mr:Main_Page)

सध्या OSM वर मराठी भाषेत माहिती खूपच कमी प्रमाणात उपलब्ध आहे.
माहिती मुखतः दोन ठिकाणी जोडायची आहे -

१. OSM नकाशावर डेटाच्या स्वरूपात

२. OSM विकी (ज्ञानकोश) वर - जिथे, OSM म्हणजे काय? त्याचे फायदे? कसे वापरायचे? नकाशावर डेटा कसा जोडायचा? व इतर प्रश्नांची उत्तरे सखोल माहितीसह उपलब्ध आहे.

## OSM विकी वरील माहिती

[OSM विकी मराठी मुखपृष्ठ](https://wiki.openstreetmap.org/wiki/Mr:Main_Page)


## OSM नकाशावरील माहिती

OSM वरील मराठी `name:mr` नावाच्या टॅगची माहिती: 
https://taginfo.openstreetmap.org/keys/name%3Amr

### ठिकाणे

भारतात ठिकाणे जोडण्याचे मार्गदर्शक (अद्याप मराठीत उपलब्ध नाही) - 

https://wiki.openstreetmap.org/wiki/India/Places

https://wiki.openstreetmap.org/wiki/India/Administrative_Boundaries

#### महाराष्ट्र

मराठी नाव (`name:mr` टॅग) नसलेल्या ठिकाणाची संख्या -

| place=? टॅग | अपूर्ण संख्या (२०२२-५-२६ रोजी) | नकाशावर पहा. (दुव्यावर जाऊन "Run" दाबा)
| --- | --- | --- |
| place=city | ० 😃 | https://overpass-turbo.eu/s/1iFP
| place=town | ० 😃 | https://overpass-turbo.eu/s/1iFH
| place=suburb | २४९ 😟 | https://overpass-turbo.eu/s/1iFQ
| place=neighbourhood | ५३६ 😟 | https://overpass-turbo.eu/s/1iFR
| place=village | ५०३८ 😢 | https://overpass-turbo.eu/s/1iFS
| place=hamlet | ७६६ 😟 | https://overpass-turbo.eu/s/1iFX

## साधने

### टायपिंग व अनुवाद

- देवनागरी मध्ये लिहिण्यासाठी -
https://www.google.com/intl/mr/inputtools/try/

- अनुवाद तपासण्यासाठी -
https://translate.google.com/?sl=mr&tl=en&op=translate

### [Overpass turbo](https://overpass-turbo.eu/)

Overpass turbo हे नकाशावरून अनेक प्रकारचा डेटा खणून पाहण्याचे व निर्यात करण्याचे एक साधन आहे.

[विकी](https://wiki.openstreetmap.org/wiki/Overpass_turbo)

[जादूगारचे](https://wiki.openstreetmap.org/wiki/Overpass_turbo#Query_wizard) उदाहरण - 

महाराष्ट्रातील मराठी नावे नसलेली सर्व ठिकाणे = `type:node and name=* and name:mr!=* and place=*  in Maharashtra`

**अर्थ** - महाराष्ट्रातील (`in Maharashtra`) नाव असलेले(`name=*`), पण मराठी नाव नसलेल्या(`name:mr!=*`) अश्या ठिकाणांच्या(`place=*`) गाठी(`type:node`)

महाराष्ट्रातील सर्व शाळा = `type:node and amenity=school in Maharashtra`

![image](https://user-images.githubusercontent.com/74632379/170809419-a93fdd09-77d6-46b3-b299-cd28d3a086ee.png)


अनेक ठिकाणांमधून शोध - https://overpass-turbo.eu/s/1iPw


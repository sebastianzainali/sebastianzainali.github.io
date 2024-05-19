---
layout: links
# multilingual page pair id, this must pair with translations of this page. (This name must be unique)
lng_pair: id_links

# publish date (used for seo)
# if not specified, site.time will be used.
#date: 2022-03-03 12:32:00 +0000

# for override items in _data/lang/[language].yml
#title: My title
#button_name: "My button"
# for override side_and_top_nav_buttons in _data/conf/main.yml
#icon: "fa fa-bath"

# seo
# if not specified, date will be used.
#meta_modify_date: 2022-03-03 12:32:00 +0000
# check the meta_common_description in _data/owner/[language].yml
#meta_description: ""

# optional
# please use the "image_viewer_on" below to enable image viewer for individual pages or posts (_posts/ or [language]/_posts folders).
# image viewer can be enabled or disabled for all posts using the "image_viewer_posts: true" setting in _data/conf/main.yml.
#image_viewer_on: true
# please use the "image_lazy_loader_on" below to enable image lazy loader for individual pages or posts (_posts/ or [language]/_posts folders).
# image lazy loader can be enabled or disabled for all posts using the "image_lazy_loader_posts: true" setting in _data/conf/main.yml.
#image_lazy_loader_on: true
# exclude from on site search
#on_site_search_exclude: true
# exclude from search engines
#search_engine_exclude: true
# to disable this page, simply set published: false or delete this file
#published: false


# you can always move this content to _data/content/ folder
# just create new file at _data/content/links/[language].yml and move content below.
###########################################################
#                Links Page Data
###########################################################
page_data:
  main:
    header: "Forskningsaktiviteter"
    info: "På denna sida kan du hitta information om alla mina pågående undervisningsaktiviteter inom solenergi och maskininlärning vid Mälardalens universitet i Sverige. Dessutom visas mina konferenser och andra forskningsaktiviteter."

  # To change order of the Categories, simply change order. (you don't need to change list order.)
  category:
    - title: "Undervisning vid Mälardalens universitet"
      type: id_jekyiiliquid
      color: "gray"
    - title: "Konferenser, seminarier och workshops"
      type: id_conf
      color: "green"


  list:
    -
    # jekyiiliquid
    - type: id_jekyiiliquid
      title: "ERA318 - Simuleringar och prognoser av elmarknader"
      url: "https://www.mdu.se/en/malardalen-university/education/courses?kod=ERA318"
      info: "Föreläsningar om den kommersiella PV-programvaran PVsyst lär studenterna hur man utvecklar PV-projekt för bostadsapplikationer. I dessa föreläsningar täcker vi praktiska begränsningar, implementering av skuggscener, PV-ekonomi och övervägande av att integrera batterilagring i applikationen."
    - type: id_jekyiiliquid
      title: "ERA306 - Hållbara energisystem - Avancerade studier"
      url: "https://www.mdu.se/en/malardalen-university/education/courses?kod=ERA306"
      info: "Denna kurs har samma föreläsningar som ERA318 om den kommersiella PV-programvaran PVsyst lär studenterna hur man utvecklar PV-projekt för bostadsapplikationer. I dessa föreläsningar täcker vi praktiska begränsningar, implementering av skuggscener, PV-ekonomi och övervägande av att integrera batterilagring i applikationen."
    - type: id_jekyiiliquid
      title: "ERA217 - Introduktion till hållbart energisystem"
      url: "https://www.mdu.se/en/malardalen-university/education/courses?kod=ERA217"
      info: "En enklare föreläsning om hur man använder PVsyst för att lära studenterna hur man utvecklar ett enkelt projekt och får fram ekonomin."
    - type: id_jekyiiliquid
      title: "ERA125 - Solenergi"
      url: "https://www.mdu.se/en/malardalen-university/education/courses?kod=ERA125"
      info: "I denna kurs används den enkla föreläsningen om hur man använder PVsyst. Dessutom genomförs en experimentell föreläsning med studenterna genom att koppla två solmoduler i serie/parallell för att skapa IV-kurvan med våra lampor och variabelt motstånd."
    - type: id_jekyiiliquid
      title: "MTK337- Multivariat dataanalys inom teknik"
      url: "https://www.mdu.se/en/malardalen-university/education/courses?kod=MTK337"
      info: "En föreläsning om rekurrenta neurala nätverk, long-short term memory (LSTM) och bi-LSTM inklusive en praktisk övning genom att förutsäga solenergi produktionen."
    - type: id_jekyiiliquid
      title: "ERA403- Examensarbete inom energiteknik"
      url: "https://www.mdu.se/en/malardalen-university/education/courses?kod=ERA403"
      info: "Jag är handledare för examensarbeten med fokus på solenergitillämpningar."
    # id_conf
    - type: id_conf
      title: "Agrivoltaics Conference 2022 - Piacenza, Italien"
      url: "https://www.tib-op.org/ojs/index.php/agripv/index."
      info: "Höll en posterpresentation om direkt och diffus skuggning för agrivoltaiska system."
    - type: id_conf
      title: "NextGems Hackathon 2022 - Wien, Österrike"
      url: "https://nextgems-h2020.eu/hackathon/"
      info: "Jag arbetade med SR-ESMs IFS och ICON-modeller för att förbättra förnybara energisystem. Inledningsvis analyserade jag data för att utvärdera noggrannheten i nuvarande solstrålningsberäkningar för fotovoltaisk (PV) modellering. Dessutom utvecklade jag en rutnätsmodell för att beräkna PV-produktionspotentialen för hela regionen."
    - type: id_conf
      title: "Agrivoltaic workshop 2022 - Västerås, Sverige"
      url: "https://www.mdu.se/en/malardalen-university/research/research-projects/evaluation-of-the-first-agrivoltaic-system-in-sweden"
      info: "Jag presenterade framtida riktningar baserat på insikter från vårt första projekt i Sverige, som fokuserade på agrivoltaiska system. Betoningen låg på modellerings- och optimeringsstrategier."
    - type: id_conf
      title: "Agrivoltaics Conference 2023 - Daegu, Sydkorea"
      url: "https://www.agrivoltaics-conference.org/history-and-past-conferences"
      info: "Jag höll en posterpresentation om 3D-vyfaktormodellering för vertikala, enaxliga och tvåaxliga agrivoltaiska system, med betoning på metoder för att uppskatta elproduktionen. Ett konferensdokument godkändes och publicerades om detta."
---

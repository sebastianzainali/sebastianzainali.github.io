---
layout: links
# flerspråkigt sidpar id, detta måste paras ihop med översättningar av denna sida. (Detta namn måste vara unikt)
lng_pair: id_links

# publiceringsdatum (används för seo)
# om det inte är specificerat, kommer site.time att användas.
#date: 2022-03-03 12:32:00 +0000

# för att åsidosätta objekt i _data/lang/[language].yml
#title: Min titel
#button_name: "Min knapp"
# för att åsidosätta side_and_top_nav_buttons i _data/conf/main.yml
#icon: "fa fa-bath"

# seo
# om det inte är specificerat, kommer datum att användas.
#meta_modify_date: 2022-03-03 12:32:00 +0000
# kontrollera meta_common_description i _data/owner/[language].yml
#meta_description: ""

# valfritt
# använd "image_viewer_on" nedan för att aktivera bildvisare för individuella sidor eller inlägg (_posts/ eller [language]/_posts mappar).
# bildvisare kan aktiveras eller inaktiveras för alla inlägg genom att använda inställningen "image_viewer_posts: true" i _data/conf/main.yml.
#image_viewer_on: true
# använd "image_lazy_loader_on" nedan för att aktivera lazy loader för bilder för individuella sidor eller inlägg (_posts/ eller [language]/_posts mappar).
# lazy loader för bilder kan aktiveras eller inaktiveras för alla inlägg genom att använda inställningen "image_lazy_loader_posts: true" i _data/conf/main.yml.
#image_lazy_loader_on: true
# uteslut från platsens sökning
#on_site_search_exclude: true
# uteslut från sökmotorer
#search_engine_exclude: true
# för att inaktivera denna sida, ställ helt enkelt in published: false eller ta bort denna fil
#published: false

# du kan alltid flytta detta innehåll till _data/content/ mappen
# skapa bara en ny fil på _data/content/links/[language].yml och flytta innehållet nedan.
###########################################################
#                Länksidans data
###########################################################
page_data:
  main:
    header: "Länkar"
    info: "Beskrivningen av din länksida."

  # För att ändra ordning på kategorierna, ändra bara ordningen. (du behöver inte ändra listordningen.)
  category:
    - title: "Jekyll / Liquid"
      type: id_jekyiiliquid
      color: "gray"
    - title: "Webbdesign"
      type: id_webdesign
      color: "#F4A273"
    - title: "Programmering"
      type: id_programming
      color: "#62b462"

  list:
    -
    # programmering
    - type: id_programming
      title: "Stack Overflow"
      url: "https://stackoverflow.com/"
      info: "Stack Overflow är en webbplats med frågor och svar för professionella och entusiastiska programmerare."

    # jekyiiliquid
    - type: id_jekyiiliquid
      title: "Jekyll"
      url: "https://jekyllrb.com/"
      info: "Förvandla din råa text till statiska webbplatser och bloggar."
    - type: id_jekyiiliquid
      title: "Jekyll fusklapp"
      url: "https://cloudcannon.com/community/jekyll-cheat-sheet/"
      info: "Det finns så många variabler och filter i Jekyll att det kan vara svårt att komma ihåg allt. Denna fusklapp fungerar som en snabb referens för allt som Jekyll kan göra."
    - type: id_jekyiiliquid
      title: "Liquid för designers"
      url: "https://github.com/Shopify/liquid/wiki/Liquid-for-Designers"
      info: "Liquid wiki för designers på GitHub."
    - type: id_jekyiiliquid
      title: "Liquid för programmerare"
      url: "https://github.com/Shopify/liquid/wiki/Liquid-for-Programmers"
      info: "Liquid wiki för programmerare på GitHub."
    - type: id_jekyiiliquid
      title: "Liquid referens"
      url: "https://shopify.dev/api/liquid/"
      info: "Liquid är ett mallningsspråk skapat av Shopify och skrivet i Ruby. Det är nu tillgängligt som ett open source-projekt på GitHub."

    # webbdesign
    - type: id_webdesign
      title: "W3Schools"
      url: "https://www.w3schools.com/"
      info: "W3Schools erbjuder gratis onlinehandledningar, referenser och övningar på alla större webbspråk. Täcker populära ämnen som HTML, CSS, JavaScript, Python, SQL, Java och många fler."
---
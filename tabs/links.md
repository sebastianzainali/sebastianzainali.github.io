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
    header: "Teaching"
    info: "I am teaching solar energy and machine learning at Mälardalen University in Sweden."

  # To change order of the Categories, simply change order. (you don't need to change list order.)
  category:
    - title: "Courses at Malardalen University"
      type: id_jekyiiliquid
      color: "gray"


  list:
    -
    # jekyiiliquid
    - type: id_jekyiiliquid
      title: "ERA318 - Simulations and forecasting of electricity markets"
      url: "https://www.mdu.se/en/malardalen-university/education/courses?kod=ERA318"
      info: "Transform your plain text into static websites and blogs."
    - type: id_jekyiiliquid
      title: "ERA306 - Sustainable Energy Systems - Advanced Studies"
      url: "https://www.mdu.se/en/malardalen-university/education/courses?kod=ERA306"
      info: "There are so many Jekyll variables and filters to remember and it can be tricky to keep it all in your head. This cheat sheet serves as a quick reference of everything Jekyll can do."
    - type: id_jekyiiliquid
      title: "ERA217 - Introduction to sustainable energy system"
      url: "https://www.mdu.se/en/malardalen-university/education/courses?kod=ERA217"
      info: "Liquid for Designers wiki on GitHub."
    - type: id_jekyiiliquid
      title: "ERA125 - Solar energy"
      url: "https://www.mdu.se/en/malardalen-university/education/courses?kod=ERA125"
      info: "Liquid for Programmers wiki on GitHub."
    - type: id_jekyiiliquid
      title: "MTK337- Multivariate data analysis in engineering"
      url: "https://www.mdu.se/en/malardalen-university/education/courses?kod=MTK337"
      info: "Liquid is a template language created by Shopify and written in Ruby. It is now available as an open source project on GitHub."
    - type: id_jekyiiliquid
      title: "ERA403- Degree project in energy engineering"
      url: "https://www.mdu.se/en/malardalen-university/education/courses?kod=ERA403"
      info: "Liquid is a template language created by Shopify and written in Ruby. It is now available as an open source project on GitHub."

---

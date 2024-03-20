Declare a HTML document with appropriate doctype and language attributes
Head section:
  - Meta tags for character set and viewport
  - Title of the document
  - External stylesheet link (style.css)
  - External JavaScript script (index.js) with defer attribute
  - Preconnect links for Google Fonts and fontawesome
  - External JavaScript library script (Splide)
  - External stylesheet link for Splide CSS

Body section:
  - Main container with class "watch-store-homepage" and id "homepageSection"
    - Product card container
      - Navigation header with class "nav-heading header"
      - Watch slider content section with id "sliderMainSection"
        - Content section with class "contentSection"
          - Watch title with id "watch-title"
          - Watch title information with id "watch-title-info"
          - Watch title highlight with id "watch-title-highlight"
          - Watch description with class "watch-title-description"
          - Watch price with class "watch-price"
          - Social media image with class "social-img" and id "socialImg1"
        - Splide slider section with class "splide watch-slide-section" and aria-label "Splide Basic HTML Example"
          - Splide track with class "splide__track custom-splide"
            - Unordered list with class "splide__list"
              - List items with class "splide__slide"
                - Images of watches
        - Social media image with class "social-img" and id "socialImg2"
  - External JavaScript script (index.js) at the end of the body

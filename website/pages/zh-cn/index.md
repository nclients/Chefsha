---
layout: "ssg-theme-astro/layouts/main.astro" # This line of code should remain unchanged.
tag: ""
title: "Chef Sha 火焱阁"
favicon: "favicon.ico"
logo: "logo.png"
primaryColor: "#AF0702" # logo color
secondaryColor: "#f3eee5"
primaryColorScheme: "dark" # dark | light
secondaryColorScheme: "light"
cuid: ""
ruid: ""
orderOnlineLink: "https://www.bestfoodtodayus.com/ordering/restaurant/menu?restaurant_uid=baf65e17-dae4-457b-9cc0-a3a33b502826"
tableReservationLink: "https://www.bestfoodtodayus.com/ordering/restaurant/menu/reservation?restaurant_uid=baf65e17-dae4-457b-9cc0-a3a33b502826&reservation=true&client_is_mobile=true"
tel: "510-566-7175"

# banner:
#   text:
#     # - boldText: "🥳 Special Offer"
#     - boldText: "20% off cash discount"
#     - text: " on xxx"
#     - smText: ""
#   # add more text...
#   textColor: "#ffffff"
#   bgColor: "#E7383D"
#   bgOpacity: "1" # 0~1

# header
header:
  logoSize: 60
  logoSizeOnMobile: 45
  textAfterLogo:
    text: "Chef Sha 火焱阁"
    size: 16
    color: "#AF0702"
  bgColor: "#ffffff"
  bgOpacity: "1" # 0~1
  menuTextColor: "#000000"
  menu:
    - { text: "主页", link: "/" }
    - { text: "菜品展示", link: "#gallery" }
    - { text: "关于我们", link: "#about-us" }
    - { text: "联系我们", link: "#contact-us" }
    - { text: "English", link: "/" }
  addOrderOnlineBtn: false
  orderOnlineBtnInsteadText: ""
  addTableReservationBtn: false
  tableReservationBtnInsteadText: ""
  addTelBtn: true
  telTextColor: "#000000"

  otherBtn1InsteadText: "Online Order"
  otherBtn1Href: "https://www.bestfoodtodayus.com/ordering/restaurant/menu?restaurant_uid=baf65e17-dae4-457b-9cc0-a3a33b502826"
  otherBtn2InsteadText: ""
  otherBtn2Href: ""

sections:
  # hero
  - type: "hero"
    id: ""
    height: "100" # Conditionally use only when sectionType is imgBg
    sectionType: "imgBg" # video | imgWithText | imgBg
    bgVideoType: "gjw" # youtube | vimeo | gjw
    bgVideoId: "1gov6sj92av4Zb9OI9K1kKJat1rv1c"
    bgImg: "gallery/Chef Sha 火焱阁10.jpeg"
    bgColor: "#000000"
    bgOpacity: "0.6" # 0~1
    title:
      - "Chef Sha"
      - "火焱阁"
    titleColor: "#ffffff"
    description:
      - "位于圣马刁的美味中国菜、火锅、干锅、川菜和特色菜"
    descriptionColor: "#ffffff"
    # title2:
    #   - ""
    # title2Color: "#ffffff"
    # description2:
    #   - ""
    # description2Color: "#ffffff"

    addOrderOnlineBtn: false
    orderOnlineBtnInsteadText: ""
    addTableReservationBtn: false
    tableReservationBtnInsteadText: ""

    btn1Text: "See Menu & OrderS"
    btn1Href: "https://www.bestfoodtodayus.com/ordering/restaurant/menu?restaurant_uid=baf65e17-dae4-457b-9cc0-a3a33b502826"
    btn2Text: "Table Reservation"
    btn2Href: "https://www.bestfoodtodayus.com/ordering/restaurant/menu/reservation?restaurant_uid=baf65e17-dae4-457b-9cc0-a3a33b502826&reservation=true&client_is_mobile=true"

    bannerImg: "sample.webp"
    imgPosition: "imgLeft" # imgLeft | imgRight
    bannerMarginTopMobile: 20
    imgRounded: "3xl" # sm | md | lg | xl | 2xl | 3xl | full

    bottomRounded: "3xl" # sm | md | lg | xl | 2xl | 3xl | full
    bottomInfo: "我们提供在线订餐服务"

  # # Video
  #   - type: "video"
  #     id: ""
  #     title:
  #       - "Lorem ipsum dolor sit amet"
  #     description:
  #       - "Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et"
  #     videoType: "gjw" # vimeo | gjw | youtube
  #     videoId:
  #       - "1gov6sj92av4Zb9OI9K1kKJat1rv1c"
  #       - "1gov6sj92av4Zb9OI9K1kKJat1rv1c"
  #     isOnlyDisplayOnMobile: false

  # Gallery
  - type: "gallery"
    id: "gallery"
    mode: 3 # 1 - 3
    bgImg: ""
    bgColor: ""
    bgOpacity: "" # 0~1
    title:
      - "Chef Sha"
      - "火焱阁的美食"
    titleColor: "#000000"
    description:
      - ""
    descriptionColor: "#333333"
    folderPath: "gallery"
    showImgName: false # true | false
    imgNameColor: "#000000"
    menuItemImgRounded: "3xl" # sm | md | lg | xl | 2xl | 3xl | full

  # textBlock - only title
  - type: "textBlock"
    id: "about-us"
    bgImg: ""
    bgColor: ""
    bgOpacity: "" # 0~1
    title:
      - "关于我们"
    titleColor: "#000000"
    description:
      - "位于圣马刁的 Chef Sha 火焱阁为您提供质量上乘的餐点，诚邀您品尝我们的美味佳肴。"
      - "Chef Sha 火焱阁于2019年9月在圣马特奥开业，开始供应亚洲和中国美食，主营四川和蒙古火锅、干锅和烧烤。欢迎来到这家典型的传统中式餐厅品尝火锅，将是与朋友和家人分享的美好时光。您也可以自己点一些特色菜。一些受欢迎的菜品包括炒鱼片、麻辣水煮鱼片、花椒水煮羊肉片、麻婆豆腐和其他一些菜品，也许您可以来本店亲自品尝一下。"
      - "Chef Sha 火焱阁的成功之道很简单：提供始终如一的优质食品，每一次都美味可口。Chef Sha 火焱阁引以为豪的是为顾客提供美味可口的正宗菜肴，如 火锅、干锅、海鲜、四川和地方特色菜以及其他中餐和亚洲美食。"

    descriptionColor: ""

  # # feature - imgWithText
  #   - type: "feature"
  #     noMarginTop: true
  #     id: ""
  #     height: "100" # Conditionally use only when sectionType is imgBg
  #     sectionType: "imgWithText" # video | imgWithText | imgBg
  #     title:
  #       - "Lorem ipsum dolor sit ame"
  #     titleColor: "#000000"
  #     description:
  #       - "Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua."
  #     descriptionColor: "#000000"

  #     addOrderOnlineBtn: false
  #     orderOnlineBtnInsteadText: ""
  #     addTableReservationBtn: false
  #     tableReservationBtnInsteadText: ""

  #     btn1Text: ""
  #     btn1Href: ""
  #     btn2Text: ""
  #     btn2Href: ""

  #     bannerImg: "sample.webp"
  #     imgPosition: "imgLeft" # imgLeft | imgRight
  #     bannerMarginTopMobile: 20
  #     imgRounded: "3xl" # sm | md | lg | xl | 2xl | 3xl | full

  # # feature - map
  #   - type: "feature"
  #     id: ""
  #     noMarginTop: false
  #     sectionType: "imgWithText" # video | imgWithText | imgBg
  #     title:
  #       - "Store 2 : Washington St"
  #     titleColor: "#000000"
  #     description:
  #       - "Opening Hours: "
  #       - "Mon-Fri 8:30 AM-8:00 PM, Sat-Sun 9:00 AM-8:30 PM"
  #     descriptionColor: "#000000"

  #     addOrderOnlineBtn: true
  #     orderOnlineBtnInsteadText: ""
  #     addTableReservationBtn: true
  #     tableReservationBtnInsteadText: ""
  #     showOtherBtn: true
  #     btn1Text: "Order online from Washington St Store"
  #     btn1Href: "#"
  #     btn2Text: ""
  #     btn2Href: ""

  #     map: true
  #     url: "https://maps.app.goo.gl/HDDb5yFih4S8TmDe7"
  #     iframeUrl: "https://www.google.com/maps/embed?pb=!1m14!1m8!1m3!1d197.0491990412703!2d-122.4063506!3d37.7950269!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x8085815e4be59617%3A0x87622e118f7e38a2!2sHon%E2%80%99s%20Wun-Tun%20House!5e0!3m2!1sen!2sjp!4v1722232541079!5m2!1sen!2sjp"
  #     addTelBtn: true
  #     tel: "12345678"
  #     telInsteadText: "Call: (123) 456-7890"
  #     tel2: "876543210" # if there are two phone numbers"
  #     tel2InsteadText: "Call: (876) 543-2100"
  #     getDirectionBtnInsteadText: ""
  #     imgPosition: "" # imgLeft | imgRight

  # # textBlock
  #   - type: "textBlock"
  #     id: "about-us"
  #     bgImg: ""
  #     bgColor: ""
  #     bgOpacity: "" # 0~1
  #     title:
  #       - "About Us"
  #     titleColor: "#000000"
  #     description:
  #       - "Lorem ipsum dolor sit amet, consectetur adipiscing elit."
  #       - "Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua."
  #     descriptionColor: "#000000"

  # textBlock - Information
  - type: "textBlock"
    noMarginTop: false
    id: ""
    bgImg: ""
    bgColor: "#000"
    bgOpacity: "1" # 0~1
    title:
      - "新功能! 在线订餐"
    titleColor: "#ffffff"
    description:
      - "现在支援线上订单自取。只要告诉我们您想要的菜餚，我们会​​尽快准备好。所有订单都由我们手动确认。您可以即时查看您的食物何时准备好。订单状态会即时更新，您可以在萤幕上查看您的食物何时可以取走。"
    descriptionColor: "#ffffff"

  # map
  - type: "map"
    noMarginTop: true
    id: "contact-us"
    mode: "fullWidth" # full-width | ...
    url: "https://maps.app.goo.gl/qsEBUa1xkqHpWJjt6"
    iframeUrl: "https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3162.5574902108265!2d-122.3258600241263!3d37.56548817203875!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x808f9f1012849009%3A0x653e48e8ffbaa252!2sChef%20Sha!5e0!3m2!1szh-CN!2sjp!4v1723105762464!5m2!1szh-CN!2sjp"
    addTelBtn: true
    tel: ""
    telInsteadText: "电话：510-566-7175"
    tel2: "" # if there are two phone numbers
    tel2InsteadText: ""
    getDirectionBtnInsteadText: "前往餐厅"

#  # The modal will only appear once within 30 minutes."
#   - type: "modal"
#     bgColor: "#333"
#     bgOpacity: "0.1" # 0~1
#     title:
#       - "🎁 Special Offers"
#     titleColor: "#FF2D2F"
#     titleSize: 24
#     description:
#       - "20% off cash discount on frozen handmade dumplings. 10% off cash discount on family meal takeout. Free rice with lunch. Delivery available."
#     descriptionColor: ""
#     descriptionSize: 16
#     imgName: "special_offer.webp"
#     imgAlt: "20% off cash discount on frozen handmade dumplings. 10% off cash discount on family meal takeout. Free rice with lunch. Delivery available."
#     imgHref: ""
#     buttonText: ""

footer:
  mode: 1 # 1
  noMarginTop: true
  bgImg: ""
  bgColor: "#f3f4f6"
  bgOpacity: "1" # 0~1
  textColor: "#000000" # default white

  openingHoursInsteadText: "营业时间"
  openingHours:
    - "周一 ～ 周日"
    - "11:00 AM - 2:30 PM, 5:00 PM - 10:00 PM"

  isLogo: true
  logoSize: 65
  logoSizeOnMobile: 50

  # menu:
  #   - { text: "Home", link: "/" }
  #   - { text: "Gallery", link: "#gallery" }
  #   - { text: "About Us", link: "/#about-us" }
  #   - { text: "Contact Us", link: "/#contact-us" }
  #   - { text: "中文", link: "/zh-cn" }

  FB: false
  FBLink: ""
  IG: false
  IGLink: ""
  X: false
  XLink: ""
  youtube: false
  youtubeLink: ""
  yelp: false
  yelpLink: ""
  doorDash: false
  doorDashLink: ""
  uberEats: false
  uberEatsLink: ""

  acceptedPaymentMethodsInsteadText: "支付方式"
  paymentMethod: "visa,amex,cash,mastercard" # alipay,applePay,cash,discover,googlePay,jcb,maestro,mastercard,stripe,unionPay,visa,weChatPay,payPal

  addressInsteadText: "地 址"
  address:
    - address: "231 S Ellsworth Ave, San Mateo, CA 94401"
      url: "https://maps.app.goo.gl/qsEBUa1xkqHpWJjt6"

  # at a minimum, please make sure to include the meta description.
seo:
  metaTitle: "Chef Sha 火焱阁｜中餐厅｜中式火锅｜圣马刁"
  metaDescription: "在圣马刁的Chef Sha 火焱阁体验最好的中式火锅！在温馨的氛围中，与家人和朋友一起品尝新鲜的食材和丰富的味道。立即在线订餐！"
  keywords: ""
  img: ""
  canonicalHref: "https://chefsha-order.com/zh-cn"
  locale: "zh_CN" # zh_TW | zh_CN
---

<!-- hello world -->

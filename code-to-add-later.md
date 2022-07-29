add to the data/homepage.yml file to put a "testimonial caracole" to the homepage

########################## Testimonial ########################
testimonial:
  enable : true
  title : "What People Are Saying <br> About Our Product"
  testimonialItem:
    # testimonial item loop
    - name : "Angelo Perara"
      image : "images/clients/client-1.jpg" # size 100px*100px
      designation : "CEO, Dialogue Broad Band"
      content : "Lorem ipsum dolor sit amet, <br> consetetur sadipscing elitr, diam <br> nonumy eirmod tempor"
      rating : "five" # rating star, one to five
      
    # testimonial item loop
    - name : "Riya Ventila"
      image : "images/clients/client-2.jpg" # size 100px*100px
      designation : "CEO, Dialogue Broad Band"
      content : "Lorem ipsum dolor sit amet, <br> consetetur sadipscing elitr, diam <br> nonumy eirmod tempor"
      rating : "three" # rating star, one to five
      
    # testimonial item loop
    - name : "john Doe"
      image : "images/clients/client-3.jpg" # size 100px*100px
      designation : "CEO, Dialogue Broad Band"
      content : "Lorem ipsum dolor sit amet, <br> consetetur sadipscing elitr, diam <br> nonumy eirmod tempor"
      rating : "five" # rating star, one to five
      
    # testimonial item loop
    - name : "Riya Ventila"
      image : "images/clients/client-2.jpg" # size 100px*100px
      designation : "CEO, Dialogue Broad Band"
      content : "Lorem ipsum dolor sit amet, <br> consetetur sadipscing elitr, diam <br> nonumy eirmod tempor"
      rating : "four" # rating star, one to five

********************************************************************

add to the data/homepage.yml file to put a "Product List" to the homepage

######################## Products #############################
products:
  enable : true
  title : "Products List"
  # product item comes from "content/products"

*********************************************************************

add to the data/homepage.yml file to put a "Promo" spot on the homepage

######################## Promo Video ##########################
video:
  enable : true
  title : "How To Use This Product?"
  content : "Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et
          dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et."
  videoThumb : "images/video-thumb.jpg"
  videoURL : "https://www.youtube.com/embed/wf4F2-9UXUo"

**********************************************************************

add to the data/homepage.yml file to add a listed description of a product

########################### Advantage #########################
advantage:
  enable : true
  title : "Advantages Of Using <br> Our Product"
  subtitle : "Lorem ipsum dolor sit amet, da decal consetetur<br> sadipscing elitr, sed diam nonumya eirmod"
  image : "images/advantage.png"
  advantageList:
    # advantage list loop
    - listItem : "Extremely lightweight"
    - listItem : "Excellent breathability"
    - listItem : "Can increase Cell activation"
    - listItem : "Glowing Skin In 7 Days"
    - listItem : "Increasing Glow Of Face"
    - listItem : "More Beautiful Face Skin"

*************************************************************************

add to data/homepage.yml for a side-by-side view of data

######################## raw material #######################
material:
  enable : true
  title : "Ingredients Of Our Products"
  subtitle : "Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et
          dol."
  materialItem:
    # material item loop
    - title : "Matcha Seeds"
      image : "images/material/material-1.png"
      content : "Lorem ipsum dolor sit amet,be consetetur sadipscing elitr, sed diam nonumy eirmod tem"
      
    # material item loop
    - title : "Aloe Vera"
      image : "images/material/material-2.png"
      content : "Lorem ipsum dolor sit amet,be consetetur sadipscing elitr, sed diam nonumy eirmod tem"
      
    # material item loop
    - title : "Turmeric"
      image : "images/material/material-3.png"
      content : "Lorem ipsum dolor sit amet,be consetetur sadipscing elitr, sed diam nonumy eirmod tem"
      
    # material item loop
    - title : "Tulshi leaf"
      image : "images/material/material-4.png"
      content : "Lorem ipsum dolor sit amet,be consetetur sadipscing elitr, sed diam nonumy eirmod tem"

***************************************************************************

add to data/homepage.yml to add two extra call to action. cta info in themes/layouts/partials/cta.html

###################### Call to action ########################
cta:
  enable : true
  title : "Buy one Get One Free Taba Cream"
  content : "Available for limited time only. Grab one while you still can!"
  image : "images/cta.png"
  overlayImage : "images/cta-overlay.png"
  button:
    label : "All Products"
    link : "products/"

****************************************************************************

add button data/homepage.yml 

  # button
  button:
    enable : true
    label : "All Products"
    link : "products/"
  # demo video
  video:
    enable : true
    videoURL : "https://www.youtube.com/embed/wf4F2-9UXUo"

***************************************************************************

# Snipcart Credentials
snipcartApiKey = "M2E5YjA3NjMtYzRiYS00YzVjLWEyYWYtNDY5ZDI0OWZhYjg5"
currencySymbol = "$"

***************************************************************************

extra foot menu items, add to config.toml

  [[menu.footer]]
  name = "Products"
  URL = "products/"
  weight = 10

  [[menu.footer]]
  name = "Blog"
  URL = "blog/"
  weight = 20

  [[menu.footer]]
  name = "FAQ"
  URL = "faq/"
  weight = 30

*****************************************************************************

add nav bar to site, add to config.toml after the front matter

############################## navigation ###############################
[menu]

  [[menu.main]]
  name = "Products"
  URL = "products/"
  weight = 1

  [[menu.main]]
  name = "Blog"
  URL = "blog/"
  weight = 2

  [[menu.main]]
  name = "FAQ"
  URL = "faq/"
  weight = 3

  [[menu.main]]
  name = "Contact"
  URL = "contact/"
  weight = 4

**********************************************************

add socials to footer, add to config.toml

  # Social Site
  [[params.social]]
  icon = "ti-facebook"
  link = "#"

  [[params.social]]
  icon = "ti-twitter-alt"
  link = "#"

  [[params.social]]
  icon = "ti-youtube"
  link = "#"

  [[params.social]]
  icon = "ti-instagram"
  link = "#"

  [[params.social]]
  icon = "ti-pinterest"
  link = "#"

************************************************************

  # Contact Form
  [params.contact]
  formAction = "#" # contact form works with formspree.io

**************************************************************

# Preloader
  [params.preloader]
  enable = true
  preloader = "" # use .png , .svg or .gif format

  # Product Rating
  # it works with https://rating-widget.com/ , you will get the ID and publicKey after creating your account there.
  [params.rating]
  enable = true
  websiteID = "444334"
  publicKey = "811cf0927332bf51f2e12f84608594ac"
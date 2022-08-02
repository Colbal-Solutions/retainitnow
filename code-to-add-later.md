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

############################ banner ##########################
banner:
  enable : true
  title : "Best Beauty Cream For Your Skin"
  content : "Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et
          dolore magna aliquyam erat, sed dia"
  image : "images/banner.png"


########################## About ##############################
about:
  enable : false
  title : "About Our Product"
  content : "Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et
          dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores et ea rebum. Stet
          clita kasd gubergren,"
  image : "images/about.png"  


**********************************************************
from themes/hargo-hugo/layouts/index.html, code below makes the code above work

<!-- banner -->
{{ if site.Data.homepage.banner.enable }}
{{ with site.Data.homepage.banner }}
<section class="section-sm">
  <div class="container">
    <div class="row justify-content-between align-items-center">
      <div class="col-lg-5 col-md-6 order-2 order-md-1">
        <h1>{{ .title | markdownify }}</h1>
        <p>{{ .content | markdownify }}</p>
        {{ if .button.enable }}
        {{ with .button }}
        <a href="{{ .link }}" class="btn btn-primary mr-3">{{ .label }}</a>
        {{ end }}
        {{ end }}

        {{ if .video.enable }}
        {{ with .video }}
        <a data-toggle="modal" data-src="{{ .videoURL | safeURL }}" data-target="#videoModal"
          class="text-color video-modal"><i
            class="ti-control-play bg-gradient hover-shadow btn-play mr-2"></i><span>Watch Video</span></a>
        {{ end }}
        <!-- Modal -->
        <div class="modal fade" id="videoModal" tabindex="-1" role="dialog" aria-hidden="true">
          <div class="modal-dialog modal-dialog-centered" role="document">
            <div class="modal-content border-0 rounded-0">
              <iframe width="560" height="315" src="" id="video" frameborder="0"
                allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture"
                allowfullscreen></iframe>
            </div>
          </div>
        </div>
        {{ end }}
      </div>
      <div class="col-lg-7 col-md-6 order-1 order-lg-2">
        <img src="{{ .image | absURL }}" class="img-fluid" alt="">
      </div>
    </div>
  </div>
</section>
{{ end }}
{{ end }}
<!-- /banner -->

<!-- about -->
{{ if site.Data.homepage.about.enable }}
{{ with site.Data.homepage.about }}
<section class="section">
  <div class="container">
    <div class="row justify-content-around align-items-center">
      <div class="col-lg-5 col-md-6">
        <img class="img-fluid" src="{{ .image | absURL }}" alt="">
      </div>
      <div class="col-md-6 col-lg-5">
        <h2>{{ .title | markdownify }}</h2>
        <p>{{ .content | markdownify }}</p>
      </div>
    </div>
  </div>
</section>
{{ end }}
{{ end }}
<!-- /about -->

{{ if site.Data.homepage.cta.enable }}
{{ partial "cta.html" . }}
{{ end }}

<!-- material -->
{{ if site.Data.homepage.material.enable }}
{{ with site.Data.homepage.material }}
<section class="section pb-0">
  <div class="container">
    <div class="row">
      <div class="col-lg-6 mx-auto text-center">
        <h2>{{ .title | markdownify }}</h2>
        <p>{{ .subtitle | markdownify }}</p>
      </div>
    </div>
    <div class="row">
      {{ range .materialItem }}
      <div class="col-lg-3 col-md-4 col-sm-6">
        <div class="card border-0 text-center">
          <img src="{{ .image | absURL }}" alt="material" class="card-img-top border-0">
          <div class="card-body">
            <h4>{{ .title | markdownify }}</h4>
            <p>{{ .content | markdownify }}</p>
          </div>
        </div>
      </div>
      {{ end }}
    </div>
  </div>
</section>
{{ end }}
{{ end }}
<!-- /material -->

<!-- advantage -->
{{ if site.Data.homepage.advantage.enable }}
{{ with site.Data.homepage.advantage }}
<section class="section pb-0">
  <div class="container">
    <div class="row align-items-center">
      <div class="col-md-6">
        <h2>{{ .title | markdownify }}</h2>
        <p class="mb-4">{{ .subtitle | markdownify }}</p>
        <ul class="list-unstyled" style="columns: 2;">
          {{ range .advantageList }}
          <li class="mb-3"><i class="ti-arrow-circle-right text-primary mr-2"></i>{{ .listItem }}</li>
          {{ end }}
        </ul>
      </div>
      <div class="col-md-6">
        <img src="{{ .image | absURL}}" class="img-fluid" alt="">
      </div>
    </div>
  </div>
</section>
{{ end }}
{{ end }}
<!-- /advantage -->

<!-- promo video -->
{{ if site.Data.homepage.video.enable }}
{{ with site.Data.homepage.video }}
<section class="section pb-0">
  <div class="container">
    <div class="row align-items-center justify-content-between">
      <div class="col-lg-5 col-md-6">
        <div class="img-border rounded mb-5 mb-md-0">
          <img src="{{ .videoThumb | absURL }}" alt="video thumb" class="img-fluid rounded">
          <a data-toggle="modal" data-src="{{ .videoURL | safeURL }}" data-target="#videoModal2"
            class="text-color video-modal content-center"><i class="ti-control-play bg-gradient btn-play-lg"></i></a>
          <!-- Modal -->
          <div class="modal fade" id="videoModal2" tabindex="-1" role="dialog" aria-hidden="true">
            <div class="modal-dialog modal-dialog-centered" role="document">
              <div class="modal-content border-0 rounded-0">
                <iframe width="560" height="315" src="" id="video2" frameborder="0"
                  allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture"
                  allowfullscreen></iframe>
              </div>
            </div>
          </div>
        </div>
      </div>
      <div class="col-md-6">
        <h2>{{ .title | markdownify }}</h2>
        <p>{{ .content | markdownify }}</p>
      </div>
    </div>
  </div>
</section>
{{ end }}
{{ end }}
<!-- /promo video -->

<!-- testimonial -->
{{ if site.Data.homepage.testimonial.enable }}
{{ with site.Data.homepage.testimonial }}
<section class="section">
  <div class="container">
    <div class="row">
      <div class="col-12 text-center">
        <h2>{{ .title | markdownify }}</h2>
      </div>
    </div>
    <div class="row testimonial-slider">
      {{ range .testimonialItem }}
      <div class="col-4">
        <div class="card border-primary text-center">
          <div class="card-body">
            <img src="{{ .image | absURL }}" class="client-img" alt="{{ .name | markdownify }}">
            <p class="quoted">{{ .content | markdownify }}</p>
            <h6 class="font-weight-medium">{{ .name | markdownify }}</h6>
            <small>{{ .designation | markdownify }}</small>
            <ul class="list-inline rating {{ .rating | lower }} mt-3">
              <li class="list-inline-item mx-0"><i class="ti-star"></i></li>
              <li class="list-inline-item mx-0"><i class="ti-star"></i></li>
              <li class="list-inline-item mx-0"><i class="ti-star"></i></li>
              <li class="list-inline-item mx-0"><i class="ti-star"></i></li>
              <li class="list-inline-item mx-0"><i class="ti-star"></i></li>
            </ul>
          </div>
        </div>
      </div>
      {{ end }}
    </div>
  </div>
</section>
{{ end }}
{{ end }}
<!-- /testimonial -->
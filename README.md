Backdrop options for a responsive popup with Bootstrap 5. Prevent close on click outside with static backdrop, remove backdrop, enable interactivity & more.

Check out [Bootstrap Modal Backdrop Documentation](https://mdbootstrap.com/docs/standard/extended/modal-backdrop/) for detailed instructions & even more examples.


## Basic example

Default modal backdrop is a delicate shadow overlaying the rest of the page design.

```html
<!-- Button trigger modal -->
<button type="button" class="btn btn-primary" data-mdb-toggle="modal" data-mdb-target="#exampleModal">
  Launch demo modal
</button>

<!-- Modal -->
<div class="modal top fade" id="exampleModal" tabindex="-1" aria-labelledby="exampleModalLabel"
  aria-hidden="true" data-mdb-backdrop="true" data-mdb-keyboard="true">
  <div class="modal-dialog  ">
    <div class="modal-content">
      <div class="modal-header">
        <h5 class="modal-title" id="exampleModalLabel">Modal title</h5>
        <button type="button" class="btn-close" data-mdb-dismiss="modal" aria-label="Close"></button>
      </div>
      <div class="modal-body">...</div>
      <div class="modal-footer">
        <button type="button" class="btn btn-secondary" data-mdb-dismiss="modal">
          Close
        </button>
        <button type="button" class="btn btn-primary">Save changes</button>
      </div>
    </div>
  </div>
</div>
```

## Static Backdrop

If you would like to prevent the modal from closing on a click outside of the modal boundries, you can set the `data-mdb-backdrop` attribute to `static`.

```html
<!-- Button trigger modal -->
<button type="button" class="btn btn-primary" data-mdb-toggle="modal" data-mdb-target="#exampleModal2">
  Launch demo modal
</button>

<!-- Modal -->
<div class="modal top fade" id="exampleModal2" tabindex="-1" aria-labelledby="exampleModal2Label"
  aria-hidden="true" data-mdb-backdrop="static" data-mdb-keyboard="true">
  <div class="modal-dialog  ">
    <div class="modal-content">
      <div class="modal-header">
        <h5 class="modal-title" id="exampleModal2Label">Modal title</h5>
        <button type="button" class="btn-close" data-mdb-dismiss="modal" aria-label="Close"></button>
      </div>
      <div class="modal-body">...</div>
      <div class="modal-footer">
        <button type="button" class="btn btn-secondary" data-mdb-dismiss="modal">
          Close
        </button>
        <button type="button" class="btn btn-primary">Save changes</button>
      </div>
    </div>
  </div>
</div>
```

## No Backdrop

If you would like to get rid of the backdrop, you can set the `data-mdb-backdrop` attribute to `false`.

```html
<!-- Button trigger modal -->
<button type="button" class="btn btn-primary" data-mdb-toggle="modal" data-mdb-target="#exampleModal3">
  Launch demo modal
</button>

<!-- Modal -->
<div class="modal top fade" id="exampleModal3" tabindex="-1" aria-labelledby="exampleModal3Label"
  aria-hidden="true" data-mdb-backdrop="false" data-mdb-keyboard="true">
  <div class="modal-dialog  ">
    <div class="modal-content">
      <div class="modal-header">
        <h5 class="modal-title" id="exampleModal3Label">Modal title</h5>
        <button type="button" class="btn-close" data-mdb-dismiss="modal" aria-label="Close"></button>
      </div>
      <div class="modal-body">...</div>
      <div class="modal-footer">
        <button type="button" class="btn btn-secondary" data-mdb-dismiss="modal">
          Close
        </button>
        <button type="button" class="btn btn-primary">Save changes</button>
      </div>
    </div>
  </div>
</div>

```


## How to use?

1. Download MDB 5 - free UI KIT

2. Choose your favourite customized component and click on the image

3. Copy & paste the code into your MDB project

[▶️ Subscribe to YouTube channel for web development tutorials & resources](https://www.youtube.com/MDBootstrap?sub_confirmation=1)



___

## More extended Bootstrap documentation

<ul>
<li><a href="https://mdbootstrap.com/docs/standard/extended/bootstrap-address-form/">Bootstrap Address Form</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/avatar/">Bootstrap Avatar</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/back-to-top/">Bootstrap Back To Top Button</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/carousel-with-thumbnails/">Bootstrap Carousel Slider with Thumbnails</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/chat/">Bootstrap Chat</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/code/">Bootstrap Code Blocks</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/comments/">Bootstrap Comments</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/bootstrap-comparison-table/">Bootstrap Comparison Table</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/credit-card/">Bootstrap Credit Card Form</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/drawer/">Bootstrap Drawer</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/dropdown-multilevel/">Bootstrap Nested Dropdown</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/faq/">Bootstrap FAQ component / section</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/gallery/">Bootstrap Gallery</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/hamburger-menu/">Bootstrap Hamburger Menu</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/bootstrap-invoice/">Bootstrap Invoice</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/jumbotron/">Bootstrap Jumbotron</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/login/">Bootstrap Login Form</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/maps/">Bootstrap Maps</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/media-object/">Bootstrap Media Object</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/mega-menu/">Bootstrap Mega Menu</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/multiselect/">Bootstrap Multiselect</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/news-feed/">Bootstrap News Feed</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/offcanvas/">Bootstrap Offcanvas</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/order-details/">Bootstrap Order Details</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/page-transitions/">Bootstrap Page Transitions</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/payment-forms/">Bootstrap Payment Forms</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/product-cards/">Bootstrap Product Cards</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/profiles/">Bootstrap Profiles</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/quotes/">Bootstrap Quotes</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/registration/">Bootstrap Registration Form</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/search-expanding/">Bootstrap Expanding Search Bar</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/shopping-carts/">Bootstrap Shopping Carts</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/side-navbar/">Bootstrap Side Navbar</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/sidebar/">Bootstrap Sidebar</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/social-media/">Bootstrap Social Media Icons & Buttons</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/square-buttons/">Bootstrap Square Buttons</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/bootstrap-survey-form/">Bootstrap Survey Form</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/testimonial-slider/">Bootstrap Testimonial Slider</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/testimonials/">Bootstrap Testimonials</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/textarea/">Bootstrap Textarea</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/timeline/">Bootstrap Timeline</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/to-do-list/">Bootstrap To Do List</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/video-carousel/">Bootstrap Video Carousel / Gallery</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/weather/">Bootstrap Weather</a></li>
  <li><a href="https://mdbootstrap.com/docs/standard/extended/dark-mode/">Bootstrap Dark Mode</a></li>
  <li><a href="https://mdbootstrap.com/docs/standard/extended/padding/">Bootstrap Padding</a></li>
  <li><a href="https://mdbootstrap.com/docs/standard/extended/modal-methods/">Bootstrap Modal Methods</a></li>
  <li><a href="https://mdbootstrap.com/docs/standard/extended/modal-size/">Bootstrap Modal Size</a></li>
  <li><a href="https://mdbootstrap.com/docs/standard/extended/card-deck/">Bootstrap Card Deck</a></li>
  <li><a href="https://mdbootstrap.com/docs/standard/extended/table-filter/">Bootstrap Table Filter</a></li>
  <li><a href="https://mdbootstrap.com/docs/standard/extended/slider/">Bootstrap Slider</a></li>
  <li><a href="https://mdbootstrap.com/docs/standard/extended/logo/">Bootstrap Logo</a></li>
  <li><a href="https://mdbootstrap.com/docs/standard/extended/popup/">Bootstrap Popup</a></li>
  <li><a href="https://mdbootstrap.com/docs/standard/extended/max-width/">Bootstrap Max Width</a></li>
  <li><a href="https://mdbootstrap.com/docs/standard/extended/hero/">Bootstrap Hero</a></li>
  <li><a href="https://mdbootstrap.com/docs/standard/extended/select-dropdown/">Bootstrap Select Dropdown</a></li>
  <li><a href="https://mdbootstrap.com/docs/standard/extended/labels/">Bootstrap Labels</a></li>
  <li><a href="https://mdbootstrap.com/docs/standard/extended/dialog/">Bootstrap Dialog</a></li>
  <li><a href="https://mdbootstrap.com/docs/standard/extended/screen-sizes/">Bootstrap Screen Sizes</a></li>
  <li><a href="https://mdbootstrap.com/docs/standard/extended/dropdown-button/">Bootstrap Dropdown Button</a></li>
  <li><a href="https://mdbootstrap.com/docs/standard/extended/widgets/">Bootstrap Widgets</a></li>
</ul>
+++
title = ""
date = 2019-12-04T16:10:50+01:00
draft = true
+++

# Components

## Alerts

{{< alert >}}Hello from Hugo Bootstrap!{{< /alert >}}

{{< alert closable=true level="success" >}}I can be closed{{< /alert >}}

## Badges

{{< badge level="success" >}}Badge{{< /badge >}}

{{< badge pill=true >}}Pill{{< /badge >}}

{{< badge href="#" >}}Link{{< /badge >}}

## Breadcrumbs

{{< breadcrumb >}}
    {{< breadcrumb_item text="Home" href="/" >}}
    {{< breadcrumb_item text="Library" href="/library/" >}}
    {{< breadcrumb_item text="Data" active=true >}}
{{< /breadcrumb >}}

## Buttons

### Inline Buttons

{{< button text="Primary">}}

{{< button text="Success" level="success" >}}

{{< button text="Outline" level="secondary" outline=true >}}

{{< button text="Small" size="sm" >}}

{{< button text="Large" size="lg" >}}

### Block Buttons

{{< button text="Block level button" block=true >}}

### Radio Buttons

{{< radio_button >}}
    {{< radio_button_item text="Foo" >}}
    {{< radio_button_item text="Bar" >}}
    {{< radio_button_item text="Buzz" active=true >}}
{{< /radio_button >}}

## Cards

### Image Card

{{< card image="/img/bootstrap.png" caption="My image card" classes="custom-card" />}}

### Text Card

{{< card classes="custom-card" >}}Hello world from my text card{{< /card >}}

### Hybrid Card

{{< card image="/img/hugo.png" caption="My hybrid card" classes="custom-card" >}}
    <h5 class="card-title">Card title</h5>
    <h6 class="card-subtitle mb-2 text-muted">Card subtitle</h6>
    <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
    <a href="#" class="card-link">Card link</a>
{{< /card >}}

## Carousel

{{< carousel id="carousel1" classes="custom-carousel" active="/img/bootstrap.png" images="/img/bootstrap.png|/img/hugo.png" >}}

### Controls

{{< carousel id="carousel2" classes="custom-carousel" active="/img/bootstrap.png" images="/img/bootstrap.png|/img/hugo.png" controls=true >}}

### Indicators

{{< carousel id="carousel3" classes="custom-carousel" active="/img/bootstrap.png" images="/img/bootstrap.png|/img/hugo.png" indicators=true >}}

## Collapse

{{< collapse id="collapse1" classes="custom-collapse" text="Toggle Section" level="success" outline=true >}}
Anim pariatur cliche reprehenderit, enim eiusmod high life accusamus terry richardson ad squid. 3 wolf moon officia aute, non cupidatat skateboard dolor brunch. Food truck quinoa nesciunt laborum eiusmod. Brunch 3 wolf moon tempor, sunt aliqua put a bird on it squid single-origin coffee nulla assumenda shoreditch et. Nihil anim keffiyeh helvetica, craft beer labore wes anderson cred nesciunt sapiente ea proident. Ad vegan excepteur butcher vice lomo. Leggings occaecat craft beer farm-to-table, raw denim aesthetic synth nesciunt you probably haven't heard of them accusamus labore sustainable VHS.
{{< /collapse >}}

## Accordion

{{< accordion id="accordion1" classes="custom-accordion" >}}
    {{< accordion_group parent="accordion1" id="accordion_group1" title="Collapsible Group Item #1" expanded=true >}}
        Anim pariatur cliche reprehenderit, enim eiusmod high life accusamus terry richardson ad squid. 3 wolf moon officia aute, non cupidatat skateboard dolor brunch. Food truck quinoa nesciunt laborum eiusmod. Brunch 3 wolf moon tempor, sunt aliqua put a bird on it squid single-origin coffee nulla assumenda shoreditch et. Nihil anim keffiyeh helvetica, craft beer labore wes anderson cred nesciunt sapiente ea proident. Ad vegan excepteur butcher vice lomo. Leggings occaecat craft beer farm-to-table, raw denim aesthetic synth nesciunt you probably haven't heard of them accusamus labore sustainable VHS.
    {{< /accordion_group >}}
    {{< accordion_group parent="accordion1" id="accordion_group2" title="Collapsible Group Item #2" >}}
        Anim pariatur cliche reprehenderit, enim eiusmod high life accusamus terry richardson ad squid. 3 wolf moon officia aute, non cupidatat skateboard dolor brunch. Food truck quinoa nesciunt laborum eiusmod. Brunch 3 wolf moon tempor, sunt aliqua put a bird on it squid single-origin coffee nulla assumenda shoreditch et. Nihil anim keffiyeh helvetica, craft beer labore wes anderson cred nesciunt sapiente ea proident. Ad vegan excepteur butcher vice lomo. Leggings occaecat craft beer farm-to-table, raw denim aesthetic synth nesciunt you probably haven't heard of them accusamus labore sustainable VHS.
    {{< /accordion_group >}}
    {{< accordion_group parent="accordion1" id="accordion_group3" title="Collapsible Group Item #3" >}}
        Anim pariatur cliche reprehenderit, enim eiusmod high life accusamus terry richardson ad squid. 3 wolf moon officia aute, non cupidatat skateboard dolor brunch. Food truck quinoa nesciunt laborum eiusmod. Brunch 3 wolf moon tempor, sunt aliqua put a bird on it squid single-origin coffee nulla assumenda shoreditch et. Nihil anim keffiyeh helvetica, craft beer labore wes anderson cred nesciunt sapiente ea proident. Ad vegan excepteur butcher vice lomo. Leggings occaecat craft beer farm-to-table, raw denim aesthetic synth nesciunt you probably haven't heard of them accusamus labore sustainable VHS.
    {{< /accordion_group >}}
{{< /accordion >}}

## Dropdown

{{< dropdown id="dropdown1" text="Dropdown button" >}}
    {{< dropdown_item text="Action" href="#" >}}
    {{< dropdown_item text="Another action" href="#" >}}
    {{< dropdown_item text="Something else here" href="#" >}}
{{< /dropdown >}}

## Jumbotron

{{< jumbotron classes="custom-jumbotron" >}}
  <h1 class="display-4">Hello, world!</h1>
  <p class="lead">This is a simple hero unit, a simple jumbotron-style component for calling extra attention to featured content or information.</p>
  <hr class="my-4">
  <p>It uses utility classes for typography and spacing to space content out within the larger container.</p>
  <a class="btn btn-primary btn-lg" href="#" role="button">Learn more</a>
{{< /jumbotron >}}

### Fluid Jumbotron

{{< jumbotron classes="custom-jumbotron" fluid=true >}}
  <div class="container">
    <h1 class="display-4">Fluid jumbotron</h1>
    <p class="lead">This is a modified jumbotron that occupies the entire horizontal space of its parent.</p>
  </div>
{{< /jumbotron >}}

## List Group

{{< list classes="custom-list" >}}
    {{< list_item >}}Cras justo odio{{< /list_item >}}
    {{< list_item active=true >}}Dapibus ac facilisis in{{< /list_item >}}
    {{< list_item >}}Morbi leo risus{{< /list_item >}}
    {{< list_item >}}Porta ac consectetur ac{{< /list_item >}}
    {{< list_item >}}Vestibulum at eros{{< /list_item >}}
{{< /list >}}

### With Links

{{< list classes="custom-list" >}}
    {{< list_item href="#" active=true >}}Cras justo odio{{< /list_item >}}
    {{< list_item href="#" >}}Dapibus ac facilisis in{{< /list_item >}}
    {{< list_item href="#" >}}Morbi leo risus{{< /list_item >}}
    {{< list_item href="#" >}}Porta ac consectetur ac{{< /list_item >}}
    {{< list_item href="#" >}}Vestibulum at eros{{< /list_item >}}
{{< /list >}}

### Horizontal

{{< list classes="custom-list" horizontal=true >}}
    {{< list_item href="#" active=true >}}Cras justo{{< /list_item >}}
    {{< list_item href="#" >}}Dapibus ac{{< /list_item >}}
    {{< list_item href="#" >}}Morbi leo{{< /list_item >}}
{{< /list >}}

## Media

{{< media image="/img/64px.png" caption="My media element" classes="custom-media" >}}
    <h5 class="mt-0">Media heading</h5>
    Cras sit amet nibh libero, in gravida nulla. Nulla vel metus scelerisque ante sollicitudin. Cras purus odio, vestibulum in vulputate at, tempus viverra turpis. Fusce condimentum nunc ac nisi vulputate fringilla. Donec lacinia congue felis in faucibus.
{{< /media >}}

### Center Aligned

{{< media image="/img/64px.png" caption="My media element" classes="custom-media" align="center" >}}
    <h5 class="mt-0">Center-aligned media</h5>
    <p>Cras sit amet nibh libero, in gravida nulla. Nulla vel metus scelerisque ante sollicitudin. Cras purus odio, vestibulum in vulputate at, tempus viverra turpis. Fusce condimentum nunc ac nisi vulputate fringilla. Donec lacinia congue felis in faucibus.</p>
    <p class="mb-0">Donec sed odio dui. Nullam quis risus eget urna mollis ornare vel eu leo. Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus.</p>
{{< /media >}}

## Navigation

{{< nav >}}
    {{< nav_item href="#" text="Active" active=true >}}
    {{< nav_item href="#" text="Link" >}}
    {{< nav_item href="#" text="Link" >}}
    {{< nav_item href="#" text="Disabled" disabled=true >}}
{{< /nav >}}

### With Pills

{{< nav pills=true classes="nav-fill custom-nav" >}}
    {{< nav_item href="#" text="Active" active=true >}}
    {{< nav_item href="#" text="Link" >}}
    {{< nav_item href="#" text="Link" >}}
    {{< nav_item href="#" text="Disabled" disabled=true >}}
{{< /nav >}}

## Pagination

{{< pagination >}}
    {{< pagination_item href="#" disabled=true >}}Previous{{< /pagination_item >}}
    {{< pagination_item href="#" >}}1{{< /pagination_item >}}
    {{< pagination_item href="#" active=true >}}2{{< /pagination_item >}}
    {{< pagination_item href="#" >}}3{{< /pagination_item >}}
    {{< pagination_item href="#" >}}Next{{< /pagination_item >}}
{{< /pagination >}}

### With Icons

{{< pagination >}}
    {{< pagination_item href="#" disabled=true >}}<span aria-hidden="true">&laquo;</span>{{< /pagination_item >}}
    {{< pagination_item href="#" >}}1{{< /pagination_item >}}
    {{< pagination_item href="#" active=true >}}2{{< /pagination_item >}}
    {{< pagination_item href="#" >}}3{{< /pagination_item >}}
    {{< pagination_item href="#" >}}<span aria-hidden="true">&raquo;</span>{{< /pagination_item >}}
{{< /pagination >}}

## Progress Bars

{{< progress cur="25" text="25%" classes="custom-progress" >}}

## Spinners

{{< spinner >}}

### Growing Spinner

{{< spinner style="spinner-grow" level="success" >}}

# Utilities

## Close Icon

{{< close_icon classes="custom-close-icon mx-2">}}

## Responsive Embed

{{< embed aspect="16by9" classes="custom-embed" >}}
    <iframe class="embed-responsive-item" src="https://www.youtube.com/embed/dQw4w9WgXcQ" allowfullscreen></iframe>
{{< /embed >}}

# Layout

## Grid

{{< grid classes="custom-grid bg-light text-primary">}}
    {{< row >}}
        {{< col >}}Foo{{< /col >}}
        {{< col >}}Bar{{< /col >}}
        {{< col >}}Buzz{{< /col >}}
    {{< /row >}}
    {{< row >}}
        {{< col width="3" >}}Narrow{{< /col >}}
        {{< col width="9" >}}Wide{{< /col >}}
    {{< /row >}}
{{< /grid >}}
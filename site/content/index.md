+++
title = ""
date = 2019-12-04T16:10:50+01:00
draft = true
+++

## Alerts

{{< alert >}}Hello from Hugo Bootstrap!{{< /alert >}}

{{< alert closable=true level="success" >}}I can be closed{{< /alert >}}

## Badges

{{< badge level="success" >}}Badge{{< /badge >}}

{{< badge pill=true >}}Pill{{< /badge >}}

{{< badge href="#" >}}Link{{< /badge >}}

## Breadcrumbs

*TODO refactor arguments?*

{{< breadcrumb "Home" "/" "Library" "/library/" "Data" >}}

## Buttons

### Inline Buttons

{{< button >}}Primary{{< /button >}}

{{< button level="success" >}}Success{{< /button >}}

{{< button level="secondary" outline=true >}}Outline{{< /button >}}

{{< button size="sm" >}}Small{{< /button >}}

{{< button size="lg" >}}Large{{< /button >}}

### Block Buttons

{{< button block=true >}}Block level button{{< /button >}}

### Radio Buttons

{{< radio_button active="Buzz" values="Foo|Bar|Buzz" >}}

## Cards

### Image Card

{{< card image="/img/bootstrap.png" caption="My image card" classes="custom-card" />}}

### Text Card

{{< card classes="custom-card" >}}Hello world from my text card{{< /card >}}

### Hybrid Card

{{< card image="/img/bootstrap.png" caption="My hybrid card" classes="custom-card" >}}
    <h5 class="card-title">Card title</h5>
    <h6 class="card-subtitle mb-2 text-muted">Card subtitle</h6>
    <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
    <a href="#" class="card-link">Card link</a>
{{< /card >}}

## Carousel

{{< carousel id="carousel1" classes="small-carousel" active="/img/bootstrap.png" images="/img/bootstrap.png|/img/hugo.png" >}}

### With Controls

{{< carousel id="carousel2" classes="small-carousel" active="/img/bootstrap.png" images="/img/bootstrap.png|/img/hugo.png" controls=true >}}

### With Indicators

{{< carousel id="carousel2" classes="small-carousel" active="/img/bootstrap.png" images="/img/bootstrap.png|/img/hugo.png" indicators=true >}}
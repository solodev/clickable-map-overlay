# clickable-map-overlay
Videos can augment your brand and user impression; with a video background you can overlay text for a clear call-to-action.

## Tutorial
For detailed instruction's, view Solodev's [Clickable Map Overlay](https://www.solodev.com/blog/web-design/clickable-map-overlay.stml) article.

## Demo
  		  
Try out a working example on [JSFiddle](https://jsfiddle.net/solodev/y7monw0h/20).

## HTML

The tutorial contains the following basic HTML markup.

```
<header class="home-hero" role="banner">
	<video autoplay="" id="heroVideo" loop="" muted="" poster="images/hero-video-poster.jpg">
    	<source src="videos/hero-video.mp4" type="video/mp4" />
        <source src="videos/hero-video.webm" type="video/webm" />
        <source src="videos/hero-video.ogg" type="video/ogg" />
    </video>
	<img alt="poster image mobile" class="poster img-fluid mx-auto d-block d-sm-none" src="https://raw.githubusercontent.com/solodev/hero-with-video-bg/master/images/hero-video-poster.jpg" />
	<div class="container h-100">
		<div class="d-flex text-center h-100">
			<div class="my-auto w-100">
				<div class="rectangle d-flex align-items-center justify-content-center p-5">
					<div class="text-center">
						<h2>Get started with Solodev DCX Enterprise</h1>
						<p class="mt-sm-3 px-sm-5 txt">Take your customer experiences to the next level with enterprise features, custom integrations, and dedicated support in your own AWS account.</p>
						<p class="mt-3"><a class="btn text-uppercase font-weight-bold" href="#">Contact Sales</a></p>
					</div>
				</div>
			</div>
		</div>
	</div>
</header>
```

## CSS
All required CSS is contained with hero-with-video-bg.css

## External Resources
This tutorial includes the following third party resources.

```
<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css" integrity="sha384-ggOyR0iXCbMQv3Xipma34MD+dH/1fQ784/j6cY/iJTQUOhcWr7x9JvoRxT2MZw1T" crossorigin="anonymous">
<script src="https://code.jquery.com/jquery-3.3.1.slim.min.js" integrity="sha384-q8i/X+965DzO0rT7abK41JStQIAqVgRVzpbzo5smXKp4YfRvH+8abtTE1Pi6jizo" crossorigin="anonymous"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.7/umd/popper.min.js" integrity="sha384-UO2eT0CpHqdSJQ6hJty5KVphtPhzWj9WO1clHTMGa3JDZwrnQq4sF86dIHNDz0W1" crossorigin="anonymous"></script>
<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/js/bootstrap.min.js" integrity="sha384-JjSmVgyd0p3pXB1rRibZUAYoIIy6OrQ6VrjIEaFf/nJGzIxFDsf4x0xIM+B07jRM" crossorigin="anonymous"></script>
```

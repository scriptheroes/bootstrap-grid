bootstrap-grid
==============

Do you just want Bootstrap's grid? You can find it here with an entirely self-contained files written in Sass. Have fun.


# Sass
```SCSS
	.example--col-xs-1 {
  		@extend %col-xs-1;
	}

	.example--col-md-2 {
		@extend %col-md-2;
	}

	.example--container {
		@extend %container;
	}

```

# CSS Output
```CSS
	.example--container {
	  margin-right: auto;
	  margin-left: auto;
	  padding-left: 15px;
	  padding-right: 15px;
	}
	.example--container:before, .example--container:after {
	  content: " ";
	  display: table;
	}
	.example--container:after {
	  clear: both;
	}
	@media (min-width: 768px) {
	  .example--container {
	    width: 750px;
	  }
	}
	@media (min-width: 992px) {
	  .example--container {
	    width: 970px;
	  }
	}
	@media (min-width: 1200px) {
	  .example--container {
	    width: 1170px;
	  }
	}

	.example--col-xs-1, .col-lg-1, .example--col-md-2 {
	  position: relative;
	  min-height: 1px;
	  padding-left: 15px;
	  padding-right: 15px;
	}

	.example--col-xs-1 {
	  float: left;
	}

	.example--col-xs-1 {
	  width: 8.33333%;
	}

	@media (min-width: 1200px) {
	  .example--col-md-2 {
	    float: left;
	  }

	  .example--col-md-2 {
	    width: 16.66667%;
	  }
	}

```


# MaterialModal

inspired by [Material Design](https://material.google.com/),
MaterialModal is the perfect modal for your projects.

## Installation

*1. Add the following CSS to your Header:*


```
<link href="assets/js/materialmodal.css" rel="stylesheet">
```

*1. Add the following JS to your Footer:*

```
<script src="assets/js/materialmodal.min.js"></script>
```

## Usage
*1. Place this somewhere in the \<body\>*

```
<!-- Modal Trigger -->
<button class="mm-trigger">Click Here</button>

<!-- Modal Content -->
<div id="modal-content">
	<!-- put modal content in here -->
</div>
```
*2. Place at the bottom of your body or include via script*

```
<script>
	(function(){
		var $content = $('#modal-content').detach();
		$(.mm-trigger).on('click', function() {
			modal.open({
				content: $content, 
				width: 340, 
				height:300
			});
		});
	}());
</script>
```


* Source: [github.com/drewpark88/materialmodal](http://github.com/drewpark88/materialmodal)
* HomePage: [MaterialModal](https://github.com/drewpark88/materialmodal)


## License

#### The MIT License (MIT)

Copyright (c) MaterialModal

Permission is hereby granted, free of charge, to any person obtaining a copy of
this software and associated documentation files (the "Software"), to deal in
the Software without restriction, including without limitation the rights to
use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies
of the Software, and to permit persons to whom the Software is furnished to do
so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.


## bootstrap3-markdown

# [live demo](http://suhailvs.github.io/bootstrap3-markdown/)

Markdown is a lightweight markup language, allowing people to write using an easy-to-read, easy-to-write plain text format, then convert it to structurally valid XHTML.

the js files are taken from <https://github.com/kevinoconnor7/pagedown-bootstrap/>

### Usage

**HTML: Create Textarea**

	<style type="text/css">
   		.wmd-panel{width:100%; border:5px solid #ccc; padding: 5px}
		.wmd-input{height:300px;width:100%;}
		.wmd-preview{width:100%;border-top:5px solid #ccc;}
	</style> 
	<textarea id="pagedownMe"></textarea>


**Script: initiate `jquery` and `jquery.pagedown-bootstrap`**

	<script src="https://ajax.googleapis.com/ajax/libs/jquery/1.11.0/jquery.min.js"></script>
	<script type="text/javascript" src="jquery.pagedown-bootstrap.min.js"></script>
	
	<!-- make the textarea Pagedown -->
	<script type="text/javascript">
	(function () {	 
		$("textarea#pagedownMe").pagedownBootstrap();	 
	})();
	</script>



<div class="text-dark bg-light py-3">
<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css" integrity="sha384-ggOyR0iXCbMQv3Xipma34MD+dH/1fQ784/j6cY/iJTQUOhcWr7x9JvoRxT2MZw1T" crossorigin="anonymous">
	<link href="https://fonts.googleapis.com/css?family=Open+Sans:400,700" rel="stylesheet"> 
	<link href="https://fonts.googleapis.com/css?family=Source+Code+Pro" rel="stylesheet"> 
	<link rel="stylesheet" href="https://felipetravassos.com/cleanalert/dist/cleanalert.css">
    <style>
<div class="container">
<div class="jumbotron">
  <h1 class="display-4">Clean Alert</h1>
  <p class="lead">A plugin to print beautiful and clean alert modals</p>
  <hr class="my-4">
  <p>Require <a href="https://getbootstrap.com/" title="Bootstrap 4">Bootstrap 4</a>, <a href="https://popper.js.org/" title="Popper.js">Popper.js</a> and <a href="https://jquery.com/" title="Jquery">Jquery</a></p>

</div>

<h4>Examples</h4>

<h5>Types:</h5>

<button class="btn btn-info clenalertbtn" data-title="Info Alert" data-text="This is a info alert" data-type="info" >Info Alert</button>
<button class="btn btn-warning clenalertbtn" data-title="Warning Alert" data-text="This is a warning alert" data-type="warning">Warning Alert</button>
<button class="btn btn-success clenalertbtn" data-title="Success Alert" data-text="This is a success alert" data-type="success">Success Alert</button>
<button class="btn btn-danger clenalertbtn" data-title="Danger Alert" data-text="This is a danger alert" data-type="danger">Danger Alert</button>

<div class="alert alert-secondary mt-3">
<small>
&lt;button class="btn btn-info clenalertbtn" data-title="Info Alert" data-text="This is a info alert" data-type="info" &gt;Info Alert&lt;/button&gt;<br>&lt;button class="btn btn-warning clenalertbtn" data-title="Warning Alert" data-text="This is a warning alert" data-type="warning"&gt;Warning Alert&lt;/button&gt;<br>&lt;button class="btn btn-success clenalertbtn" data-title="Success Alert" data-text="This is a success alert" data-type="success"&gt;Success Alert&lt;/button&gt;<br>&lt;button class="btn btn-danger clenalertbtn" data-title="Danger Alert" data-text="This is a danger alert" data-type="danger"&gt;Danger Alert&lt;/button&gt;<br>
</small>
</div>

<hr class="my-4">
<h5>Sizes:</h5>
<button class="btn btn-info clenalertbtn" data-title="Small Info Alert" data-text="This is a small info alert" data-type="info" data-size="sm" >Small Info Alert</button>
<button class="btn btn-info clenalertbtn" data-title="Medium Info Alert" data-text="This is a medium info alert" data-type="info" data-size="md" >Medium Info Alert</button>
<button class="btn btn-info clenalertbtn" data-title="Large Info Alert" data-text="This is a large info alert" data-type="info" data-size="lg" >Large Info Alert</button>
<div class="alert alert-secondary mt-3">
<small>
&lt;button class="btn btn-info clenalertbtn" data-title="Small Info Alert" data-text="This is a small info alert" data-type="info" data-size="sm" &gt;Small Info Alert&lt;/button&gt;<br>&lt;button class="btn btn-info clenalertbtn" data-title="Medium Info Alert" data-text="This is a medium info alert" data-type="info" data-size="md" &gt;Medium Info Alert&lt;/button&gt;<br>&lt;button class="btn btn-info clenalertbtn" data-title="Large Info Alert" data-text="This is a large info alert" data-type="info" data-size="lg" &gt;Large Info Alert&lt;/button&gt;
</small>
</div>

<hr class="my-4">
<h5>BG color:</h5>
<button class="btn btn-info clenalertbtn" data-title="Light Alert" data-text="This is a light info alert" data-type="info" data-bg="light" >Light Modal</button>
<button class="btn btn-info clenalertbtn" data-title="Dark Alert" data-text="This is a dark info alert" data-type="info" data-bg="dark" >Dark Modal</button>
<div class="alert alert-secondary mt-3">
<small>
&lt;button class="btn btn-info clenalertbtn" data-title="Light Alert" data-text="This is a light info alert" data-type="info" data-bg="light" &gt;Light Modal&lt;/button&gt;<br>&lt;button class="btn btn-info clenalertbtn" data-title="Dark Alert" data-text="This is a dark info alert" data-type="info" data-bg="dark" &gt;Dark Modal&lt;/button&gt;
</small>
</div>


<hr class="my-4">
<h5>Button:</h5>
<button class="btn btn-info clenalertbtn" data-title="Info Alert w/ Danger Button" data-text="This is a info alert" data-type="info" data-btntype="danger" >Info Alert w/ Danger Button</button>
<button class="btn btn-info clenalertbtn" data-title="Info Alert w/ Custom Button Text" data-text="This is a info alert" data-type="info" data-btntext="Okay" >Info Alert w/ Custom Button Text</button>
<div class="alert alert-secondary mt-3">
<small>
&lt;button class="btn btn-info clenalertbtn" data-title="Info Alert w/ Danger Button" data-text="This is a info alert" data-type="info" data-btntype="danger" &gt;Info Alert w/ Danger Button&lt;/button&gt;<br>&lt;button class="btn btn-info clenalertbtn" data-title="Info Alert w/ Custom Button Text" data-text="This is a info alert" data-type="info" data-btntext="Okay" &gt;Info Alert w/ Custom Button Text&lt;/button&gt;
</small>
</div>
<hr class="my-4">
<h5>Direct Call:</h5>

<div class="alert alert-secondary mt-3">
<small>
&lt;script&gt;<br>&nbsp;&nbsp; &nbsp;callalert(title, text, type, btntext, btntype, size, bg);<br>&lt;/script&gt;
</small>
</div>

</div>
	
<script src="https://code.jquery.com/jquery-3.4.0.min.js"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.7/umd/popper.min.js" integrity="sha384-UO2eT0CpHqdSJQ6hJty5KVphtPhzWj9WO1clHTMGa3JDZwrnQq4sF86dIHNDz0W1" crossorigin="anonymous"></script>
<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/js/bootstrap.min.js" integrity="sha384-JjSmVgyd0p3pXB1rRibZUAYoIIy6OrQ6VrjIEaFf/nJGzIxFDsf4x0xIM+B07jRM" crossorigin="anonymous"></script>
<script  src="https://felipetravassos.com/cleanalert/dist/cleanalert.js"></script>

<script>



Version - 0.4
by Felipe Travassos

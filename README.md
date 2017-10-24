# jQuery Honeycombs
jQuery plugin for displaying images in a responsive Honeycomb/ Hexagon grid with caption and anchor


## Honeycomb/ Hexagon Grid
To create a Honeycomb/ Hegagon grid, use the following HTML markup:

```
<div class="honeycombs">
    <div class="comb">
      <img src="https://farm6.staticflickr.com/5737/31044656732_c031f1294c_z.jpg" /> 
    </div>
    <div class="comb">
      <img src="https://farm6.staticflickr.com/5727/30785062315_cb44d0c372_z.jpg" /> 
    </div>
    <div class="comb">
      <img src="https://farm8.staticflickr.com/7091/27557985951_7abf426c1e_z.jpg" /> 
    </div>
</div>
```

Add the following Javascript snippet at the bottom of the page,

```
<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.2.1/jquery.min.js"></script>
<script src="homeycombs/js/jquery.homeycombs.js"></script>

<script type="text/javascript">
    $(document).ready(function () {
        $('.honeycombs').honeycombs();
    });
</script>
```

## Honeycomb/ Hexagon Grid With Caption
To create a Honeycomb/ Hegagon grid, use the following HTML markup:

```
<div class="honeycombs">
    <div class="comb">
      <img src="https://farm6.staticflickr.com/5737/31044656732_c031f1294c_z.jpg" />
      <span>
        <br>
        jQuery Honeycombs
      </span>
    </div>

    <div class="comb">
      <img src="https://farm6.staticflickr.com/5727/30785062315_cb44d0c372_z.jpg" /> 
        <span>
            <b>Image</b>
            <br>Caption
        </span>
    </div>

    <div class="comb">
      <img src="https://farm8.staticflickr.com/7091/27557985951_7abf426c1e_z.jpg" /> 
    </div>
</div>
```

Add the following Javascript snippet at the bottom of the page,

```
<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.2.1/jquery.min.js"></script>
<script src="homeycombs/js/jquery.homeycombs.js"></script>

<script type="text/javascript">
    $(document).ready(function () {
        $('.honeycombs').honeycombs();
    });
</script>
```
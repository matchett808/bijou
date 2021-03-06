#Bijou

A small (less than 10 kb) CSS framework, Based on the origional 2 kb version by andhart...

Example: http://matchett808.github.io/bijou

Based on Bijou by @andhart - https://github.com/andhart/bijou

###Navbar:

```html
<div class='navbar fixed'>
   <div class='container'>
      <h4 class='pull-left'>Bijou</h4>
   </div>
</div>
```

or a navbar with navigation:

```html
<div class='navbar fixed'>
   <div class='container'>
      <h4 class='pull-left'>Bijou</h4>
      <ul class='pull-right'>
         <li><a href='#'>Link</a></li>
         <li><a href='#'>Link</a></li>
         <li><a href='#'>Link</a></li>
      </ul>
   </div>
</div>

```

Add a `fixed` class to the navbar to make it fixed to the top of the screen (Make sure you also add `margin-top:50px` to the body if you make it fixed). 

***

###Table:

```html
<table class='table'>
   <thead>
      <tr>
         <th>Test</th>
         <th>Test</th>
         <th>Test</th>
         <th>Test</th>
      </tr>
    </thead>
    <tbody>
       <tr>
         <td>Test</td>
         <td>Test</td>
         <td>Test</td>
         <td>Test</td>
       </tr>
    </tbody>
</table>
```

This will style just a plain table. If you want it striped, add the `table-striped` class, or if you want it bordered, the `table-bordered` class.

***

###Buttons

```html
<button class='button danger large'>Test</button>
<button class='button primary large'>Test</button>
<button class='button success large'>Test</button>

<button class='button danger small'>Test</button>
<button class='button primary small'>Test</button>
<button class='button success small'>Test</button>
```

Large buttons have the `large` class, while small have the `small` class. Easy, isn't it?

***

###Alerts

```html
<div class='alert primary'><p>Test</p></div>
<div class='alert success'><p>Test</p></div>
<div class='alert danger'><p>Test</p></div>
```

***

###Grid

Bijou has a responsive 10 column grid.

For an example, the following will create a one column span and and a nine-column span:

```html
<div class='row'>
   <div class='span one'>ONE</div><div class='span nine'>NINE</div>
</div>
```


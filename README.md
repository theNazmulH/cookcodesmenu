# cookcodesmenu v1.0
## Responsive Mobile Menu jQuery Plugin
* * *
###  [Demo](https://nazmulh.github.io/cookcodesmenu/demo/)


### Usage

#### Include the CSS

	<link type="text/css" rel="stylesheet" href="https://cdn.rawgit.com/nazmulh/cookcodesmenu/master/cookcodesmenu.min.css" />


#### Include the JS
    
    <script type="text/javascript" src="https://cdn.rawgit.com/nazmulh/cookcodesmenu/master/jquery.cookcodesmenu.min.js"></script>


#### Menu Markup

    <ul id="menu">
        <li><a href="#">item 1</a></li>
        <li><a href="#">item 2</a></li>
        <li><a href="#">item 3</a></li>
        <li><a href="#">item 4</a></li>
    </ul>
    

#### Initialize

    <script>
        $(function(){
            $('#menu').cookcodesmenu();
        });
    </script>

### Options
            display: 767, // From where mobile menu apears and desktop  menu gone
 	        label: 'MENU', // html supports
	        brand: 'LOGO', // html supports
            duplicate: true,
            duration: 200,
            easingOpen: 'swing',
            easingClose: 'swing',
            closedSymbol: "&#10133;", // html supports
            openedSymbol: "&#10134;",  // html supports
            prependTo: 'body',
            appendTo: '',
            parentTag: 'a',
            closeOnClick: true,
            allowParentLinks: true,
            nestedParentLinks: true,
            showChildren: false,
            removeIds: true,
            removeClasses: false,
            removeStyles: false,

=======
# cookcodesmenu
Responsive Mobile Menu jQuery Plugin

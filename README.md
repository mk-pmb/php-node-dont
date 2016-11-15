
<!--#echo json="package.json" key="name" underline="=" -->
php-node-dont
=============
<!--/#echo -->

<!--#echo json="package.json" key="description" -->
(Don&#39;t use this.) Adapter for serving web on the lowest common
denominator: Combine the worst aspects of cgi-node with the worst aspects of
PHP.
<!--/#echo -->

If [invoking node via CGI](http://www.cgi-node.org/) isn't demented enough
for your very special case of totally adequate ninja corner-case scenario,
you <i>could*</i> add a layer of PHP between your browser and your node app.

(* You shouldn't. Ask #node.js on FreeNode IRC for better solutions.)




Usage
-----

1. Blog about why you think you deserve to suffer,
   and why you chose this method.
2. Consider trying self-flagelation instead.
3. `cd /var/www/gfmo && npm install --save php-node-dont`
4. Read the source because there's no proper docs.


<!--#toc stop="scan" -->



License
-------
<!--#echo json="package.json" key=".license" -->
ISC
<!--/#echo -->

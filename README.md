
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



Deprecated!
-----------

"Finally, I found a valid usecase for this!", I thought.
However, a few minutes after starting to implement it,
I remembered I (and you) could just use
[`cgi-emu.php` from phutility][cgi-emu] instead,
so I guess that's the final nail to the coffin.

  [cgi-emu]: https://github.com/mk-pmb/phutility-160816-pmb/blob/master/web/cgi-emu.php




Usage
-----

1. Blog about why you think you deserve to suffer,
   and why you chose this method.
2. Consider trying self-flagelation instead.
3. <del>`cd /var/www/gfmo && npm install --save php-node-dont`</del>
4. <del>Read the source because there's no proper docs.</del>
5. See deprecation notice above and consider using the cgi-emu instead.


<!--#toc stop="scan" -->


Known issues
------------

* The `PATH_TRANSLATED` variable is not provided, and that's
  [not a bug](https://bugs.php.net/bug.php?id=23610#1052878041).




License
-------
<!--#echo json="package.json" key=".license" -->
ISC
<!--/#echo -->

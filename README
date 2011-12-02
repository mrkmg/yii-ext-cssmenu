Css Menu extenstion For Yii 1.1

Copyright Kevin Gravier 2011.
     
     Copying and distribution of this file, with or without modification,
     are permitted in any medium without royalty provided the copyright
     notice and this notice are preserved.


** How to Install **

	Copy the folder 'cssmenu' to the extenstions folder in your Yii Installation

** How to Use **
	Place the following where you would like the menu to appear. Css Menu conforms to the standard for
	menus as defined by CMenu in Yii Version 1.1*
	
	http://www.yiiframework.com/doc/api/1.1/CMenu
	
	
	
	<? $this->widget('ext.cssmenu.CssMenu',array(
	    'items'=>array(
	        array('label'=>'Home', 'url'=>array('site/index')),
	        array('label'=>'Products', 'url'=>array('product/index'), 'items'=>array(
	            array('label'=>'New Arrivals', 'url'=>array('product/new')),
	            array('label'=>'Most Popular', 'url'=>array('product/index')),
	        )),
	        array('label'=>'Login', 'url'=>array('site/login'), 'visible'=>Yii::app()->user->isGuest),
	    ),
	)); ?>


*the "tag" option was not included.
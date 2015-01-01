#Search API autocomplete for an input box

##Purpose :
IF you are using search API with Acquia solr search and need a autocomplte widget for search results.
Search API autocomplete does the job. But if you just have a input box in your tpl files and you are using it for search 
and need to add autocomplete feature on it then this module can be used.

Example : 

<input type="text">

<input class="auto_submit form-text form-autocomplete" type="text" id="gk_search_box" name="keys" value="" size="60" maxlength="128" autocomplete="OFF" aria-autocomplete="list" placeholder="searhbox">




##Usage :
 - install module.
 - enable the module and setup up as shown in enable_search.png

 Then in any tpl file you can print this.
 
##<? print drupal_render(drupal_get_form ('gk_search_form')); ?>

It will print a searcbox with AutoComplete dropdown. 


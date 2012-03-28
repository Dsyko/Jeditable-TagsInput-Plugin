
## Jeditabel Tags Input

In place editing with a Tagsinput. Clean and simple. Based on Jeditable and Tagsinput.

## Background

 * [Jeditable](http://www.appelsiini.net/projects/jeditable) is an in place editing plugin for jQuery.
 * [Tagsinput](http://xoxco.com/projects/code/tagsinput/) is a tag editing plugin for jQuery
 * Jeditable works with several types of input fields out of the box, like text fields and text area fields.
 * You can write your own plugins for Jeditable to support in place editing of other types of input fields. 
 * Jeditable-Tags-Input is a Jeditable plugin to add the jQuery Tags Input plugin. Yep a plugin for a plugin for a plugin.

## Demo

Coming Soon?

## Tested

Firefox, Chrome

## Usage

Example 1:

    $( '.editable' ).editable( {
      type: 'tagsinput'
    } );

Example 2: (passing options to tagsinput):

    $( '.editable' ).editable( {
      type: 'tagsinput',
      tagsinput: {
        'height':'100px',
		'width':'300px',
		'interactive':true,
		'defaultText':'add a tag',
		'onAddTag':callback_function,
		'onRemoveTag':callback_function
      }
    } );

## Dependencies

 * [jQuery] (http://www.jquery.com/)
 * [Jeditable](http://www.appelsiini.net/projects/jeditable)
 * [jQuery Tagsinput](http://xoxco.com/projects/code/tagsinput/)

## Installation

Inlude jquery.jeditable.tagsinput.js in your project _after_ jquery.js, jquery.jeditable.js and jquery.tagsinput.js or their minified varients.

## License

Released under the MIT license. Copyright (C) 2012 David 'Dsyko' Sykora.